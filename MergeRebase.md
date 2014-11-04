# Merge

Merge básico

Entrar no diretório que deseja fazer o merge por exemplo no master;
Executar o comando merge;
Informar a mensagem de merge;
Caso haja conflito, corrigi-los;
Fazer os commits;

git checkout master
git merge <nome_da_branch_para_merge> -m "Mensagem do Commit"


# Rebase

Entrar no diretório que deseja fazer o rebase por exemplo no master;
Executar o comando rebase;
Caso haja conflito, corrigi-los e adicionar com o git add;
Executar o comando git rebase --continue;
Pode ser utilizado --abort, --skip e --continue

git checkout master
git rebase <nome_da_branch_para_rebase>

