# Curso Digital: Git

## Introdução
- Registro de mudanças em arquivos, que possibilita recuperar ou
- acesso a versões anteriores.
- Desenvolvimneto de código em colaboração com outros integrantes.

## 1 - O que é git?
- Snapshots do estado do projeto
- Registro de mudanças em arquivos, que possibilita recuperar ou
- acesso a versões anteriores.
- Desenvolvimneto de código em colaboração com outros integrantes.

```
 git cmd
 git desktop
 git vscode

```
## 2 - Instalação

https://git-scm.com/


## 3 - Repositório Git

Criando repositório remoto no github

https://github.com/

```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/silveiratcl/letscode-br_git_e_versionamento.git
git push -u origin main

```

ou enviando um repositório local

```
git remote add origin https://github.com/silveiratcl/letscode-br_git_e_versionamento.git
git branch -M main
git push -u origin main

```

## 4 - Gravando mundamças no repositório

Staged - preparando para commit, modificações

Caso “staged” vão ser inseridas no próximo commit


```
$ git add .
$ git commit -m "first commit"
$ git push origin

# git status branch and status
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
 .
```

# 5 - Git diff, commit e rm

Diff -  revela as diferenças nos dois arquivos

```
$ git diff --staged
# list the staged changes

```

## 6 - Git log e restore

```
$ git log
Author: Thiago Silveira <62719017+silveiratcl@users.noreply.github.com>
Date:   Thu Oct 19 08:57:43 2023 -0300

    edit publi
# histórico
# "q" exis from git log

```

```
$ git restore .\README.md
# restore para retornar para unmodified ou
# desiste de deixar na área de modificado

```

## 7 - Repositórios remotos

```
$ git add .
$ git commit -m "changes in README.me"
$ git push origin

```

```
$ git pull
# download all data from remote

```

```
$ git fetch
# download everything on remote without merging
$ git diff origin master
# show lines missing
"q" quit
$ git pull
# download and merge

```

## 8 - Git e github


## 9 - Git branch


