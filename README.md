
Git Repository Creations

$ git init GIT
$ git add .
$ git commit -m "Initial commit"

Git Create Branches localy from master head revison 

$ git branch sit
$ git branch qa
$ git branch dev

Add file change and publish local SIT branch into remote

$ git push -u origin sit

Add file change and publish local QA branch into remote

$ git push -u origin qa

Add file change and publish local DEV branch into remote

$ git push -u origin dev

Creating feature branches which is not affecting any remote branches
 - Find the latest HEAD node version
 $ git rev-parse --short HEAD
 - Create new branch with this revision id
 $ git branch branch-name revision-id
 - Switch to local branch
 $ git switch branch-name


