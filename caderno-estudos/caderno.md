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






rm -r diretorio

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


O seletor de tipo seleciona todos os elementos de um tipo especifico. Exemplo:html <div>Hello, World!</div>

<div>Again!</div>

<p>Hi...</p> div {

  color: white;

}

Nesse caso, todos os elementos <div> terao o texto branco, mas o <p> nao.





## Seletores de Classe


Seleciona todos os elementos com uma classe especifica. HTML: <div class="alert-text">Texto de alerta.</div>

? .alert-text {

  color: red;

}

A classe pode ser usada em varios elementos.



## Seletores de ID


Seleciona um elemento unico com um ID especifico. Exemplo:

html: <div id="title">Titulo da Pagina</div>



css:#title {

  background-color: red;

}

O ID e unico, ou seja, nao pode ser repetido em uma pagina.



## Seletores de Agrupamento


Agrupar seletores que compartilham declaracoes comuns reduz a repeticao. Exemplo:css .read, .unread {

  color: white;

  background-color: black;

}

## Seletores Encadeados


Permite combinar seletores de forma que um seletor tenha que atender a varias condicoes. Exemplo:css .subsection.header {

  color: red;

}

## Combinador Descendente


Seleciona um elemento se ele for descendente de outro. Exemplo:css .ancestor .child {

  /* regras */

}

Aqui, .child sera selecionado apenas se estiver dentro de .ancestor.





