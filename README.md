# chrome-extensions

## FMI:
### how to add chrome-extension
```
git submodule add -f -b master $submodule_url
```
### how to update
```
git checkout latest || git checkout -b latest

git submodule foreach git pull origin master
```
