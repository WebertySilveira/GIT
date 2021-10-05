# FLUXO DE TRABALHO NO GIT
![git](https://hermes.digitalinnovation.one/articles/cover/8de9986e-f7c0-447d-ba76-ff695b9db0b4.jpg)

---
### COMANDOS BÁSICOS

* > Clonar um repositório do github:

 ``` git clone``` 

* > Ver informações dos arquivos alterados:

 ``` git status``` 

* > Adicionar arquivos específicos:

``` git add 'file.py' ``` 

* > Adicionar todos os arquivos em 'staged':

``` git add .``` 

* > Ver commits realizados:

 ``` git log```

* > Realizar um commit de arquivos específicos:

``` git commit 'file.py'``` 

* > Realizar um commit com todos os arquivos:

``` git commit .``` 

* > Adicionar arquivos ao último commit realizado (HEAD):

``` git commit --amend --no-edit``` 

* > Subir alterações para o repositório do git

``` git push```

---

### TRABALHANDO COM BRANCHS

* > Criando um Branch

``` git checkout -b branchName```

* > Deletando um Branch

``` git branch -D branchName```

* > Selecionar repositório remoto

``` git remote add remoteExample linkExample```

* > Listar repositório remoto

``` git remote -v```

* > Listar repositório remoto

``` git remote rm remoteExample```

* > Pegar todos os Branchs no repositório remoto

``` git fetch remoteExample```

* > Pegar todos os Branchs no repositório remoto

``` git rebase remoteExample/remoteBranch```

---

### UTILIZANDO TEMPLATE


1. >Criar e clonar novo repositório

``` git clone exampleLink```

2. >Selecionar link do template remoto

``` git remote add template templateLink```

3. >Pegar todas as informações do template

``` git fetch template```

4. >Gerar novo repositório com base no template

```git merge template/branch --allow-unrelated-histories --squash```

#### :warning: ATENÇÃO!!!
 Em caso de gerar conflitos, pode ser utilizado a própria ferramenta do [Visual Studio Code](https://code.visualstudio.com/download). Uma boa alternativa é o programa [Sublime Merge](https://www.sublimemerge.com/).

5. >Adicionar todos os arquivos desajados

```git add .```

6. >Adicionar alterações para o commit inicial

```git commit --amend --no-edit```

7. >Subir arquivos para o repositório desejado

```git push -f```

---
### CONTEÚDOS RECOMENDADOS

* [APRENDA GIT JOGANDO](https://learngitbranching.js.org/?locale=pt_BR) :joystick: