ink caderno google: 
https://docs.google.com/document/d/1DM4BZaxHqcmds2fj_spGfzonPYvh4n0u0WOZbN6Hn9Y/edit?usp=sharing

Linux
Aulas Terminal
https://www.cursoemvideo.com/curso/linux/aulas/comandos-do-terminal-do-linux/
Praticando superpoderes de CLI

Crie um novo diret?rio no seu diret?rio home com o nome "test". 
Navegue at? o diret?rio "test". 
Crie um novo arquivo chamado "test.txt". Dica: use o comando touch.
Abra o arquivo rec?m-criado no VSCode, fa?a algumas altera??es, salve o arquivo e feche-o. 
Navegue de volta para fora do diret?rio "test". 
Delete o diret?rio "test".



Gloss?rio de comandos
sudo
O que ??: Significa "Super User DO". Usado para executar comandos com permiss?es de administrador (root).
mkdir
O que ??: Significa "make directory"
cd
O que ??: Significa "change directory" 
rm
O que ??: Significa "remove" (remover). Usado para excluir arquivos ou diret?rios.
Para excluir um diret?rio e seu conte?do, use a op??o -r (recursivo). EX:
rm -r diret?rio
touch
O que ??: Usado para criar arquivos vazios ou atualizar a data de modifica??o de arquivos existentes.
ls
O que ??: Significa "list". Usado para listar arquivos e pastas no diret?rio atual.
pwd
O que ??: Significa "print working directory". Mostra o caminho completo do diret?rio em que voc? est?.
clear
O que ??: Usado para limpar a tela do terminal.
man
O que ??: Usado para acessar o manual de qualquer comando.




Git

Cheatsheet

Commands related to a remote repository:
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push ou git push origin main (Ambos servem pro mesmo objetivo nesse contexto)
Commands related to the workflow:
git add .
git commit -m "message? -> A mensagem que voc? escreve no comando git commit -m "mensagem" deve descrever o que foi alterado, adicionado ou corrigido desde o ?ltimo snapshot. Essa descri??o ajuda voc? e outras pessoas a entenderem as mudan?as feitas no c?digo ao longo do tempo."
Commands related to checking status or log history
git status
git log

-> The basic Git syntax is program | action | destination. For example:

git add . is read as git | add | ., where the period represents everything in the current directory;
git commit -m "message" is read as git | commit -m | "message" (After typing your commit message, save it Ctrl + S ); and
git status is read as git | status | (no destination).







*preciso entender melhor essa parte de git/github pelo terminal. Sei fazer pelo GitHub Desktop por?m.




HTML
Estrutura Geral
<!DOCTYPE html>: Declara??o que informa ao navegador o tipo de documento HTML.
<html>: Elemento raiz de um documento HTML.
lang: Define o idioma da p?gina.
<head>: Cont?m informa??es meta e links externos.
<meta>: Define metadados da p?gina.
charset="UTF-8": Define o conjunto de caracteres como UTF-8.
<title>: Define o t?tulo exibido na aba do navegador.
<body>: Cont?m o conte?do vis?vel da p?gina.
Links
<a>: Define um link.
href: Especifica o destino do link.
Links absolutos: Incluem esquema e dom?nio (ex.: https://site.com/pagina).
Links relativos: Referem-se a arquivos locais do mesmo site (ex.: ./pasta/arquivo.html).
./: Diret?rio atual.
../: Diret?rio pai (sobe um n?vel).

Atributos Adicionais em Links
target: Define como o link ser? aberto.
_blank: Abre o link em uma nova aba.
_self: Abre o link na mesma aba (comportamento padr?o).
rel: Define a rela??o entre a p?gina atual e o link.
noopener: Melhora a seguran?a ao evitar que a nova aba tenha acesso ? p?gina de origem.
noreferrer: Evita que informa??es de refer?ncia (como URL da p?gina atual) sejam enviadas ao site de destino.
nofollow: Indica aos motores de busca para n?o seguirem o link, ?til para links patrocinados.


Exemplo de boas pr?ticas ao usar target=?_blank?: 
<a href="https://example.com" target="_blank" rel="noopener noreferrer">Clique aqui</a>


Imagens
<img>: Insere imagens.
src: Caminho da imagem (absoluto ou relativo).
alt: Texto alternativo para acessibilidade (obrigat?rio).
width e height: Especificam largura e altura da imagem (opcional, mas recomendado).
Void element: N?o possui tag de fechamento.
Boas Pr?ticas
Use alt em todas as imagens para descrever o conte?do e garantir suporte para leitores de tela e falhas no carregamento.
Use links relativos para arquivos internos, e inclua ./ no in?cio de links relativos para evitar problemas.

GitHub
Aulas GitHub (via app)
https://www.cursoemvideo.com/curso/curso-de-git-e-github/aulas/aulas-de-git-e-github

Commits

Uma boa mensagem de commit explicar? o motivo por tr?s das suas altera??es, ou seja, ela descreve qual problema suas altera??es resolvem e como elas resolvem isso.

Commits eficazes consistem de duas partes separadas: um assunto e um corpo:
Assunto
Um resumo breve da altera??o que voc? fez no projeto.

?Esta ? a altera??o que fiz na base de c?digo.?

Corpo
Descreva o problema que seu commit resolve e como resolve.


Agora que aprendemos o segredo para criar uma boa mensagem de commit, vamos tentar corrigir a mensagem de commit de antes:

Exemplo de bom commit:
Assunto:
Adicionei link e texto alternativo faltantes no logo da empresa.
Corpo:
Leitores de tela n?o ler?o as imagens para usu?rios com defici?ncia sem essas informa??es.

E lembre-se: o GitHub tem um limite de 72 caracteres, por isso recomendamos manter o assunto dos seus commits dentro dessa quantidade.

Quando fazer um commit
? onde voc? salvaria o jogo pra n?o dar ruim caso o personagem morra kkkkk
Ou seja, fa?a commits sempre que houver mudan?as significativas no c?digo, como corrigir um erro ou fazer uma funcionalidade funcionar corretamente. Isso cria um hist?rico do seu progresso e permite voltar a vers?es anteriores, caso algo quebre mais tarde.

Dica extra:
O "Conventional commits" ? um exemplo de site com templates de commits que voc? pode conhecer e utilizar: https://www.conventionalcommits.org/en/v1.0.0/











