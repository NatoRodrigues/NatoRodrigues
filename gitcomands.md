Inicializar um Repositório a Partir de uma Pasta Nova
Navegue até o diretório da pasta:

cd /caminho/para/sua/pasta


Inicialize o repositório Git:

git init

Adicionar um Projeto a um Repositório Remoto
Adicione o repositório remoto:

git remote add origin https://github.com/usuario/repositorio.git


Envie (push) o projeto para o repositório remoto:

git push -u origin main

Fazer o Merge
Combine as mudanças de diferentes branches:
Mude para a branch principal (por exemplo, main):

git checkout main

Faça o merge da branch desejada (por exemplo, feature-branch):

git merge feature-branch

Criar uma Branch
Crie e mude para uma nova branch:
git checkout -b nova-branch

Checar Mudanças do Repositório Local para o Remoto
Busque as alterações do repositório remoto:
git fetch origin

Fazer o Pull
Atualize sua branch local com as mudanças do repositório remoto:
git pull origin nome-da-branch


Envie (push) o projeto para o repositório remoto:

git push -u origin main



