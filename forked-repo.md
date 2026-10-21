### Tarea 1: Bifurcar el repositorio

theia@theia-haroldandre1:/home/project$ curl -s https://api.github.com/repos/HaroldMontanoHurtado/mcino-Introduction-to-Git-and-GitHub | jq -r '.parent.clone_url'
https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub.git

### Tarea 2: Corrija el error tipográfico y fusione con main
theia@theia-haroldandre1:/home/project/mcino-Introduction-to-Git-and-GitHub$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
theia@theia-haroldandre1:/home/project/mcino-Introduction-to-Git-and-GitHub$ git branch
  bug-fix-typo
* main
theia@theia-haroldandre1:/home/project/mcino-Introduction-to-Git-and-GitHub$ git merge bug-fix-typo
Updating eee6a45..9cf749a
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
theia@theia-haroldandre1:/home/project/mcino-Introduction-to-Git-and-GitHub$ git branch
  bug-fix-typo
* main

### Tarea 3: Revierta el error tipográfico y envíe una solicitud de extracción


