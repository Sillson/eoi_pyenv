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

https://conda.io/docs/user-guide/getting-started.html

1. install conda
2. Open up the anaconda prompt and confirm conda is installed by typing `conda --version`
3. Update if preferred `conda update conda`
4. Search for packages by typing `conda search` + the package name `conda search shapely`
5. Search for packages here https://anaconda.org/anaconda/repo and run commands to test for functionality
6. Install packages as specified in the link in #5 of by `conda install` + the package name `conda install shapely`
7. List all packages by typing `conda list`
8. `conda install jupyter`

### Binaries
Why not download from the source? It looks like the Windows installer comes with pip, so we should be able to install packages. 

https://www.python.org/downloads/windows/
https://docs.python.org/3/using/windows.html

1. Install per the instructions above
2. Open up either the installed python command shell or a terminal (command prompt?)
3. `python -V` should return a python version. 
4. `pip install --upgrade pip` should function
5. `pip install jupyter`

### ArcPy

## Mac Users

### Native Python
Congratulations! If you're using a Mac, it's more likely than not you already have a Python version installed. 

1. Open up the terminal (launchpad > Other > Terminal)
2. Type `python -V` 
3. Do you have `pip` installed? Try `pip install --upgrade pip`
4. If step 3 fails, try `sudo easy_install pip`
5. To confirm we can install packages, try `pip install pandas`
6. `pip install jupyter`

### Homebrew Python
Homebrew is an excellent package manager for the MacOS environment. It can handle installing Python binarys and 'shimming' their paths, so that they are the executable of choice for all of your applications. There are also packages available through Homebrew that allow us to have multiple Python binaries, and environments. Ensuring a clean work environment with every project. I recommend `pyenv`, which I'll include a link to as a bonus. 

1. Is homebrew installed? Open up a terminal and try `brew upgrade && brew doctor`
2. If this succeeds, you will update your packages -- if not, install homebrew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
3. Is python installed? Try `brew list` and look for either `python` or `python@2` listed in your packages
4. Do you have `pip` installed? Try `pip install --upgrade pip`
5. If step 3 fails, try `sudo easy_install pip`
6. To confirm we can install packages, try `pip install pandas`
7. `pip install jupyter`

### Conda Install
```
Conda is an open source package management system and environment management system that runs on 
Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their 
dependencies.Conda easily creates, saves, loads and switches between environments on your local 
computer. It was created for Python programs, but it can package and distribute software for any language.
```

https://conda.io/docs/user-guide/install/macos.html
https://conda.io/docs/user-guide/getting-started.html

1. install conda
2. Open up a terminal and confirm conda is installed by typing `conda --version`
3. Update if preferred `conda update conda`
4. Search for packages by typing `conda search` + the package name `conda search shapely`
5. Search for packages here https://anaconda.org/anaconda/repo and run commands to test for functionality
6. Install packages as specified in the link in #5 of by `conda install` + the package name `conda install shapely`
7. List all packages by typing `conda list`
8. `conda install jupyter`
