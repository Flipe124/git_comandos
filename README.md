# GIT COMANDOS    
<img width= "300px" src="https://cdn.pixabay.com/photo/2014/07/15/23/36/github-394322_960_720.png">


# ![alt](https://img.shields.io/badge/-Configura%C3%A7%C3%A3o-blueviolet?style=for-the-badge)

+ Para identificar quem fez os commits
    ```
    git config --global user.name NOME
   ```
   ```
    git config --global user.email EMAIL@gmail.com
   ```


<br><br>

# ![alt](https://img.shields.io/badge/-Reposit%C3%B3rio-blueviolet?style=for-the-badge)

+ Iniciar o repositório Git (1)
    ```
     git init 
+ Adidionar repositório remoto (2)
    ```
    git remote add origin  https://github.com/USUARIO/REPOSITORIO.git

+ Verificar o repositório
    ```
    git remote -v
+ Remover o repositório   
    ```
    git remote remove origin
+ Alterar o repositório
    ```
    git remote set-url origin 'NOVA URL'
    ```
+ Clonar repositório
    ```
    git clone https://github.com/USUÁRIO/REPOSITÓRIO
    ```    

<br><br>

# ![alt](https://img.shields.io/badge/-Commit-blueviolet?style=for-the-badge)

+ Prepara o arquivo para ser commitado (1)
    ```
     git add .
+ Commita as modificações que estão estágiadas (2)
    ```
    git commit -m"MENSAGEM"
+ Sobe para o repositório remoto(Git) (3)
    ```
    git push origin master
 + Visualizar histórico de commits
    ```
    git log
+ Salvar commit em modo "oculto"
    ```
    git stash
    ```
    ```
    git stash push -m MEU-NOVO-STASH   
    ``` 
+ Listar stashes
    ```
    git stash list
+ Recuperar modificações do stach
    ```   
    git stash apply
+ Recuperar stash específico
    ```
    git stash apply stash@{NÚMERO-DA-STACHE} 
+ Remover stache
    ```
    git stash drop stash@{NÚMERO-DA- STACHE}       

<br><br>

# ![alt](https://img.shields.io/badge/-Branch-blueviolet?style=for-the-badge)

+ Lista todas as branches
    ````
    git branch
+ Alterar a branch atual
    ````
    git checkout MINHA-BRANCH
+ Renomear branch
    ```
    git branch -m NOVO-NOME-DA-BRANCH
+ Exibir branches mais legíveis
    ```
   - git log --all --decorate --oneline --graph
   ```
    - ("A DOG")  
+ Puxa os commits do repositório remoto
    ```
    git pull origin SUA-BRANCH
    ```    

+ Remove o que foi commitado no repositório remoto
    ```
    git push origin SUA-BRANCH --force
    ```    



