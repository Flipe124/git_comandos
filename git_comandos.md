# GIT COMANDOS    

====================================================

# Para identificar quem fez os commits
    git config --global user.name NICK
    git config --global user.email EMAIL@gmail.com

====================================================

# Iniciar o repositório Git
    git init 
# Adidionar repositório remoto
    git remote add origin https://github.com/USUARIO/REPOSITORIO.git

====================================================

# Verificar o repositório
    git remote -v
# Remover o repositório   
    git remote remove origin
# Alterar o repositório
    git remote set-url origin 'NOVA URL'

====================================================    

# Comandos básicos para git

==================================================== 

# Prepara o arquivo para ser commitado
    git add .
# Commita as modificações que estão estágiadas
    git commit -m"MENSAGEM"
# Sobe para o repositório remoto(Git)
    git push origin master

====================================================  
