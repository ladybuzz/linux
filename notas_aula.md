# Aula 01 | Trabalhando com arquivos e diretórios

`pwd` - mostra o diretório que eu estou atualmente

`ls` - mostra a lista de arquivos no diretório

`ls -l`- mostra informações sobre arquivos e diretórios ( quando a linha inicia com d é um diretório, também mostra o grupo e o usuario, o tamanho do arquivo e a data e hora de modificação)

`ls -a` - mostra todos (a de all) os arquivos, incluindo invisíveis (iniciados pelo caractere .) podemos usar a combinação `ls -la` 

`echo Bem vindo` - echo (repetir) diz para o terminal falar Bem vindo

Setas direcionais para cima e para baixo  - recupera comandos digitados

`echo "Bem vindo" > bemvindo.txt` - redireciona a frase para um arquivo txt

`cat bemvindo.txt` - mostra o conteúdo de texto do arquivo bemvindo.txt

A tecla `tab` ajuda a completar o nome de um arquivo que você iniciou a digitação

`clear`- limpar a tela do terminal (atalho Ctrl + L)

`man [comando]`- abre o manual de ajuda sobre o comando informado (para sair do manual basta clicar em q)

`whoami` - mostra o nome do usuário no linux que está sendo usado

# Aula 02 |  Mais sobre redirecionamento e caracteres coringa no bash

`cd` - volta para o diretório base

`cd [Nome Diretorio]` - mudar para o diretório informado, cd é de change directory

`cd home/joseline/diretorio`- vai para um diretório especificado pelo caminho passado (atalho cd ~/diretorio)

`echo "Nova mensagem" >> bemvindo.txt` - adiciona a nova mensagem ao arquivo bemvindo.txt. Se você usar o > você sobrescreve o que estava guardado anteriormente

`cd ..` - voltar para o diretório anterior

`ls .` - mostra o conteúdo do diretório atual(.)

`ls ..`- mostra o conteúdo do diretório anterior(..)

`ls /`- mostra o conteúdo do diretório raiz(/)
/home é onde ficam os arquivos dos usuários da máquina

`mkdir [Nome diretorio]` - cria um novo diretório com o nome informado

`rmdir [nome diretorio]`- remove o diretorio informado. Só apaga diretórios vazios.

`rm [arquivo.ext]`- apagar arquivo

`cat [arquivo?.txt]` - a interrogação serve como um coringa, assim o comando é aplicado para todo arquivo que tiver um caractere qualquer no lugar da ?

`cat [arquivo*.txt]` - o asterisco serve como um coringa, assim o comando é aplicado para todo arquivo que tiver um número qualquer de caracteres no lugar do *. Caso você tenha um arquivo chamado *.txt você tem que colocar aspas para o terminal interpretar como texto.

`rm -r [nome diretorio]`- remove recursivamente o conteúdo do diretório informado

# Aula 03 | Manipulando, compactando e descompactando arquivos


# Aula 04 |


# Aula 05 |