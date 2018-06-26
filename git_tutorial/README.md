# Comandos básicos do git
referência: https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf <br>

## Criando repositórios

$ git clone [url] <br>
    ex: git clone https://github.com/nightteatime/studygroup.git <br>
$ git status <br>


## Realizando mudanças

$ git status <br>
    lista todas os arquivos novos ou modificados a serem comitted <br>
$ git diff <br>
    Mostra todas as diferenças não staged <br>
$ git add [file] <br>

$ git commit -m "[descriptive message]" <br>

## Mudanças em grupos

$ git branch  <br>
    Lista todos os branches no repositório atual <br>
$ git branch [name-branch] <br>
    Cria um novo branch  <br>
$ git checkout [branch-name] <br>
    Muda para o branch especificado <br>
$ git merge [branch] <br>
    Combina o branch especificado no branch atual (selecionado) <br>
$ git branch -d [branch-name] <br>
   Deleta o branch especificado  <br>
   

