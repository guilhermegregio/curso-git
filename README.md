Author: Guilherme Mangabeira Gregio
E-mail: guilherme@gregio.net
Version: 0.2


Criando um repositório vazio
Crie a pasta no seu computador e acesse esta pasta. Ex:
mkdir curso-git
cd curso-git

Informando para o git que esta pasta sera versionada
git init

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