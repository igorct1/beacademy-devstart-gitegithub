
# Be Academy - DevStart - Git e Github

Lista de comandos úteis para auxiliar no versionamento de projetos


![Logo](https://media-exp1.licdn.com/dms/image/C4D12AQGXkZf6DJB9kA/article-cover_image-shrink_600_2000/0/1625492357429?e=1653523200&v=beta&t=XtfpluRy4o2KLM8c8iUIG-vnpddAQ-zmU-uDjTfpBXQ)

## Antes de começar um novo projeto, é legal configurar nome e email, pois são eles que aparecem em todos os commits feitos.
## Funcionalidades

`git config --global user.name "seuNome"` (configurar nome)

`git config --global user.email "seuemail@aqui.com"` (configurar email)

`git init` (iniciando projeto no rep local)

`git status` (monitorar arquivos, tudo que esta sendo criado ou modificado)

`git add <file>` (empacotar arquivos para ser commitado, pode ser utilizado `add .` para adicionar todos)

`git commit -m "mensagem"` (armazena o conteudo em um novo commit)

`git log` (lista todos os commits feitos, incluindo quem o fez)

`git branch` (lista todos a branchs e mostra qual você está)

`git branch nome_da_branch` (cria uma nova branch)

`git checkout nome_da_branch` (trocar de branch)

`git checkout -b nome_da_branch` (criar nova branch e acessa-la)

`git branch -d nome_da_branch` (remover branch)

`git merge nome_da_branch` (faz o merge de branchs, você precisa estar na branch que vai receber a branch secundaria)

`git clone URL` (clonar repositório remoto para rep local)

`git push` (envia para o rep remoto)

`git stash` (salvar modificações sem commitar, por exemplo, você precisa mudar de branch mas não quer commitar uma parte incompleta, então você utiliza o git stash para salvar essas modificações sem commitar)

`git stash list` (lista todas as stashs)

`git stash pop` (restaurar alterações salvas)

`git stash pop stash@{1}` (stash especifico)

`git revert id_commit` (reverte um commit)

`git revert --abort` (reverte a reversão de um commit)

`git rm` (remove arquivos do projeto)
## Autores
- Aluno [@igorct1](https://www.github.com/igorct1)
- Professor [@lnmont](https://www.github.com/lnmont)
- Professor [@rejota23](https://www.github.com/rejota23)

