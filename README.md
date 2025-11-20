# push-conf cmds

Print remotes
```sh
git config --get branch.$(git branch --show-current).pushRemote
git config --get remote.pushDefault
git config --get branch.$(git branch --show-current).remote
```

Set remotes
```sh
git config branch.$(git branch --show-current).pushRemote origin
git config remote.pushDefault origin
git config branch.$(git branch --show-current).remote origin
```

Unset remotes
```sh
git config --unset branch.$(git branch --show-current).pushRemote
git config --unset remote.pushDefault
git config --unset branch.$(git branch --show-current).remote
```
