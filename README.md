# senai-versoes-colaboracoes
Atividade 1 da disciplina Versionamento.

//Configurando nome de usuário e e-mail: 

$ git config --global user.email "Cleber1108@hotmail.com"
$ git config --global user.name "Cleber Ernesto"

//Criei um repositório na pasta senai-versoes-colaboracoes 
$ git init -b "main" --initial-branch="main"

//Criei o arquivo versoes.txt e usei os comandos abaixo para adicioná-lo ao repositório local:
git remote add origin https://github.com/Cleber1108/senai-versoes-colaboracoes/
$ git add versoes.txt
$ git commit -m "..."

//Além da branch principal (Trunk, com o nome de main), criei duas branchs, com nome branch1 e branch2

$ git add .
$ git commit -m "subindo o readme na branch1"
$ git push origin branch1
