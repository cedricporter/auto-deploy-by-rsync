auto-deploy-by-rsync
====================

use inotify to check file change and auto deploy.

## Linux

Before using this script, you need to do `sudo apt-get install inotify-tools`.

Then link `auto-deploy-by-rsync` into you $PATH.

After that, you can run this on your project folder to auto copy this folder to remote server.

```
auto-deploy-by-rsync . user@everet.org:~/work/2959_add_new_type_awards
```


## Mac
In Mac OS X, we need fswatch.

```
brew install fswatch
```

Link `mac-auto-deploy` into you $PATH.
And run this on your project folder.

```
mac-auto-deploy . gzhualiang@dev35:~/git/`basename $(PWD)`
```

## Screencast
![sample](http://everet.b0.upaiyun.com/imgs/mac_20140301_225042_77450LLb.gif)
