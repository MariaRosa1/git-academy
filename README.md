# git-academy

## git init
inicialização de um projeto

```
git init
```

## Configurações iniciais

```bash
git config --global user.name "username" 
git config --global user.email "user@email.com" 
```

### Controle de alterações 
Para visualizar as alterações feitas, vamos usar:

```
git status
```

## Criando commits
Primeiramente precisamos adicionar as mudanças e enfim "commitar":
> utilize o ponto para adicionar todas alterações do projeto.

```bash
git add .
git commit -m "descricao das alteracoes"
```

## Branches
Podemos ramificar o código usando branches para criar uma nova, executamos: 

```
git switch --create <nome-da-nova-branch>
> or
git checkout -b <nome-da-branch>
```
listando branches criadas:

```
git branch
```
Apagando branch:

```
git branch -D <nome-da-branch>
```

## GitHub
>Adicionando um remote origin:

```
git remote add origin link
ex: git remote add origin https://github.com/MariaRosa1/git-academy.git
```

>Subindo alterações:
 ```bash
git push origin <nome-da-branch>
# caso a branch nao exista no github use:
git push -u origin <nome-da-branch>
 ```

