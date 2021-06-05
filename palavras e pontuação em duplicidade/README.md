Macros de revisão de texto para uso com Notepad++, para encontrar palavras e sinais de pontuação em duplicidade.

Talvez não seja tão poderoso como em outros editores, mas o suporte a macros é nativo no Notepad++ (não depende de plugins) e nunca me deixou na mão. 

Há duas macros inclusas em "shortcuts_macros_de_revisao.xml"
"Search double." Macro para achar exatamente dois pontos (..) e exatamente dois espaços (  )
"Search doublew" Macro para achar palavras repetidas

Copie o código contido dentro do arquivo e cole o código antes da seguinte linha em seu arquivo shortcuts.xml:
    </Macros>
    
Para acessar a pasta na qual Notepad++ guarda shortcuts.xml, digite o seguinte na barra de endereços do Windows Explorer:
%appdata%\Notepad++

É uma macro de localização e não de substituição, visto que algumas vezes você realmente pode querer manter as coisas como estão.
