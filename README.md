# Installation
In Cygwin, clone the git repo:
```
git clone https://github.com/nosuchuser/apt-cyg.git ~/.apt-cyg
```

Make the apt-cyg file executable:
```
chmod +x ~/.apt-cyg/apt-cyg
```

Modify your `.bashrc` file and ddd the `.apt-cyg` folder to your path:
```
PATH=$PATH:$HOME/.apt-cyg
```

# Use
Run `apt-cyg` as you would `apt-get`. Example:
```
apt-cyg install git
```
