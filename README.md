# Sequência de Passos Git

## Primeira Criação

* Passo 1: Criar repositório no Github
* Passo 2: Inicializar repositório local (no arquivo) - `git init`
* Passo 3: Enviar arquivo para área stage - `git add <arquivo> / git add .`
* Passo 4: Dar commit no repositório - `git commit -m "<comentário>"`
* Passo 5: Alterar nome da branch - `git branch -M "main"`
* Passo 6: Vincular repositório local com repositório Github - `git remote add origin <url repositório Github>`
* Passo 7: Enviar para o repositório Github - `git push -u origin main`

## Adição e/ou Altereção de Arquivo:

* Passo 1: Enviar alterações para área stage - `git add <arquivo> / git add .`
* Passo 2: Dar commit no repositório - `git commit -m "<comentário>"`
* Passo 3 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Passo 4: Enviar para o repositório Github - `git push origin main`

## Branch e Merge

### Branch

* Passo 1: Adicionar e mover para a nova branch - `git checkout -b "<nome>"`
* Passo 2: Enviar alterações para área stage - `git add <arquivo> / git add .`
* Passo 3: Dar commit no repositório - `git commit -m "<comentário>"`
* Passo 4 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Passo 5: Enviar para o repositório Github - `git push origin <nova branch>`

### Merge

* Passo 1: Voltar para branch principal(default) - `git checkout main`
* Passo 2: Mesclar as branchs - `git merge <nome branch>`
* Passo 3 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Passo 4: Enviar para o repositório Github - `git push origin main`