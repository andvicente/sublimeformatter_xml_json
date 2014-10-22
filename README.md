Formatando arquivos XML e JSON no Sublime Text 3

Passo 1: Adicione os arquivos prettify_json.py e tidy_xml.py 
         - Menu Preferences -> Browse packages… 
         - Irá abrir uma nova janela apontando para $HOME/.config/sublime-text-3/Packages
         - Cole os dois arquivos nessa pasta
         
Passo 2: Configurar os atalhos do teclado para formatar o JSON e o XML
         - Menu Preferences -> Key Bindings – User.
         - Irá abrir um arquivo no Sublime
         - Edite e cole o seguinte texto:
         
```<JSON>
[
    { "keys": ["ctrl+shift+x"], "command": "tidy_xml" },
    { "keys": ["ctrl+shift+j"], "command": "prettify_json" }
]
```

Como utilizar:
		Formatar XML: ctrl + shift + x
		Formatar JSON: ctrl + shift + j

Fontes: http://blog.bytenoodles.com/sublime-text-3-plugins-get-pretty-xml-json
