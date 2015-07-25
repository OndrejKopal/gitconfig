# gitconfig
Customized .gitconfig for my friends or anyone who's interested

It's base on Ikar (https://github.com/porn) and Josef (https://github.com/josef-spak) gitconfig.

Clone this repository or download zip archive. Include this gitconfig file to your .gitconfig. Example:
```
[include]
    path = /path/to/gitconfig/repository/gitconfig
```

Init .git template directory with tags generate for vim:
```
$ cd
$ ln -s /path/to/gitconfig/repository/gitconfig/.git_templatedir
```

This config doesn't contains user settings. When you can set user informations, plese use these commands:
```
$ git config --global user.name "Super Loony"
$ git config --global user.email "loony(:))superloony.info"
```

Include the git prompt config to your bash shell config file. Example:
```
$ echo "source /path/to/gitconfig/repository/gitprompt" >> /path/to/your/home/directory/.bashrc
```
