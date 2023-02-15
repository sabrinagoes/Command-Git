# Command-Git
*

List of git command

cd nomeCaminho (Caminho da pasta do projeto)

git add nomeDoArquivo (adiciona o arquivo que vai ser comitado)

git status (visualiza se o arquivo já está pronto para ser comitado)

git commit -m "Mensagem do Commit" (cria o commit do arquivo)

Dentro do projeto criar arquivo ".gitignore" e colocar camminhos de pastas e arquivos que não devem ser comitados.

.gitignore deve ser comitado

*
*
*
CRIAR SERVIDOR REMOTO LOCAL

git init --bare (primeiro passo para criar o servidor local, caso tenha esquecido de --bare digite: git config core.bare true)

git remote add local {caminho} (adicione o caminho da sua pasta)
*
*
*
PARA CLONAR PROJETOS PARA SEU GIT

git clone {caminho} projeto (Substitua {caminho} pelo caminho completo da pasta que criamos no primeiro passo)

git remote rename origin local (para acessar a pasta Projetoexecute o comando, renomeando o repositório de "origin" para "local" )

git push local main (para enviar as suas modificações para o seu servidor)

git pull local main (para baixar as modificações)

ENVIAR PARA O REPOSITÓRIO DO GITHUB


