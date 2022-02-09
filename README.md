# Git_CheetSheet
---
**Version 1.0.0**

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
---

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://dillinger.io/)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://www.markdownguide.org/getting-started/)

- git init --> if you do in the project then it will create history record of that project.

- git status --> current project status, if files are unstaged, added, or commited.

- git add . --> (staged) adds all the untracked files in staging area.

- git commit -m "comments" --> add all the staged files to tracked.

- git restore --staged filename.txt --> this will move the file to untracked stage.

- git log --> shows the history of the file, also the log dates states that the latest changes are on the top.

- git reset --> (hash code of which state you want) bring your project to what ever you desired the condition of the project to be, this results in unstaged condition of the project.

- git stash --> this has to be done after add or staged, which means I dont want you now so go back stage.

- git stash pop --> what ever was on backstage bring it back.

- git stash clear --> cleans out what ever you have kept on back stage.

- git remote add origin https: ---url--> this attachs the remote repo project to your local git repo, but local files won't be seen onremote because you haven't shared it yet.

- rm -rf names.txt --> to remove the file.

- git push origin master --> pushes the local changes to respective remote master branch

- git branch feature --> creating new branch with the name feature.

- git push --set-upstream origin feature --> it helps to create and push local branches to the remote repo

- git checkout main --> to go to the main branch

- git branch -a --> shows all the local and remote branches

- git branch --> shows your current branch

- git branch -m master main --> to rename master to main

- git diff branch1..branch2 --> compare two branches 

- git remote -v --> shows two origin link of remote repo.

- git remote add upstream https: ---url--> add to origin from which you have forked

- git push origin kunal -f --> you are forcing the changes to be pushed on remote after you have already created PR.

- git pull origin main --allow-unrelated-histories --> combines local with remote repo.

---
#License & copyright

&copy; Amrit Bohara, Software Developer


