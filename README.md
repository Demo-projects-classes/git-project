# git-project
for git scenarios
use ```https://github.com/Demo-projects-classes/git-project.git``` to clone the repo

**MERGE CONFLICT** = is a situation whereby two different developpers make changes [in the same branch, same file, same ligne of code] and git does not know what changes to take into consideration.

**git checkout -b feature** to switch to a newly  created branch **feature**

**git checkout main** to switch to branch main

**Authentication process with git (repo)**
```git remote set-url origin https://github.com/Demo-projects-classes/git-project.git```

```git remote -v```

```git push origin main```
Username for 'https://github.com': AAichaGit
Password for 'https://AAichaGit@github.com': (P.A.T)

**RESOLVING A MERGE CONFLICT**
```git pull -r```

```vi``` conflicted file and make the change

```git add``` conflicted file

```git rebase --continue```

