# NOTAS-ESTUDO
Notas de estudo do téc SENAC 2026

markdown

## Configurar Git
Abra o CMD

Para utilizar o git na minha maquina  eu preciso configurar determinador comandos sendo eles:
```bash
git -- version
```
```bash
git config --global user.name "Seu nome"
git config --global user.email  "seuemail@gmail.com"
```
## Como configurar  Github SSH
Verificar se existe a chave SSH
```bash
ls -al ~/.ssh
```
=======
Para utilizar o git na minha maquina  eu preciso configurar determinado comandos sendo eles:
>>>>>>> 0c21bb5bc582754c7a9ff33c9cc83e247aab90e9

```bash
ssh-key -t ed25519 -C "your_email@example.com"
```

```bash
eval "$(ssh-agent -s)"
```

```bash
ssh-add ~/.ssh/id_ed25519
```

```bash
clip<~/.ssh/id_ed25519.pub>
```


## SSH - Como configurar a maquina parb

## Como criar um repositório

# Revisão
 
## Conteúdo da avaliação
 
Git hub
 
 ### 1 passo
 
```
Primeiro abra o seu git hub no navegador

Depois clica no foto de perfil

Criar um repositório

Nome do repositório (Exemplo de batata ) sem caractere especial

Descrição ( aquilo que vai ter no repositório ) ( ex : aula para avaliação )

Depois marque o redame e sempre em public.
 ```
### 2 passo  ( Clonar  )
 
```
Vai no repositório que tu criou e vai no code e copia o código

Depois vai no git bash 
 
Vai colocar esse comado :
 
$ cd documents/
 
$git clone , botão direito e cola
 
Depois o nome do repositório , enter
 
Vai aparecer o ( main ) , depois
 
Code .( código )
 
Pronto abriu o teu vs code
 ```
### 3 passo ( criar pastas ) 
 ```
Vai ter a pasta readme.md
 
Clica no vazio e cria um
 
Clica com o botão direito new file , ( index.html )

Depois vai no espaço vazio , botão direito new folder ( script )

Em cima do folder ( script ) clica em new file e cria ( nome da avaliação.js )
 ```
### 4 passo ( configurando o index.html )
 ```
Vai no index.html
 
Digita lá ( Ctrl 1 = ! )
 
La em cima em ( lang ) vai estar em ( en ) = english

Muda para “ pt-br”
 
Depois disso vai em baixo do    ( <body> )

Em baixo do body digita script
 
 PRESTA ATENÇÃO !!!!!

Vai estar assim <script>

Você vai fazer isso aqui = <script src

Depois disso você vai escrever esse comando ( src="./scripts/avaliacao.js" )

E vai selecionar script>/avaliação
 
Depois disso você vai fazer o botão
 
Escreve “button” vai aparecer <button></button>

Dentro dessa merda aqui ( > )
 
Dentro dessa merda ali você vai escrever(  ID=”exercicio1” )

Depois da control V nesse código que você fez !!
 
<button id="exercicio1" >exercicio 1</button>
<button id="exercicio2" >exercicio 2</button>
<button id="exercicio3" >exercicio 3</button>
 
Só muda depois os número né
 ```
### 5 passo  ( dentro da pasta da avaliação )
 ```
function exemplo1( ) {
alert("funcionou aqui ")
}
 
Primeira coisa que você vai fazer é essa função
 
Depois disso vai por esse código aqui
 
const buttonexemplo1 = document.getElementById("exercicio1")

buttonexemplo1.addEventListener('click', () => { exemplo1() })// nome da função 
 ```

