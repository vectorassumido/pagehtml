# Página HTML
## Introdução ao Git
### Comandos básicos

#### Iniciar um repositório
````
git init
````

#### Clonar um repositório
````
git clone <url_do_repositorio>
````

#### Comando Git Fetch - Baixa o conteúdo do repositório remoto
````
git fetch
````

#### Buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local
#### Git pull = git fecth + git merge
````
git pull
````

#### Criar e fazer o checkout para uma nova branch
````
git chekout -b <nome da branch>
````

#### Adiciona todas as alterações na branch atual
````
git add .
````

#### Faz commit das alterações com uma mensagem
````
git commit -m "Msg"
````

#### Faz o chekout para uma branch
````
git checkout <nome da branch>

````



#### Unifica as alterações feitas
````
git merge <nome da branch com alterações realizadas>
````

#### Manda as alterações para o repositório remoto
````
git push
````


#### Enviar branch para o repositório remoto <origin>
````
git push origin <nome_da_branch>
````

#### Exibir histórico
````
git log
````

#### Exibir os repositórios remotos
````
git remote

git remote -v
````


