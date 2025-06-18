# Criando Repositórios, Branches e Pull Requests - Prática 1

## Objetivos da Aula:
1. Criar um repositório local e adiciona-lo ao nosso GitHub remoto;
2. Clonar um repositório remoto para o nosso computador local;
3. Fazer alterações >> Adicionar | Commitar | Enviar arquivos;
4. Criar uma nova Branch;
5. Realizar um Pull Request e Merge;
6. Criar nosso primeiro Fork.

## Ações no GitBash

Configuração rápida — se você já fez esse tipo de coisa antes

ou 

https://github.com/francildoalves/meu-repositorio-teste.git

Comece criando um novo arquivo ou enviando um arquivo existente. Recomendamos que cada repositório inclua um README, uma LICENÇA e um .gitignore.

…ou crie um novo repositório na linha de comando
```
echo "# meu-repositorio-teste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/francildoalves/meu-repositorio-teste.git
git push -u origin main''
```
…or push an existing repository from the command line
```
git remote add origin https://github.com/francildoalves/meu-repositorio-teste.git
git branch -M main
git push -u origin main
```
