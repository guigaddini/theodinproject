Link caderno google docs: 

https://docs.google.com/document/d/1DM4BZaxHqcmds2fj__spGfzonPYvh4n0u0WOZbN6Hn9Y/edit?usp=sharing



Linux

# Aulas Terminal


https://www.cursoemvideo.com/curso/linux/aulas/comandos-do-terminal-do-linux/

# Praticando superpoderes de CLI






















# Glossario de comandos


### sudo




### mkdir




### cd




### rm






EX: 				rm -r diretorio

### touch




### ls




### pwd




### clear




man









Git



# Cheatsheet




## Commands related to a remote repository:


git clone git@github.com:USER-NAME/REPOSITORY-NAME.git

git push ou git push origin main (Ambos servem pro mesmo objetivo nesse contexto)

## Commands related to the workflow:


git add .

git commit -m "message? -> A mensagem que voce escreve no comando git commit -m "mensagem" deve descrever o que foi alterado, adicionado ou corrigido desde o ultimo snapshot. Essa descricao ajuda voce e outras pessoas a entenderem as mudancas feitas no codigo ao longo do tempo."

## Commands related to checking status or log history


git status

git log



-> The basic Git syntax is program | action | destination. For example:



git add . is read as git | add | ., where the period represents everything in the current directory;

git commit -m "message" is read as git | commit -m | "message" (After typing your commit message, save it Ctrl + S ); and

git status is read as git | status | (no destination).















*preciso entender melhor essa parte de git/github pelo terminal. Sei fazer pelo GitHub Desktop porem.





HTML

# Estrutura Geral


















# Links
















## Atributos Adicionais em Links




















Exemplo de boas praticas ao usar target=?__blank?: 

<a href="https://example.com" target="__blank" rel="noopener noreferrer">Clique aqui</a>





# Imagens














## Boas Praticas






# Containers e Elementos de Texto










GitHub

# Aulas GitHub (via app)


https://www.cursoemvideo.com/curso/curso-de-git-e-github/aulas/aulas-de-git-e-github



# Commits




Uma boa mensagem de commit explicara o motivo por tras das suas alteracoes, ou seja, ela descreve qual problema suas alteracoes resolvem e como elas resolvem isso.



Commits eficazes consistem de duas partes separadas: um assunto e um corpo:

## Assunto


Um resumo breve da alteracao que voce fez no projeto.



?Esta e a alteracao que fiz na base de codigo.?



## Corpo


Descreva o problema que seu commit resolve e como resolve.





Agora que aprendemos o segredo para criar uma boa mensagem de commit, vamos tentar corrigir a mensagem de commit de antes:



## Exemplo de bom commit:


Assunto:

Adicionei link e texto alternativo faltantes no logo da empresa.

Corpo:

Leitores de tela nao lerao as imagens para usuarios com deficiencia sem essas informacoes.







# Quando fazer um commit


E onde voce salvaria o jogo pra nao dar ruim caso o personagem morra kkkkk

Ou seja, faca commits sempre que houver mudancas significativas no codigo, como corrigir um erro ou fazer uma funcionalidade funcionar corretamente. Isso cria um historico do seu progresso e permite voltar a versoes anteriores, caso algo quebre mais tarde.



# Dica extra:


O "Conventional commits" e um exemplo de site com templates de commits que voce pode conhecer e utilizar: https://www.conventionalcommits.org/en/v1.0.0/





CSS

Cascading Style Sheet

# Sintaxe basica do CSS




O CSS e composto por regras, cada uma com um seletor (indica qual elemento HTML sera estilizado) e uma lista de declaracoes separadas por ponto e virgula.





# Tipos de Seletores


## Seletor Universal


O seletor universal seleciona todos os elementos de uma pagina. Sua sintaxe e um asterisco *. Exemplo:css * {

  color: purple;

}



## Seletores de Tipo (ou Elemento)


O seletor de tipo seleciona todos os elementos de um tipo especifico. 

HTML: <div>Hello, World!</div>

<div>Again!</div>

<p>Hi...</p>

CSS:div {

  color: white;

}

Nesse caso, todos os elementos <div> terao o texto branco, mas o <p> nao.





## Seletores de Classe


Seleciona todos os elementos com uma classe especifica. HTML: <div class="alert-text">Texto de alerta.</div>CSS: .alert-text {

  color: red;

}

A classe pode ser usada em varios elementos.

## Seletores de ID


Seleciona um elemento unico com um ID especifico. Exemplo:

HTML: <div id="title">Titulo da Pagina</div>



css:#title {

  background-color: red;

}



O ID e unico, ou seja, nao pode ser repetido em uma pagina, por isso, nao costuma ser muito utilizado!



## Seletores de Agrupamento


Agrupar seletores que compartilham declaracoes comuns reduz a repeticao.

css: .read, .unread {

  color: white;

  background-color: black;

}

## Seletores Encadeados


Permite combinar seletores de forma que um seletor tenha que atender a varias condicoes. css: .subsection.header {

  color: red;

}

## Combinador Descendente


Seleciona um elemento se ele for descendente de outro. 

css: .ancestor .child {

  /* regras */

}

