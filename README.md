# git-commands (made by the best)

## når jeg skal kode
|description|command|shortcut(egen)|
|--|--|--|
|sjekk status|`git status`|`gs`|
|ny branch|`git checkout -b <branch-name>`|`gcob <branch-name>`|
|add file|`git add <filepath>`|`ga`|
|commit|`git commit -m "<description>"`|`gc -m "<description>"` eller `gcm "<description>"`|
|push to main|`git push`| `gp`|
|hvis ny push|`git push --set-upstream origin <branch-name>`| `gpsuo <branch-name>`|
|for å legge til github|cmd-click: `https://github.com/<owner>/<git-repo>/pull/new/<branch-name>`|
|lage pull request|klikk: **create pull request**|
|lage draft pull request|klikk: **draft pull request**|
|hvis legge til|klikk: **rebase and merge**|
|etterpå| **slack** melding til Dennis|
|gå tilbake til main|`git checkout main`| `gco main`|
|få endringene fra merge|`git pull`|`gpl`|
|slette branch|`git branch -d <branch-name>`|`gbd <branch-name>` eller `gb -d <branch-name>`|

## spesielle tilfeller
|description|command|shortcut(egen)|
|--|--|--|
|Merge a branch into the current branch|`git merge <branch-name>`|`gm <branch-name>`|
|add noe fra fil|`git add -p <filepath>`|`gap <filepath>`|
|endre siste commit-melding|`git commit --amend -m "ny melding"`|`gc --amend -m "ny melding"`|
|angre siste commit og behold endringene|`git reset HEAD~`| `gr`|
|Stash changes|`git stash`|
|Apply stashed changes|`git stash apply`|
|List stashes|`git stash list`| 
|Drop a stash|`git stash drop <stash-name>`| 

## inspeksjon
|description|command|shortcut(egen)|
|--|--|--|
|quit|trykk: `q`|
|Se forskjeller i filen|`git diff <filepath>`| `gd <filepath>`|
|se forskjellene mellom to branches|`git diff <branch1>..<branch2>`| `gd <branch1>..<branch2>`|
|Se log|`git log`| `gl`|
|Se log penere|`git log --graph`| `glg`|
|se hvem som har gjort endringer|`git blame <filepath>`| `gbl`|
|se hvilke filer som er endret i en commit|`git show --name-only <commit-hash>`|
|List all branches|`git branch`| `gbr`|

## koble opp nytt repo
|description|command|
|--|--|
|lage repo|`https://github.com/KristianHafell?tab=repositories` -> **new** -> **fyll ut**|
|koble opp i terminal| `git clone git@github.com:KristianHafell/<git-repo>.git . `|
