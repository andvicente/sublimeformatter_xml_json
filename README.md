Formatando arquivos XML e JSON no Sublime Text 3

<b>Passo 1:</b> Adicione os arquivos prettify_json.py e tidy_xml.py 
<ul>
  <li>Menu Preferences -> Browse packages… </li>
  <li>Irá abrir uma nova janela apontando para $HOME/.config/sublime-text-3/Packages</li>
  <li>Cole os dois arquivos nessa pasta</li>
</ul>
        
<b>Passo 2:</b> Configurar os atalhos do teclado para formatar o JSON e o XML
<ul>
  <li>Menu Preferences -> Key Bindings – User</li>
  <li>Irá abrir um arquivo no Sublime</li>
  <li>Edite e cole o seguinte texto:</li>
</ul>
```<JSON>
[
    { "keys": ["ctrl+shift+x"], "command": "tidy_xml" },
    { "keys": ["ctrl+shift+j"], "command": "prettify_json" }
]
```
<b>Passo 3 (opcional):</b> Adicionar formatador no MENU Selection -> Format
<ul>
  <li>Colar o arquivo Main.sublime-menu seguindo os mesmas etapas do PASSO 1</li>
</ul>



Como utilizar:
<ul>
  <li><b>Formatar XML:</b> ctrl + shift + x</li>
  <li><b>Formatar JSON:</b> ctrl + shift + j</li>
</ul>
		
		

<b>Fonte:</b> <a href="http://blog.bytenoodles.com/sublime-text-3-plugins-get-pretty-xml-json">http://blog.bytenoodles.com/sublime-text-3-plugins-get-pretty-xml-json</a>
