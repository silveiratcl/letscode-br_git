# Curso Digital: Git
- Registro de mudanças em arquivos, que possibilita recuperar ou
- acesso a versões anteriores.
- Desenvolvimneto de código em colaboração com outros integrantes.

## O que é git?
Snapshots do estado do projeto
- git cmd
- git desktop
- git vscode

## Repositório Git

Criando repositório remoto no github

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

## Gravando mundamças no repositório

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

```

