# My Sublime Text 3 Settings & Packages
Stolen from this blog post: https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d#.dl5pzen41

## TL; DR
Apply these Submlime Text 3 settings by fetching this repository to your local environment. On a Mac:
```
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
$ git init
$ git remote add origin https://github.com/gwmccubbin/sublime_settings.git
```
**[STOP]** Back up your settings file first, or remove the `--hard` flag & resolve merge conflicts manually:
```
$ git reset --hard origin/master
```
Restart Sublime Text 3 to apply these settings & install packages.

You can keep your environment in sync once it's configured:
```
$ git -C ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User pull origin master
```
