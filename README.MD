# Curso Digital: Git
- Registro de mudanças em arquivos, que possibilita recuperar ou acesso a versões anteriores.\
- Desenvolvimento de código em colaboração com outros integrantes.
## o que é git?
 ### O git é uma ferramenta de versionamento de código que possibilita uma melhor gestão da criação de aplicações.
- git CLI
- git Desktop
## Git status ciclo de vida 
- Untracked  - arquivo adicionado no projeto
- Unmodified - salvo no estado atual (já recebeu commit e está salvo)
- Modified - sofreu ateração (não recebeu commit e não está salvo)
- Staged - sofreu ateração e foi para area de tranferencia "area do git add" (não recebeu commit e não está salvo)
## Comandos
- git init - inicia o git no repositório local
- git clone + url_do_repopsitorio - traz os arquivos do repositório remoto para máquina local
- git status - demonstra os status dos arquivos trabalhados - untracked - unmodified - modified - staged
- git diff - demonstra a diferença entre o que foi modificado entre os arquivos
- git diff --staged demonstra a diferença entre o que foi modificado em arquivos com status staged
- git commit -m "descrição do commit"
- git log lista commits realizados
- git log --staged  - lista os commits na área de stage
- git log --oneline --decorate - lista HEAD da branch principal e commits realizados
- git restore nome_do_arquivo  - retorna o arquivo informado para um estado anterior
- git restore --staged nome_do_arquivo - retorna o arquivo em estado de staged para um estado anterior
- git push origin nome_da_branch - envia as novas versões dos arquivos para o repositório remoto online
- git pull - traz arquivos do repositório remoto para a máquina local e modifica-os
- git fetch - traz descrição das modificações que serão realizadas através do comando anterior.
- git diff origin/branch - mostra as modificações locais que serão realizadas através do pull
- git branch new_name - cria uma nova branch
- git checkout branch_name - altera entre as branches trabalhadas
- git merge nome_da_branch - realiza a unificação entre branches que estão sendo trabalhadas remotamente
