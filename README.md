# GitHubHelp 
## Commands
* git status
  - xx
* git clone "url copiada do GitHub"
  - xx
* git remote -v 
  - xx
* git add . 
  - adiciona tudo da pasta 
* git commit -m "mensagem "
  - commit local 
* git push origin main 
  - empurra tudo commitdado anterior para a branch master 
* git push origin HEAD 
  - empurra tudo commitdado anterior para a HEAD, pois HEAD aponta para main
* git branch
  - lista os ramos (branches) do repositório
* git log
  - lista os commits
*The command to delete a local git branch can take one of two forms:
  - git branch –delete old-branch
  - git branch -d old-branch
    
* git checkout -b "branch name"
  - cria uma nova branch
  
* sequencia básica
  - git status 
  - git add .
  - git commit -m "mensagem "
  - git push origin "nome_branch"
  
* git log - visualiza as ações no git da mais recente para a mais antiga

* git reset --soft HEAD~1 : cancela o última commit >> Muito útil para desfazer commits locais e corrigir situações de falhas ao se tentar fazer o push.

* git pull origin rcp/vaccination-proximity  : atualiza localmente os arquivos remotos (Github)

* The command to delete a local git branch can take one of two forms:
  - git branch –delete old-branch
  - git branch -d old-branch

* reset commits locais e força sincronizar local e remoto. ATENÇÃo: antes de tudo, faça backup de todo o projeto.
  - git reset --hard origin/master

* git stash - guarda na pilha as alterações locais para posterior commit e push
* git restore - descarta as alterações locais no arquivo específico e permite as próximas operações.
   - git restore "nome do arquivo"
