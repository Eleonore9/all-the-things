# Install Python 3

Several operating systems come with Python installed (usually Python 2).

One way to install Python 3 alongside other Python scientific libraries is by downloading [Anaconda](https://docs.anaconda.com/anaconda/install/).

Otherwise, install Python 3 using the following information from [installation guides](https://docs.python-guide.org/starting/installation/):

## Install Python 3 on MacOS
[Link](https://docs.python-guide.org/starting/install3/osx/#install3-osx)

Open a Terminal window and type the following commands

1) If you don't have a package manager, install Homebrew:

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

2) Install Python 3:

`brew install python3`

You can check the version of Python install by using the command

`python --version`

## Install Python 3 on Windows
[Link](https://docs.python-guide.org/starting/install3/win/#install3-windows)

Alternative, use the Python installer

1) Go to this [link](https://www.python.org/downloads/release/python-370/) click on `Windows x86-64 executable installer`

2) Choose `Add Python 3.7 to PATH` and follow the installation guide

You can check the version of Python install by writing this command in your terminal

`python3 --V`

## Install Python 3 on Linux

The latest Linux distributions come with Python 3 installed. Check what version you have from your terminal using the command:

`python3 --version`

To install Python 3.7 follow those steps:

[Link](https://tecadmin.net/install-python-3-7-on-ubuntu-linuxmint/)

1) Install some dependencies using the following commands:

```
sudo apt-get install build-essential checkinstall

sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev
```

2) Download Python 3.7

a) Download

```
cd /usr/src

sudo wget https://www.python.org/ftp/python/3.7.2/Python-3.7.2.tgz

```

b) Extract

`sudo tar xzf Python-3.7.2.tgz`

You can now check your install with the command:

`python3.7 -V`
