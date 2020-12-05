# chrome-extensions

## init
``` bash
git submodule update --init --recursive
```

## FMI:
### how to add chrome-extension
``` bash
git submodule add -f -b master $submodule_url
```

### how to update
``` bash
git submodule foreach git pull origin master
```
