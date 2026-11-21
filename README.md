These are some of the essential, focused commands you'll need in Termux. Before you begin anything, install these tools first. 


# Termux update
* Firstly Grant the Termux application access to storage to install tools and save files.
```
termux-setup-storage
```
* Essential commands for updating the system and tools (preferably executed before starting and periodically) 

```
pkg update
```
```
pkg upgrade
```
```
apt update
```
```
apt upgrade
```

 Installing development environments and programming languages in Termux
```
pkg install python
```
```
pkg install python2
```
```
pkg install python3
```
```
pkg install git
```
```
pkg install ruby
```
```
pkg install git
```
```
```
pkg install python
```
```
```
pkg install curl
```
```
pkg install wget
```
```
pkg install nano
```
```
pkg install vim
```
```
pkg install unzip
```
```
pkg install zip
```
```
pkg install tar
```
```
pkg install openssh
```
```
pkg install clang
```
```
pkg install make
```
* Or install them all with one command

  $ pkg install git python curl wget nano vim unzip zip tar openssh clang make -y

  

# Install some utilities in Termux

```
pkg install pip
```
```
pkg install unzip
```
```
pkg install nano
```
```
pkg install x11-repo
```
```
pkg install php
```
# Fix incomplete packages 

If you receive a message about uninitialized packages or missing dependencies, try this 
```
dpkg --configure -a
```
Then this 
```
apt --fix-broken install
```
And then this 
```
pkg update && pkg upgrade -y

```
| command | purpose  |
|---|---|
| pkg update | تحديث الحزم |
| pkg upgrade | ترقية الحزم |
| pkg install git | تثبيت Git |
| pkg install python | تثبيت Python |




