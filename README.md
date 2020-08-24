

A program that was used as the donation bar for SDC's 10th Anniversary Gala. It keeps track of the total amount of funds raised from the gala and displays it both numerically and visually. 




Installation
------------

### Install Homebrew
``` Shell

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/
  install/master/install.sh)"
  
  
brew update

```
### Install Python 
``` Shell
brew install python python3


brew link python


brew link python3
```

### Update ~.bash_profile
``` Shell
nano ~/.bash_profile
```
Add the following and save .bash_profile
```
# Homebrew
export PATH=/usr/local/bin:$PATH


# point to python2
export PATH="/usr/local/opt/python/libexec/bin:$PATH"
```

``` Shell
source ~/.bash_profile
```
### Install OpenCV
``` Shell
brew install opencv
```

Usage
-----

Every time the space bar is pressed, the donation bar goes up by $500


Staff
-----

Programmer : Joon Kang


Artist : Juan Juan Yin


Work Period
-----------

Start Date: 2019-12-27


End Date: 2019-12-30

