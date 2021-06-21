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

# ver as mudancas do ultimo commit
git diff

# ver apenas os nomes de arquivos que foram modificados
git diff --name-only

# commitando o arquivo add e com msg de commit
git commit -am "message"

# remover do staged
git reset HEAD <arquivo>

# tirar todas as mudancas de um arquivos (modified)
git checkout <arquivo>

# git reset --soft
# Mata o commit mas Arquivo fica em staged
git reset --soft <hash_id>

# git reset --mixed
# Mata o commit mas Arquivo fica em modified
git reset --mixed <hash_id>

# git reset --hard
# Mata o tudo, commit, modificacao, etc, altera o historico do log de commit
git reset --hard <hash_id>

# criando uma cchave ssh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

# vinculando repositorio remoto ao diretorio git
git remote add origin https://github.com/vitoreticode/git-course.git

# verificar repositorios remotos
git remote

# mais informacoes dos repositorios remotos
git remote -v

# levando o commit para o repositorio remoto
# git push -u <remoto> <branch>
git push -u origin master
