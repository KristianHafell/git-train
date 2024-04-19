# git-commands

## koble opp nytt repo
|description|command|
|--|--|
|lage repo|`https://github.com/KristianHafell?tab=repositories` -> **new** -> **fyll ut**|
|koble opp i terminal| `git clone git@github.com:KristianHafell/<git-repo>.git . `|

## når jeg skal kode
|description|command|
|--|--|
|sjekk status|`git status`|
|ny branch|`git checkout -b <branch-name>`|
|add file|`git add <filepath>`|
|commit|`git commit -m "<description>"`|
|push to main|`git push`|
|hvis ny push|`git push --set-upstream origin <branch-name>`|
|for å legge til github|cmd-click: `https://github.com/<owner>/<git-repo>/pull/new/<branch-name>`|
|lage pull request|klikk: **create pull request**|
|lage draft pull request|klikk: **draft pull request**|
|hvis legge til|klikk: **rebase and merge**|
|etterpå| **slack** melding til Dennis|
|gå tilbake til main|`git checkout main`|
|få endringene fra merge|`git pull`|
|slette branch|`git branch -d <branch-name>`|

## spesielle tilfeller
|description|command|
|-|-|
|Merge a branch into the current branch|`git merge <branch-name>`|
|add noe fra fil|`git add -p <filepath>`|
|endre siste commit-melding|`git commit --amend -m "ny melding"`|
|angre siste commit og behold endringene|`git reset HEAD~`|
|Stash changes|`git stash`|
|Apply stashed changes|`git stash apply`|
|List stashes|`git stash list`|
|Drop a stash|`git stash drop <stash-name>`|


## inspeksjon
|description|command|
|--|--|
|quit|trykk: `q`|
|Se forskjeller i filen|`git diff <filepath>`|
|se forskjellene mellom to branches|`git diff <branch1>..<branch2>`|
|Se log|`git log`|
|Se log penere|`git log --graph`|
|se hvem som har gjort endringer|`git blame <filepath>`|
|se hvilke filer som er endret i en commit|`git show --name-only <commit-hash>`|
|List all branches|`git branch`|
