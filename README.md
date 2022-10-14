1. **git init**
   \*(é utilizado para criar e iniciar um projeto git);

1- `git init` (é utilizado para criar e iniciar um projeto git);
2- `git add` landingpage.html (adiciona um ponto na história do projeto);

- `ou git add .` (adiciona todos);
  3- `git commit -m` "added landing page" (Grava o ponto na história do projeto, leva a alteração até o repositório);
  4- `git status` (lista o status de todos os arquivos no git);
  5- `git show` (mostra o historico do último arquivo atualizado, ou seja o último ponto na historia);
  :wq sai do git show (comando do vim);
  6- `git branch` [nome=feature/carrinho-de-compras] (cria uma nova versão);
  7- `git checkout` [nome da branch;
  8- `git merge` une as branch´s;
  9- `git branch -D feature/cart `// (Após a união das branch´s - merge, pode ser excluida);
  10-`git remote add origin` git@github.com:pslcorrea/aula-git-mikbrito.git;
  11- `git remote -v` (lista os meus repositorios remotos);
  12- `git push -u origin master`;
  13- `ls -al ~/.ssh` (lista as chaves ssh)
  14- `git config credential.helper store` (não precisa inserir credencial quando fizer um push);
