# git-commands

## koble opp nytt repo
|description|command|
|--|--|
|lage repo|gjennom https://github.com/KristianHafell?tab=repositories -> new -> fyll ut|
|koble opp i terminal| `git clone git@github.com:owner/git-repo.git . `|

## når jeg skal kode
|description|command|
|--|--|
|ny branch|`git checkout -b new-branch`|
|add file|`git add filepath`|
|add noe fra fil|`git add -p README.md`|
|commit|`git commit -m "description"`|
|push to main|`git push`|
|hvis ny push|`git push --set-upstream origin new-branch`|
|for å legge til github|cmd-click: https://github.com/owner/git-repo/pull/new/new-branch|
|lage pull request|klikk: create pull request|
|lage draft pull request|klikk: draft pull request|
|hvis legge til|klikk: rebase and merge|
|etterpå| slack melding til Dennis|
|gå tilbake til main|`git checkout main`|
|få endringene fra merge|`git pull`|
|slette branch|`git branch -d new-branch`|

## inspeksjon
|description|command|
|--|--|
|quit|trykk: `q`|
|Se forskjeller i filen|`git diff`|
|Se log|`git log`|
|Se log penere|`git log --graph`|
|se hvem som har gjort endringer|`git blame filepath`|

