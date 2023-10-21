# dotfiles

```bash
for f in $(ls -a |  egrep '^\.\w+.*' | grep -v '.git'); do ln -sf $PWD/$f ~/$f; done
```
