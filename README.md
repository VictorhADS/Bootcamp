# Acesse a pasta do seu projeto (altere conforme necessário)
cd /caminho/para/sua/pasta-do-projeto

# Inicia o repositório Git local
git init

# Adiciona todos os arquivos para o controle de versão
git add .

# Cria o commit inicial
git commit -m "Commit inicial do projeto"

# Adiciona o repositório remoto (substitua com sua URL real do GitHub)
git remote add origin https://github.com/victorads/README.md.git

# Define a branch principal como 'main'
git branch -M main

# Envia o código para o GitHub
git push -u origin main
