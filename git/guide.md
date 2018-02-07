
## Trabalhando no master
Command | Description
--------|------------
git merge [branch] | utilizado para enviar alterações do branch para a master
git revert | serve para o master


## Trabalhando em branches
Command | Description
--------|------------
git reset | bom para branches separadados (o contrário do merge)
git commit -- force | para enviar alterações no histório. Não é uma boa prática utilizar no master
git pull -- rebase | utilizado para puxar itens do master para a branch


## Trabalhando antes de enviar para o repositório remoto
Command | Description
--------|------------
git commit -- amend | para alterar a descrição de um commit ou adicionar mais modificações ao commit anterior
git stash | guarda alterações que podem ser acessadas no futuro mas que não quero que entre em um próximo commit (por exemplo)
