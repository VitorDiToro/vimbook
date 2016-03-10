Comparando arquivos com o vimdiff
---------------------------------

O vim possui um modo para checagem de diferenças entre arquivos, é
bastante útil especialmente para programadores, para saber quais são as
diferenças entre dois arquivos faz-se:

        vimdiff arquivo1.txt arquivo2.txt .. exibe as diferenças
        ]c ................................. mostra próxima diferença
        vim -d ............................. outro modo de abrir o
                                             vimdiff mode

Para usuários do GNU/Linux é possível ainda checar diferenças
remotamente assim:

        vimdiff projeto scp://usuario@estacao//caminho/projeto

O comando acima irá exibir lado a lado o arquivo local chamado
`projeto` e o arquivo remoto contido no computador de nome
`estacao` de mesmo nome.

[^1]: Espaçamento entre o começo da linha e o início do texto

[^2]: Em códigos Python por exemplo não se pode misturar espaços e
    tabulações

[^3]: Abreviação para um comando do GNU/Linux