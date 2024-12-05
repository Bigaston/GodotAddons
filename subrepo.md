[Link of git subrepo](https://github.com/ingydotnet/git-subrepo)

1. Open Git Bash
2. `git clone https://github.com/ingydotnet/git-subrepo /path/to/git-subrepo`
3. `nano .bash_profile`
4. Put this inside
```sh
if [ -f ~/.bashrc ]; then . ~/.bashrc; fi
```
5. `pwd`
6. `nano .bashrc`
7. Put this inside
```sh
export GIT_SUBREPO_ROOT="/path/to/git-subrepo"
export PATH="/path/to/git-subrepo/lib:$PATH"
export MANPATH="/path/to/git-subrepo/man:$MANPATH"
```
