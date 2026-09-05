---
title: Installing Python on Mac/Linux
template: default
---
On Mac use homebrew
brew install python@3.14

On Linux, ubuntu say you can use apt package manager, but you have to add additional repo to obtain python 3.14

Something like
sudo apt install software-properties-common
sudo apt update
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.14 


After installing python, you can check the version by running
python --version

If this does not work the python installation is probably not on system path