Aqui, .child sera selecionado apenas se estiver dentro de .ancestor.





## ATENCAO!


### Ordem de leitura do CSS




# Cheat sheet CSS


Baseado em: https://www.youtube.com/watch?v=l1mER1bV0N0

Descricao

CSS

Resultado

Basico





Seletor universal

*

Seleciona todos os elementos

Seletor de tipo

div

Seleciona elementos do tipo especificado (ex.: <div>)

Seletor de classe

.classe

Seleciona elementos com a classe especificada

Seletor de ID

#id

Seleciona elementos com o ID especificado

Combinacoes de seletores





Descendente

div a

Seleciona elementos <a> que sao descendentes de um <div>

Filho direto

div > a

Seleciona <a> que sao filhos diretos de <div>

Irmao geral

div ~ a

Seleciona elementos <a> que sao irmaos de <div> e aparecem depois

Irmao adjacente

div + a

Seleciona o primeiro elemento <a> que aparece imediatamente apos <div>

Combinacao OR

div, a

Seleciona todos os elementos <div> e <a>

Combinacao AND

div.classe

Seleciona elementos <div> que possuem a classe especificada

Atributos





Tem atributo

[atributo]

Seleciona elementos que possuem o atributo especificado

Valor exato

[atributo="valor"]

Seleciona elementos cujo atributo tenha o valor exato especificado

Comeca com

[atributo^="valor"]

Seleciona elementos cujo atributo comeca com o valor especificado

Termina com

[atributo$="valor"]

Seleciona elementos cujo atributo termina com o valor especificado

Contem

[atributo*="valor"]

Seleciona elementos cujo atributo contem o valor especificado em qualquer parte

Pseudo-elementos





Antes

div::before

Insere conteudo antes dos filhos do elemento selecionado

Depois

div::after

Insere conteudo depois dos filhos do elemento selecionado

Classes de estado (Pseudo-classes)





Hover

button:hover

Seleciona botoes quando o mouse passa por cima

Foco

button:focus

Seleciona botoes quando estao em foco (clicados ou tabulados)

Obrigatorio

input:required

Seleciona campos <input> obrigatorios

Marcado

input:checked

Seleciona checkboxes ou botoes de radio marcados

Desabilitado

input:disabled

Seleciona campos <input> desabilitados

Posicao e outros





Primeiro filho

a:first-child

Seleciona o primeiro filho dentro de um container

Ultimo filho

a:last-child

Seleciona o ultimo filho dentro de um container

Enesimo filho

a:nth-child(n)

Seleciona o enesimo filho dentro de um container (baseado em formula)

Enesimo filho a partir do final

a:nth-last-child(n)

Seleciona o enesimo filho contando a partir do final

Unico filho

a:only-child

Seleciona elementos que sao os unicos filhos de um container

Primeiro do tipo

a:first-of-type

Seleciona o primeiro elemento de um determinado tipo dentro de um container

Ultimo do tipo

a:last-of-type

Seleciona o ultimo elemento de um determinado tipo dentro de um container

Enesimo do tipo

a:nth-of-type(n)

Seleciona o enesimo elemento de um determinado tipo dentro de um container

Enesimo do tipo a partir do final

a:nth-last-of-type(n)

Seleciona o enesimo elemento de um tipo contando a partir do final

Unico do tipo

a:only-of-type

Seleciona elementos que sao os unicos de um determinado tipo dentro de um container

Nao

a:not(.classe)

Seleciona todos os elementos <a> que nao possuem a classe especificada





SASS

### Baseado no video: 




O Sass (Syntactically Awesome Stylesheets) e uma extensao do CSS que adiciona funcionalidades como variaveis, aninhamento, mixins, heranca e importacao de arquivos, tornando o codigo mais organizado, reutilizavel e facil de manter.

### Principais vantagens do Sass


? Facilita a organizacao do codigo CSS? Evita repeticao, reduzindo a quantidade de codigo? Permite variaveis, facilitando alteracoes globais? Suporta aninhamento, tornando o codigo mais intuitivo? Possui mixins e heranca, ajudando na reutilizacao de estilos

### Como funciona?






Exemplo de codigo Sass (.scss):$primary-color: blue;



body {

  background: $primary-color;

  nav {

    ul {

      list-style: none;

    }

  }

}



Apos a compilacao, vira CSS puro:body {

  background: blue;

}

body nav ul {

  list-style: none; 

}

### 1. Variaveis ($nome-da-variavel)




$primary-color: blue;

body {

  background: $primary-color;

}

###  2. Aninhamento (Nestings)




nav {

  ul {

   list-style: none;

    li {

      display: inline-block;

    }

  }

}

### 3. @import (Divisao de arquivos)




Exemplo:scssCopiarEditar@import "header";

@import "footer";



### 4. Mixins (@mixin e @include)




@mixin flex-center($direction) {

  display: flex;

  justify-content: center;

  align-items: center;

  flex-direction: $direction;

}



.container {

  @include flex-center(column);

}



### 5. @extend (Heranca de estilos)




.btn {

  padding: 10px;

  border-radius: 5px;

}



.btn-primary {

  @extend .btn;

  background-color: blue;

}

###  




