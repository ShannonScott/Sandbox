# ZSH History

Connect the remote sandbox as the origin for a local repo.  Rebase the remote onto the local, and push to remote.

```
8509  git remote origin git@github.com:ShannonScott/Sandbox.git
 8510  git remote add origin git@github.com:ShannonScott/Sandbox.git
 8511  git pull --rebase
 8512  git pull --rebase master
 8513  git pull --rebase origin/master
 8514  git pull --rebase
 8515  git pull --rebase origin master
 8516  git push
 8517  git push --set-upstream origin master
```

