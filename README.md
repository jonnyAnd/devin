



# Aim: {#aim}

To take the shortest path to get to mid level developer cutting all the crap. We will cover tool, setup, best practice and a few basic coding challenges - aimed to make you understand that all coding languages and jobs are basically the same, just with a little finesse in certain areas.

We will also give you a lexicon to remember Even after 20 years in the industry, every new job is a challenge to start. What makes it easy is remembering the key terms so you know what people are talking about, and giving a starting point to start your google research to learn more


# 


# Setup and getting comfortable {#setup-and-getting-comfortable}


## Get used to the basic tools first {#get-used-to-the-basic-tools-first}

Behind all dev roles, back-end, front-end, devops all of it all use the same few basic things, they are also the things behind all the fancy coding tools that you see people use, so lets get cody with those first


### 


### A sain command line {#a-sain-command-line}

No surprise here! - grown ups cant work in a windows command line, but good news, you don’t have to install a whole system to have this (although you know my thoughts on this ;) ). There is now a way in windows to have a tiny linux system in a box just for this.


#### Install WSL {#install-wsl}



* Do all the steps here: [https://klauswong.medium.com/setup-guide-for-a-cool-terminal-on-windows-with-windows-terminal-and-wsl-d692fa8bdbac](https://klauswong.medium.com/setup-guide-for-a-cool-terminal-on-windows-with-windows-terminal-and-wsl-d692fa8bdbac) 
* When you have completed this you will have:
    *  Linux command line (on a tiny debian install behind the scenes)
    * A terminal application
    * Oh-my-zsh - this is a really cool helper app that you wont be able to live without, you will get into the cool features as we get into things
    * Done a `sudo apt-get update` and `sudo apt-get install -y zsh` These you will do a lot, but basically update your linux system and install the zsh app

**Lexicon terms: **

_Command line, terminal, debian, WSL_


### 


### Install your first linux app {#install-your-first-linux-app}

As windows and OSX has an ‘app store’ linux has had this for years! There is a list of _repositories_ (servers) on your linux machine where you can download all sorts of apps. The handy thing is that when the developer of that app updates it, this system will also handle updating things for you.



* Open your linux terminal
* Update the list of _‘repositories’_ that your system knows about _(note all linux commands start with a ‘$’ when you see them online, its just convention, and you DONT need to copy that bit, i am just including that as you will see it lots)_
    * <code>$ sudo apt-get update<em> </em></code>
* Install a silly program called cmatrix
    * <code>$ sudo apt-get install cmatrix</code> 
* Run cmatrix
    * <code>$ cmatrix</code> 
* Bask in the fact that you now look like a L337 H4x0r
* Stop the cmatrix program with ‘ctrl-c’ (this is how you stop all command line apps, remember this)

<strong>Stretch exercise:</strong>

In the same way, here are some other silly command line apps that you can install



* ‘Cowsay’
* ‘neofetch’

**Lexicon terms: **

_repositories, apt-get, _


### 


### Learn the minimum command line things  {#learn-the-minimum-command-line-things}

I want to show here that this is NOT scary or difficult at all! And by learning a few small basics, you will be able to understand the fundamentals that underpin all development. 

Before we start - 

Always remember this very simple thing, no matter how complicated it _looks _all commands are just ‘**_run this app with this input’_**:

To prove this, we are going to make our first computer program with just the command line! Each step will be an ‘**_run this app with this input’ _**You will see the pattern `$ AppName "input"`



* Open your linux terminal
* With an app called ‘mkdir’ make a folder called ‘leetcode’
    * `$ mkdir leetcode`

Commands you have learned:



* mkdir
* ls

Simply put, the power of the linux command line is how you can ‘chain’ applications and programs to do 


### 


### Setup Git {#setup-git}

When you work you want to save your code off your local machine, on a server, in little steps. So you can track changes, roll them back, and work on little side projects without messing up your main project - this is called _‘source control’ _There are a few source control systems Git, SVN, perforce… But git is the industry standard and is amazing - if a company doesn't use git… run

There are many git code storage servers online - you can even make your own - but for ease we will use the most popular, GitHub



* Open your linux terminal
* Install the git tool to ‘push’ your code to your own ‘repository’
    * `$ sudo apt-get install git`
* To test ‘clone’ someone else's code from github - this is a very simple repo that i own
    * `$ git clone https://github.com/jonnyAnd/git-lesson.git`
* if you now for a ` $ ls` you will see a new folder with this code
* Note that this is the same that you will see if you go to [https://github.com/jonnyAnd/git-lesson](https://github.com/jonnyAnd/git-lesson)

**Lexicon terms: **

_Source control, _
