# # Bem-vindo a primeira wiki ComandosLinux!
## `ls` 
lista os arquivos de um diretório onde no formato caminho/arquivo
### Exemplo:
**`ls Documents`**

Mostra os diretórios e pastas do diretório "Documents".

**`ls Documents/teste`**

Mostra os diretórios e pastas do diretório "teste".

**`ls -a, --all`**

lista todos os arquivos incluindo os ocultos de um diretório.

**`ls -A, --almost-all`**

A diferença aqui é que este lista todos os arquivos de um diretório, exceto o diretório atual e o de nível anterior.

Pode se utilizar como: `ls -a Documents` o mesmo se aplica para ls -A.

**`ls -b, -- ignore-backups`**

lista arquivos que **não** contém ~ (backup)

**`ls --color`** 

É utilizado para mostrar o arquivo em diferentes cores.

**`ls --color=never`** - Nunca lista em cores (mesma coisa de não usar o
parâmetro --color).

**`ls --color=always`** - Sempre lista em cores conforme o tipo de arquivo.

**`ls --color=auto`** - Somente colore a listagem se estiver em um terminal.

**`ls -d, --directory`**

lista o diretório pelo nome e não pelo conteúdo

**`ls -f`**

Não classifica a listagem

**`ls -F`**

Insere um caracter após arquivos executáveis ('*'), diretórios ('/'),
soquete ('='), link simbólico ('@') e pipe ('|'). Seu uso é útil
para identificar de forma fácil tipos de arquivos nas listagens de
diretórios.

**`ls -g`**

Oculta o grupo do arquivo 
### Exemplo:
`drwxr-xr-x 2 kali 4096 Apr 23 18:23 Documents`

drwxr-xr-x -> permissões

2 -> número de links

kali -> grupo

4096 -> tamanho

Dec 30 19:05 -> data

Documents -> nome

**`ls -h, human-readable`**

Mostra o tamanho dos arquivos em Kbytes, Mbytes, Gbytes.
**`ls -H`**

Faz o mesmo que `ls -h`, mas usa unidades de 1000 ao invés de 1024 para especificar Kbytes, Mbytes, Gbytes.

**`ls -l`**

Semelhante ao `ls -g` a única diferença é que este comando mostra o grupo e o dono.

**`Ls -n`** 
Usa ID numérico de usuário e grupo (em vez de nomes)
**`Ls-L`** 
Mostra o arquivo original (não o link simbólico)
**`Ls-o`** 
Listagem longa sem mostrar o dono

**`Ls-p`** 
 Adiciona / no final dos diretórios
**`Ls-R`** 
 Lista diretórios e subdiretórios (recursivo)
**`Ls--full-time`**
 Mostra data e hora completas
**`Ls-f`** 
 Não ordena e já usa -a e -u
**`ls-r`**
 Inverte a ordem da listagem
**`ls -c`** 
 Ordena pela data de alteração
**`ls-X`** 
 Ordena pela extensão
**`ls-U`**
 Não ordena (ordem original do diretório)
**`ls-Z`** 
 Mostra o contexto de segurança (SELinux)

Exemplos do uso do comando ls:
**`ls`** 

Lista os arquivos do diretório atual.

**`ls/bin/sbin`** 

Lista os arquivos do diretório /bin e /sbin

**`ls -la /bin`**

Listagem completa (vertical) dos arquivos do diretório /bin inclusive os ocultos.

**`PWD`**
Mostra o nome e caminho do diretório atual.
Você pode usar o comando pwd para verificar em qual diretório se encontra (caso seu aviso de comandos
não mostre isso).
