# Dillinger

# Some tip for Git command line:

## Git submodule

Git create submobule

```sh
cd dillinger
npm i
node app
```

### Git change tag or branch submodule
In root folder: 
```sh
git submodule update --init --recursive --remote 
```
cd to folder submodule
```sh
cd submodule_name
git checkout branch_name/tag_name
```
Commit to repository
```sh
git add .
git commit -m"change submodule"
git push
```

### Tips
#### Add file
```
git add .
```
### Commit file
```
git commit -m"commit file"
```

### Combine add and commit in single command(must be tracked file)
```
git commit -am "combine add & commit"
```
### Custom git command
```
git commit --global alias.drxgonio "!git add -A & git commit -m"
git drxgonio "add & commit include file untrack"
```

### Git change message old commit
```
git commit --amend -m"change message done!"
```

### Git reset 
- Hard reset
```
git reset --hard
```
- Soft reset
```
git reset --soft HEAD~1
```
