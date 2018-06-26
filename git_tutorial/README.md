# Comandos básicos do git
referência: https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf

## Criando repositórios

$ git clone [url]
    ex: git clone https://github.com/nightteatime/studygroup.git
$ git status


## Realizando mudanças

$ git status
    lista todas os arquivos novos ou modificados a serem comitted
$ git diff
    Mostra todas as diferenças não staged
$ git add [file]

$ git commit -m "[descriptive message]"

## Mudanças em grupos

$ git branch 
    Lista todos os branches no repositório atual
$ git branch [name-branch]
    Cria um novo branch 
$ git checkout [branch-name]
    Muda para o branch especificado
$ git merge [branch]
    Combina o branch especificado no branch atual (selecionado)
$ git branch -d [branch-name]    
   Deleta o branch especificado
   

