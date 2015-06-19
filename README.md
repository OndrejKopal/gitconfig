# gitconfig
Customized .gitconfig for my friends or anyone who's interested

It's base on Ikar (https://github.com/porn) and Josef (https://github.com/josef-spak) gitconfig.

Create directory with apps setting (for example I use my_settings folder) in your home directory
```
cd ~
mkdir my_settings
cd my_settings
```

Clone this repository
```
git clone http://github.com/OndrejKopal/gitconfig
```

Apply gitconfig
```
cd ~
ln -s my_settings/gitconfig/.gitconfig
```

Now you can change your user informations
```
git config --global user.name "Super Loony"
git config --global user.email "loony(:))superloony.info"
```

The last step: include the git prompt config to your bash shell config file
```
$ echo "source ~/my_settings/gitprompt" >> ~/.bashrc
```
