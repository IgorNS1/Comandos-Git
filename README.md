# Sequência de Pasos Git

## Primeira Criação

* Paso 1: Criar repositório no Github
* Paso 2: Inicializar repositório local (no arquivo) - `git init`
* Paso 3: Enviar arquivo para área stage - `git add <arquivo> / git add .`
* Paso 4: Dar commit no repositório - `git commit -m "<comentário>"`
* Paso 5: Alterar nome da branch - `git branch -M "main"`
* Paso 6: Vincular repositório local com repositório Github - `git remote add origin <url repositório Github>`
* Paso 7: Enviar para o repositório Github - `git push -u origin main`

## Adição e/ou Altereção de Arquivo:

* Paso 1: Enviar alterações para área stage - `git add <arquivo> / git add .`
* Paso 2: Dar commit no repositório - `git commit -m "<comentário>"`
* Paso 3 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Paso 4: Enviar para o repositório Github - `git push origin main`

## Branch e Merge

### Branch

* Paso 1: Adicionar e mover para a nova branch - `git checkout -b "<nome>"`
* Paso 2: Enviar alterações para área stage - `git add <arquivo> / git add .`
* Paso 3: Dar commit no repositório - `git commit -m "<comentário>"`
* Paso 4 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Paso 5: Enviar para o repositório Github - `git push origin <nova branch>`

### Merge

* Paso 1: Voltar para branch principal(default) - `git checkout main`
* Paso 2: Mesclar as branchs - `git merge <nome branch>`
* Paso 3 (Se tiver outros usários mexendo no código): Puxar alterações feitas por outros usuários - `git pull`
* Paso 4: Enviar para o repositório Github - `git push origin main`