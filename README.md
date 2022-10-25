# Dillinger

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
