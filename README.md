# Git & GitHub - Repositório de Estudos

Este repositório foi criado com o objetivo de praticar e aprimorar os conhecimentos em Git e GitHub. Aqui, realizarei experimentos com commits, branches, merges, pull requests e outras funcionalidades da plataforma.

**Objetivos:**

- Aprender os conceitos básicos e avançados do Git

- Praticar comandos essenciais do Git

- Entender o fluxo de trabalho com GitHub

- Testar diferentes cenários de versionamento e colaboração

# Comandos Importantes

**Alguns dos comandos do Git que serão utilizados e estudados:**

### Configuração inicial
git config --global user.name "Seu Nome"

git config --global user.email "seuemail@example.com"


### Inicializar um repositório
git init


### Clonar um repositório
git clone 'URL-do-repositorio'


### Adicionar arquivos
git add 'arquivo'

git add . (para add todos os arquivos)


### Criar um commit
git commit -m "Mensagem do commit"


### Verificar o status do repositório
git status


### Ver o histórico de commits
git log


### Ver versões de commits
git reflog


### Visualizar branchs
git branch


### Criar e alternar entre branches
git branch 'nome-da-branch'

git checkout 'nome-da-branch'


###permite mudar e criar uma nova branch com base em outra
git checkout -b "nome da branch de origem" "nome da nova branch"  


### Mesclar branches
git merge 'nome-da-branch'


### Enviar alterações para o GitHub
git push origin 'nome-da-branch


### Baixar alterações do repositório remoto
git pull origin 'nome-da-branch'


### fazer não subir arquivos indesejados
touch .gitignore
(adicionar o nome do arquivo a .gitignore)
git add .gitignore
