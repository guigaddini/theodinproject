Link caderno google: 

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

























