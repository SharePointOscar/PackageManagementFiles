#MY PACKAGE MANAGEMENT FILES  

![alt text](packages.png "Package Management on My Macbook Pro")

##Overview
I like to have some control to the chaos of installing different packages and libraries on my Macbook Pro.  These are the files I use to keep things in order.

###BrewFile
I use homebrew to manage various casks and software I need.

Within the directory where the Brewfile resides, run the following command

```shell
brew bundle install
```

![alt text](BrewBundleInstall.png "The command to run for updating and installing Casks")

###Gemfile
To manage my Gems I use RVM which is typical.  However, having a Gemfile to replicate my Gems across development machines is a nice thing to have :)

Within the directory where the Gemfile resides, run the following command

```shell
brew bundle install
```
![alt text](GemfileRunBundler.png "The command to run for updating and installing Gems")