Author: Guilherme Mangabeira Gregio
E-mail: guilherme@gregio.net
Version: 0.2


Criando um repositório vazio
Crie a pasta no seu computador e acesse esta pasta. Ex:
mkdir curso-git
cd curso-git

Informando para o git que esta pasta sera versionada
git init

Crie os arquivos que deseja no diretório;

Verificar quais arquivos estão no git
git ls-files

Verificar modificações, arquivos não trakeados, etc
git status

Adicionar arquivos para o git
git add NOME_ARQUIVO

Adicionar tudo
git add .

Configurar no usuario e email que o blame captura
git config user.name "João Carlos Fonseca"
git config user.email "jcfonsecagit@gmail.com"

Configurar o usuario e email pro sistema inteiro
git config --global user.name "João Carlos Fonseca"
git config --global user.email "jcfonsecagit@gmail.com"

Fazer um commit
git commit -m 'MENSAGEM'

Adicionar e fazer commit
git commit -am 'MENSAGEM'

Configurar repositório remoto
git remote add origin git@github.com:[seu_nome_de_usuario]/[node_do_repositorio].git.

Enviar os commits locais para o repositorio remoto
git push origin master

Sincronizando com o repositorio remoto
git pull origin master

Copiando um projeto do Github para sua maquina:

git clone git://github.com/[USER]/[REPOSITORIO].git 

Tag's

Listar tags
git tag

Criar uma tag
git tag NOME

Substituir uma tag
git tag NOME -f

Comparar diferença entre tags
git diff TAG1 TAG2

Ir para uma tag especifica
git checkout TAG_NAME

Descobrir que alterou o arquivo linha a linha
git blame NOME_DO_ARQUIVO

Visualizar logs de commits
git log

Visualizar o que sofreu alteração
git whatchanged 

Trabalhando com branch's

Listar branch's 
git branch

Note que o "*" mostra em qual branch estamos no momento

Criar uma branch
git branch NOME_DA_BRANCH

Ir para uma branch especifica
git checkout NOME_DA_BRANCH

Enviar um branch para o repositorio remoto
git push origin NOME_DA_BRANCH

Para não precisar digitar origin NOME_DA_BRANCH no push e pull
git push -u origin NOME_DA_BRANCH

Visualizar branch's remoto
git branch -r

Copiar uma branch remota para o local
git branch -t NOME_DA_BRANCH origin/NOME_BRANCH_REMOTA

end of file