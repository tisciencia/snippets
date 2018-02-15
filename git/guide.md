# Comandos

### Básico
Command | Description
--------|------------
git init | inicializar o uso do git em um diretório
git add [./file] | adicionar arquivos
git commit -m [message] | comitar arquivos
git pull [origin] [branch] | puxar alterações 
git push [origin] [branch] | enviar alterações
git push [origin] [branch] --tags | enviar alterações e as tags
git checkout [branch] | para trocar de branch
git checkout -b [new branch] | cria um novo branch e troca o atual para o novo

### Trabalhando no master
Command | Description
--------|------------
git merge [branch] | utilizado para enviar alterações do branch para a master
git revert | serve para o master


### Trabalhando em branches
Command | Description
--------|------------
git reset | bom para branches separadados (o contrário do merge)
git commit -- force | para enviar alterações no histório. Não é uma boa prática utilizar no master
git pull -- rebase | utilizado para puxar itens do master para a branch


### Trabalhando antes de enviar para o repositório remoto
Command | Description
--------|------------
git commit -- amend | para alterar a descrição de um commit ou adicionar mais modificações ao commit anterior
git stash | guarda alterações que podem ser acessadas no futuro mas que não quero que entre em um próximo commit (por exemplo)
git stash apply | para obter as modificações que haviam sido guardadas


### Diversos
Command | Description
--------|------------
git log | visualizar o histórico de commits
git cherry-pick [hash] | pegar um commit específico
git checkout - | retorna para o brach anterior
git add -p | comitar partes de um mesmo arquivo
git show | mostrar o que foi alterado no commit
git rebase -i | para modificar o histórico (deletar commits, juntar commits, etc)
git commit --fixup [hash] | para corrigir um commit anterior
git merge --continue | serve para seguir com o merge após as correções dos conflitos
git config --global | alterar as configurações globais
git config --global help.autocorrect 1 | assume que o comando foi digitado corretamente
git archive [branch] --format=zip --output=master.zip | zipa o repositório 
git log --pretty=online [--graph] [--all] | deixando o log mais interessante
git log --author=['username'] | filtrando o log por autor
git shortlog -sn | visualizar a quantidade de commits por autor
git reflog | recuperar coisas. Salva vidas!! 

# Links úteis (github)
* https://help.github.com/articles/closing-issues-using-keywords
* https://github.com/devspace/awesome-github-templates
