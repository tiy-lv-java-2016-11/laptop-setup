# Laptop Setup

Open a terminal window. `command+space` and search `terminal`

## Homebrew
Homebrew is a really cool program that will allow you quickly install programs we often use as developers.
* Install [homebrew](http://brew.sh/)
* Update: `brew update`

## Java Install
* Make sure you have the correct version of java type `java -version` and make sure it starts with 1.8
* If NOT: Install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

## Install Maven
* `brew install maven`

## IntelliJ
IntelliJ is an integrated development environment (IDE)
* Install [IntelliJ Community Edition](https://www.jetbrains.com/idea/download/)

## SSH Keys
We need to generate some encryption keys for our system.
* `ssh-keygen`
* Accept all the defaults and don't set a password

## Git
Git allows us to share code.
* Type `git` in the terminal. If a dialog appears, click `Install` and go through the steps.
* Update: `git upgrade git`

## Github
This is where you will host your code
* Signup for [Github](http://www.github.com)

### Add the SSH key
This will allow for simple commands on github from your computer without a username and password
* Click your picture in upper right corner 
* Click `Settings`
* Click `SSH and GPG Keys`
* Click `New SSH key`
* Enter a title. This can be anything you would like. I put the name of my computer.
* Go back to terminal and type `cat ~/.ssh/id_rsa.pub`
* Copy the entire block to the clipboard (command + c)
* Paste the block into the `Key` text area
* Click `Add SSH Key` button below the text area
