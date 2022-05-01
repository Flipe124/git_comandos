# GIT COMANDOS    
====================================================
## Para identificar quem fez os commits
    git config --global user.name NICK
    git config --global user.email EMAIL@gmail.com
====================================================
# Repositório
## Iniciar o repositório Git
    git init 
## Adidionar repositório remoto
    git remote add origin https://github.com/USUARIO/REPOSITORIO.git
## Verificar o repositório
    git remote -v
## Remover o repositório   
    git remote remove origin
## Alterar o repositório
    git remote set-url origin 'NOVA URL'
====================================================    
# Commits
## Prepara o arquivo para ser commitado
    git add .
## Commita as modificações que estão estágiadas
    git commit -m"MENSAGEM"
## Sobe para o repositório remoto(Git)
    git push origin master
 ## Visualizar histórico de commits
    git log
## Salvar commit em modo "oculto"
    git stash
    git stash push -m MEU-NOVO-STASH    
## Listar stashes
    git stash list
## Recuperar modificações do stach
    git stash apply
#### Recuperar stash específico
    git stash apply stash@{NÚMERO-DA-STACHE} 
## Remover stache
    git stash drop stash@{NÚMERO-DA- STACHE}       
==================================================== 
# Branches
## Lista todas as branches
    git branch
## Alterar a branch atual
    git checkout MINHA-BRANCH
## Renomear branch
    git branch -m NOVO-NOME-DA-BRANCH
## Exibir branches mais legíveis
    git log --all --decorate --oneline --graph
#### ("A DOG")  



