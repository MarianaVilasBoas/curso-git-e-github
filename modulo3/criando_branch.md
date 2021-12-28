cle# criando uma nova branch
git checkout -b modulo3

# conferindo branchs
git branch

# mudando de branch
git checkout [nome da branch]

# para criar branch pelo github
1. acessar o repositorio
2. ir na listagem de branch
3. inserir o nome da nova branch
4. confirmar a criacao da nova branch

# exlcuir branch pelo github
1. va a sessao de listagem de branchs
2. excluir na lixeira

# push
definir a upstream no github, difinir upstream no github que ate entao estava local
git push --set-upstream origin modulo3

# merge branchs
ir para a branch que deseja adicionar a outra branch
git merge [nome da branch que deseja adicionar] 
commit do merge e feito automaticamente