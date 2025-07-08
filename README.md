# Git Comandos Essenciais

Este guia apresenta os comandos essenciais para realizar controle de versão.

## Configuração Inicial

```bash
# Configurar nome de usuário
git config --global user.name "Seu Nome"

# Configurar email
git config --global user.mail "seu@email.com"

# Verificar configurações
git config --list

```

## Comandos iniciais 
```bash
# Inicializa repositório
$ git init

# Clonar um repositório existente
$ git clone https://github.com/usuario/repositorio.git

# Adicionar arquivo ao repositório
$ git add README.md

# Push an existing repository from the command line
$ git remote add origin https://github.com/thobias0104/petro-workshop.git
$ git branch -M main
$ git push -u origin main
```

## Lista de comandos
```bash
$ git --help
These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects
```