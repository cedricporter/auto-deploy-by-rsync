auto-deploy-by-rsync
====================

use inotify to check file change and auto deploy.

## Linux
You need libnotify

put `auto-deploy-by-rsync` in you $PATH.

run this on your project folder
```
auto-deploy-by-rsync . user@everet.org:~/work/2959_add_new_type_awards
```


## Mac
```
brew install fswatch
```

put `mac-auto-deploy` in you $PATH.
run this on your project folder.

```
mac-auto-deploy . gzhualiang@dev35:~/git/`basename $(PWD)`
```
