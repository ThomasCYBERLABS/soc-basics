# === PASSOS GIT/GITHUB ===

# PASSOS DE 1ª VEZ (quando ainda não existe repo local)

-Criar repo no GitHub (site) ou já ter URL do repo
-No PC:
    -git clone <url> (ou criar pasta e fazer git init)
    -git remote add origin <url> (se usou git init)
    -git remote -v
    -git branch -M main
    -git push -u origin main (primeiro push)

=======================================================

# PASSOS GIT/GITHUB (dentro de um repo já conectado)

-Criar pastas/arquivos
    -mkdir runbooks, writeups, troubleshooting -Force
    -ni runbooks\README.md, troubleshooting\README.md, writeups\README.md

Editar no VS Code / Notepad
    -README = propósito + índice
    -Arquivos .md = conteúdo real (runbook/writeup/erros)

Salvar versão e enviar
    -git status 
    -git add . (ou git add caminho\arquivo.md)
    -git commit -m "mensagem curta do que mudou"
    -git push

======================================================    

# OBS: 

Ao criar um repositório ou arquivo de texto, deve-se verificar o status e adicionar as mudanças ao git, e assim deve-se confirmar com uma mensagem curta, também explicando sobre o que foi feito, e ao final enviar para o github. Também há o meio de editar no github também, e depois salvar no pc. 

======================================================

# COMANDOS GIT:

git clone - baixa um repositório do github pro seu pc, já conectado ao remoto.

git init - transforma uma pasta do seu pc em um repositório git (local)

git remote add origin <url> - conecta seu repositório local a um repositório remoto (github)

git remove -v - mostra pra onde seu repositório está apontando (url do github)

git branch -M main - renomeia/define o branch atual como main (padrão hoje)

git status - mostra o que mudou e o que está pronto pra commit.

git add . / git add (arquivo) - seleciona mudanças para entrar no próximo commit ("staging"). 
"." = tudo   

git commit -m "(mensagem)" - salva uma versão no histórico local com uma descrição.

git push - envia seus commits pro github

git push -u origin main - primeiro push + define "upstream" (liga seu branch local main ao remoto origin/main)

git pull - quando se edita no github e quer salvar no pc.




