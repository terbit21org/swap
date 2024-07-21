# Swap

Simple swap setup script for Linux

Swap is an area on a hard drive that has been designated as a place where the operating system can temporarily store data that it can no longer hold in RAM.

Disclamer: This script may not work on every GNU/Linux distro. Sorry.

## Usage

First of all, download the main script using `wget` or `curl`:
```
wget https://raw.githubusercontent.com/terbit21org/swap/master/swap.sh -O swap.sh
# or using curl:
# curl https://raw.githubusercontent.com/terbit21org/swap/master/swap.sh -O swap.sh
```

Then simply run the file with this format:
```
sh swap.sh <size>
```

Example (with 4G):
```
sh swap.sh 4G
```

The default path for the swap file is /swapfile. If you wish to change this, simple the file location (file must not exist) add it to the command:
```
sh swap.sh 4G /swap
```
