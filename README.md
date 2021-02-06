# Anotacoes curso GIT-GITHUB :computer_mouse:

Comandos 

#### GIT Init

- Inicia uma área de GIT na pasta atual
  - Sintaxe:  **git init**

#### GIT ADD

- Coloca o arquivo local no GIT
  - Sintaxe: **git add <arquivo> ou git add ***

#### GIT STATUS

<<<<<<< HEAD
<<<<<<< HEAD

- Mostra o status do GIT

  - Sintaxe: **git status**

  

#### GIT COMMIT

- Comita as informacoes no GIT
  - Sintaxe: **gi commit -m "Descritivo"**

#### GIT PUSH

- Empurra os arquivos para o GITHUB
  - Sintaxe: **git push origin master** //  **git push -u master** //  **git push -f master**



#### GIT CONFIG

- Seta as configuracoes da conta GIT
  - Sintaxe:  **git config --list** -> Mostra o profile da conta
    - 		**git config --global --unset user.email** -> Remove o email do usuario
    - 		**git config user.email "aaaa@aaaa"** -> Seta o email do usario

#### GIT REMOTE

**Adicionar no git a conta GITHUB**

- git remote add origin https://github.com/cursosivanpetrucci/cursogit-github.git



# Quando houver conflito

hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.



Usar o **git pull origin master**