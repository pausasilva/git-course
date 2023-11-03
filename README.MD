# Curso Digital: Git
- Registro de mudanças em arquivos, que possibilita recuperar ou acesso a versões anteriores.\
- Desenvolvimento de código em colaboração com outros integrantes.
## o que é git?
Snapshots do estado do projeto\
- git cmd\
- git desktop\
- git vscode
## Git status
- Untracked # arquivo adicionado no projeto\
- Unmodified # salvo no estado atual (já recebeu commit e está salvo)\
- Modified # sofreu ateração (não recebeu commit e não está salvo)\
- Staged # sofreu ateração e foi para area de tranferencia "area do git add" (não recebeu commit e não está salvo)
## Comandos
- git init #inicia o git\
- git clone http #clone repositorio\
- git status # status do projeto # Git status\
- git diff # o que foi modificado nos modificados\
- git diff --staged #arquivos modificados no staged\
- git commit -m "descrição do commit"\
- git log #lista commits realizados\
- git log --staged #lista commits na área de stage\
- git log --oneline --decorate #lista HEAD da branch principal e commits realizados
- git restore  File #Retornar modificacoes no arquivo\
- git restore --staged File #Retornar um arquivo do staged antes do commit\
- git push\
- git pull\
-git fetch\
-git diff origin/branch\
-git branch new_name
-git log --oneline --decorate
