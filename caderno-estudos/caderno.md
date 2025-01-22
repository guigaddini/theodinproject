-> Link caderno google: 
https://docs.google.com/document/d/1DM4BZaxHqcmds2fj_spGfzonPYvh4n0u0WOZbN6Hn9Y/edit?usp=sharing

Linux
Aulas Terminal
https://www.cursoemvideo.com/curso/linux/aulas/comandos-do-terminal-do-linux/
Praticando superpoderes de CLI

Crie um novo diretorio no seu diretorio home com o nome "test". 
Navegue ate o diretorio "test". 
Crie um novo arquivo chamado "test.txt". Dica: use o comando touch.
Abra o arquivo recem-criado no VSCode, faca algumas alteracoes, salve o arquivo e feche-o. 
Navegue de volta para fora do diretorio "test". 
Delete o diretorio "test".



Glossario de comandos
sudo
O que e?: Significa "Super User DO". Usado para executar comandos com permissoes de administrador (root).
mkdir
O que e?: Significa "make directory"
cd
O que e?: Significa "change directory" 
rm
O que e?: Significa "remove" (remover). Usado para excluir arquivos ou diretorios.
Para excluir um diretorio e seu conteudo, use a opcao -r (recursivo). EX:
rm -r diretorio
touch
O que e?: Usado para criar arquivos vazios ou atualizar a data de modificacao de arquivos existentes.
ls
O que e?: Significa "list". Usado para listar arquivos e pastas no diretorio atual.
pwd
O que e?: Significa "print working directory". Mostra o caminho completo do diretorio em que voce esta.
clear
O que e?: Usado para limpar a tela do terminal.
man
O que e?: Usado para acessar o manual de qualquer comando.




Git

Cheatsheet

Commands related to a remote repository:
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push ou git push origin main (Ambos servem pro mesmo objetivo nesse contexto)
Commands related to the workflow:
git add .
git commit -m "message? -> A mensagem que voce escreve no comando git commit -m "mensagem" deve descrever o que foi alterado, adicionado ou corrigido desde o ultimo snapshot. Essa descricao ajuda voce e outras pessoas a entenderem as mudancas feitas no codigo ao longo do tempo."
Commands related to checking status or log history
git status
git log

-> The basic Git syntax is program | action | destination. For example:

git add . is read as git | add | ., where the period represents everything in the current directory;
git commit -m "message" is read as git | commit -m | "message" (After typing your commit message, save it Ctrl + S ); and
git status is read as git | status | (no destination).







*preciso entender melhor essa parte de git/github pelo terminal. Sei fazer pelo GitHub Desktop porem.




HTML
Estrutura Geral
<!DOCTYPE html>: Declaracao que informa ao navegador o tipo de documento HTML.
<html>: Elemento raiz de um documento HTML.
lang: Define o idioma da pagina.
<head>: Contem informacoes meta e links externos.
<meta>: Define metadados da pagina.
charset="UTF-8": Define o conjunto de caracteres como UTF-8.
<title>: Define o titulo exibido na aba do navegador.
<body>: Contem o conteudo visivel da pagina.
Links
<a>: Define um link.
href: Especifica o destino do link.
Links absolutos: Incluem esquema e dominio (ex.: https://site.com/pagina).
Links relativos: Referem-se a arquivos locais do mesmo site (ex.: ./pasta/arquivo.html).
./: Diretorio atual.
../: Diretorio pai (sobe um nivel).

Atributos Adicionais em Links
target: Define como o link sera aberto.
_blank: Abre o link em uma nova aba.
_self: Abre o link na mesma aba (comportamento padrao).
rel: Define a relacao entre a pagina atual e o link.
noopener: Melhora a seguranca ao evitar que a nova aba tenha acesso a pagina de origem.
noreferrer: Evita que informacoes de referencia (como URL da pagina atual) sejam enviadas ao site de destino.
nofollow: Indica aos motores de busca para nao seguirem o link, util para links patrocinados.


Exemplo de boas praticas ao usar target=?_blank?: 
<a href="https://example.com" target="_blank" rel="noopener noreferrer">Clique aqui</a>


Imagens
<img>: Insere imagens.
src: Caminho da imagem (absoluto ou relativo).
alt: Texto alternativo para acessibilidade (obrigatorio).
width e height: Especificam largura e altura da imagem (opcional, mas recomendado).
Void element: Nao possui tag de fechamento.
Boas Praticas
Use alt em todas as imagens para descrever o conteudo e garantir suporte para leitores de tela e falhas no carregamento.
Use links relativos para arquivos internos, e inclua ./ no inicio de links relativos para evitar problemas.

GitHub
Aulas GitHub (via app)
https://www.cursoemvideo.com/curso/curso-de-git-e-github/aulas/aulas-de-git-e-github

Commits

Uma boa mensagem de commit explicara o motivo por tras das suas alteracoes, ou seja, ela descreve qual problema suas alteracoes resolvem e como elas resolvem isso.

Commits eficazes consistem de duas partes separadas: um assunto e um corpo:
Assunto
Um resumo breve da alteracao que voce fez no projeto.

?Esta e a alteracao que fiz na base de codigo.?

Corpo
Descreva o problema que seu commit resolve e como resolve.


Agora que aprendemos o segredo para criar uma boa mensagem de commit, vamos tentar corrigir a mensagem de commit de antes:

Exemplo de bom commit:
Assunto:
Adicionei link e texto alternativo faltantes no logo da empresa.
Corpo:
Leitores de tela nao lerao as imagens para usuarios com deficiencia sem essas informacoes.

E lembre-se: o GitHub tem um limite de 72 caracteres, por isso recomendamos manter o assunto dos seus commits dentro dessa quantidade.

Quando fazer um commit
E onde voce salvaria o jogo pra nao dar ruim caso o personagem morra kkkkk
Ou seja, faca commits sempre que houver mudancas significativas no codigo, como corrigir um erro ou fazer uma funcionalidade funcionar corretamente. Isso cria um historico do seu progresso e permite voltar a versoes anteriores, caso algo quebre mais tarde.

Dica extra:
O "Conventional commits" e um exemplo de site com templates de commits que voce pode conhecer e utilizar: https://www.conventionalcommits.org/en/v1.0.0/











