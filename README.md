# Setup Development Environment


### Getting Started: Operating System

* Install Ubuntu 20.04 ( https://releases.ubuntu.com/20.04/ ).
* Install all updates
* Install Virtual Box Guest Additions (only if you use VirtualBox for development)

### Getting Started: Base Software

**Update**

```bash
sudo apt update
```

**Node**

```bash
sudo apt install nodejs
sudo apt install npm
sudo npm install -g n
sudo n stable
```

```bash
sudo npm install yarn -g
```

**git**

```bash
sudo apt install git
```

Create new ssh key and add it to github:

```bash
ssh-keygen -t ed25519 -C "info@geoswap.app"
``` 


**Visual Studio Code**

```bash
sudo snap install code --classic
``` 

### Setting up Development Environment

We create a directory 'develop' in your home dir, everything will be in there

```bash
mkdir develop
cd develop
```

Clone

```bash
git clone git@github.com:geotokenapp/eslint-config-geoswap.git
git clone git@github.com:geotokenapp/geoswap-sdk.git
git clone git@github.com:geotokenapp/geoswap-uikit.git
git clone git@github.com:geotokenapp/geoswap-frontend.git
```



## Publishing Package

in .bashrc:

export NPM_TOKEN="YOUR TOKEN"


To publish call:

npm publish --access public



