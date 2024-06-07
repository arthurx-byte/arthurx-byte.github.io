# 1- Comando para criar um repositorio git
git init

# 2- Adicionei um repositorio online do github
git remote add origin <nome do repositorio de origem ex: https://github.com/arthurx-byte/jogo-mario-html5-js-css.git>

# 3- Criar um branch(ramificassão do código)
git branch -M main

# 4- Adicionar somente um arquivo especifico
git add <nome do arquivo.ex>

# 5- Configurar github na maquina local
git config --global user.email "arthurdefigueiredodaconceiao@gmail.com"
git config --global user.name "Arthur Figueiredo"

# 6- Adicionar todo seus arquirvos para envio ao github
git add .

# 7- Definir o que vai ser enviado ao repositorio github
git commit -M "<comentario do código>"

# 8- Envia seu codigo para o repositorio github online
git push -u origin <nome da sua branch