1- O comando git init é utilizado para criar e iniciar um projeto git
2- git add landingpage.html (adiciona um ponto na história do projeto)
3- git commit -m "added landing page" (Grava o ponto na história do projeto, leva a alteração até o repositório)
4- git status (lista o status de todos os arquivos no git)
5- git show (mostra o historico do último arquivo atualizado, ou seja o último ponto na historia)
:wq sai do git show (comando do vim)
6- git branch [nome=feature/carrinho-de-compras] (cria uma nova versão)
7- `git checkout` [nome da branch
8- `git merge` une as branch´s
9- `git branch -D feature/cart `// (Após a união das branch´s - merge, pode ser excluida)
10- `git remote -v` (lista os meus repositorios remotos)
11- `git push -u origin master`

Lista de comandos:
git config
git status
git diff
git add
git commit
git log
git pull
git push
git push -u origin

git init
git add .
git commit -m "Deem uma mensagem de commit clara"
git branch -M main
git remote add origin git@github.com:username/new_repo
git push -u origin main

git init
git branch <nome_branch>
git branch --all
git branch -d <nome_branch> - deleta branch local
git checkout -t origin/<nome_branch> - checkout par ao branch remoto
git checkout
git commit -am -> Utilizado para adicionar modificações em arquivos já existentes e dar commit
git merge

git config credential.helper store
git remote add origin git@github.com:username/new_repo
git push -u origin master

git stash - pega as modificações e "guarda"
git stach apply - pega as modificações "guardadas" e aplica
