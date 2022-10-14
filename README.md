# Comandos e comentários

1. **git init**: _(é utilizado para criar e iniciar um projeto git)_;
2. **git add**: _landingpage.html (adiciona um ponto na história do projeto)_;

- **git add .** : _(adiciona todos os arquivos)_

3. **git commit -m "comentário"**: _(Grava o ponto na história do projeto, leva a alteração até o repositório)_;

- **git commit -am [comentário]** _(adiciona e faz o commit)_;

4. **git status**: _(lista o status de todos os arquivos no git)_;
5. **git show**: _(mostra o historico do último arquivo atualizado, ou seja o último ponto na historia)_;

- _:wq sai do git show (comando do vim)_;

6. **git branch**: _[nome=feature/carrinho-de-compras] (cria uma nova versão)_;
7. **git checkout**: _[nome da branch]_;
8. **git merge**: _une as branch´s_;
9. **git branch -D feature/cart**: _(Após a união das branch´s - merge, pode ser excluida)_;

- **git checkout -b [nome da branch]** _(comando abreviado)_;

10. **git remote add origin**: _git@github.com:pslcorrea/aula-git-mikbrito.git\_;
11. **git remote -v**: _(lista os meus repositorios remotos)_;
12. **git push -u origin master**: _(Somente na primeira vez)_;

- **git push**: _(nas proximas, envia alterações locais para o repositório remoto)_;

13. **ls -al ~/.ssh**: _(lista as chaves ssh)_;
14. **git config credential.helper store**: _(não precisa inserir credencial quando fizer um push)_;

- **git clone**: _[link do projeto] (copia o projeto para nossa máquina)_;

* **git pull**: _(puxa o projeto da nuvem)_;

* **git checkout [id da linha do tempo] -- [nome do arquivo]**
  // Voltar um arquivo para um determinado momento
