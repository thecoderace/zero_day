# Project: 0x00. [Optional] Vagrant

## What is Vagrant?

Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.

In a nutshell, Vagrant is a tool for working with virtual environments, and in most circumstances, this means working with virtual machines.

## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), without the help of Google:

## General

* What is a virtual machine
* What is Vagrant
* Who wrote Vagrant
* What is Ubuntu
* What does “Ubuntu” mean
* How to use VMs with Vagrant
* What does the command `uname` do

# More Info

## Install `git`

If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

## Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

## Warning

 * This project `can’t be done in Sandboxes` - it can be done only in your local computer. Please refer to our concept pages for your operating system.

# Project Tasks

## Create and setup your Git and GitHub account

[README.md](./README.md) - You will need Git for this project, you might have to [install it](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) on your computer if it’s not done yet.

* Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

On [GitHub.com](https://github.com):

* Using the graphic interface on the website, create the repository (if it’s not done yet)
    * Description: `This is my first repository as a full-stack engineer`
    * Public repo: `zero_day`
    * No `README`, `.gitignore`, or license

On your computer, open a terminal and do the following:

* Navigate to your home directory. [Tips](https://linuxconfig.org/single-linux-command-to-return-to-home-directory)
* Create a directory `zero_day`. [Tips](https://help.ubuntu.com/community/Beginners/BashScripting)
* Navigate to this new directory. [Tips](https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal)
* Initialize git and add the remote origin
* Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://wordpress.com/support/markdown-quick-reference/) text to present this project. `This file is mandatory in projects`
* Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your `first repository` of the `first task` of your `first School project`.

# Advanced Task:

## Hello Ubuntu

[0-hello_ubuntu](./0-hello_ubuntu) - Inside the `zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory.

`ssh` into your Ubuntu VM. What does the command` uname` print when you run it without any option?

Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file accordingly as shown below:

Repo:

* GitHub repository: `zero_day`
* Directory: `0x00-vagrant`
* File: `0-hello_ubuntu`



