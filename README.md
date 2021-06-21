# Github

# Lifecycle
Untracked ->"add the file"-> Unmodified ->"Edit the file"-> Modified ->"Stage the file"-> Staged ->"Commit"-> Unmodified

# Inicializar um diretorio do git
git init

# Verificar o status
git status

# Adicionar arquivo para ser trackeado
git add README.md

# criar um commit com msg
git commit -m "Add README.me"

# verificar o log do Git
git log --decorate

# filtrar o log pelo author
git log --author="John"

# mostrar log em orderm alfabetica
git shortlog

# quantidade de commits por author
git shortlog -sn

# mostrar o log de forma grafica
git log --graph

# identificar commit log pela hash
git show <hash_id>

# ver as mudancas entre commit
