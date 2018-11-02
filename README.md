# Python Environment setup for EOI

Let's get everyone setup with a baseline Python enviornment for our tutorial assignments. Everyone is going to have a slightly different setup (computer, OS, version, etc.), so it's important to remember Google is your friend.

## Windows Users

### Conda
```
Conda is an open source package management system and environment management system that runs on 
Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their 
dependencies.Conda easily creates, saves, loads and switches between environments on your local 
computer. It was created for Python programs, but it can package and distribute software for any language.
```

https://conda.io/docs/user-guide/install/windows.html

### Binaries
### ArcPy

## Mac Users

### Native Python
Congratulations! If you're using a Mac, it's more likely than not you already have a Python version installed. 

1. Open up the terminal (launchpad > Other > Terminal)
2. Type `python -V` 
3. Do you have `pip` installed? Try `pip install --upgrade pip`
4. If step 3 fails, try `sudo easy_install pip`
5. To confirm we can install packages, try `pip install pandas`

### Homebrew Python
Homebrew is an excellent package manager for the MacOS environment. It can handle installing Python binarys and 'shimming' their paths, so that they are the executable of choice for all of your applications. There are also packages available through Homebrew that allow us to have multiple Python binaries, and environments. Ensuring a clean work environment with every project. I recommend `pyenv`, which I'll include a link to as a bonus. 

1. Is homebrew installed? Open up a terminal and try `brew upgrade && brew doctor`
2. If this succeeds, you will update your packages -- if not, install homebrew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
3. Is python installed? Try `brew list` and look for either `python` or `python@2` listed in your packages
4. Do you have `pip` installed? Try `pip install --upgrade pip`
5. If step 3 fails, try `sudo easy_install pip`
6. To confirm we can install packages, try `pip install pandas`

### Conda Install
```
Conda is an open source package management system and environment management system that runs on 
Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their 
dependencies.Conda easily creates, saves, loads and switches between environments on your local 
computer. It was created for Python programs, but it can package and distribute software for any language.
```

https://conda.io/docs/user-guide/install/macos.html
