Web Template
============

This is a simple web starter project that includes Bootstrap, jQuery, and D3 and various Grunt tasks I developed for a class I teach. This template uses build and watch Grunt tasks to stage and test a website. The build folder will be generated in `dist` and source files in `src`.

## Installation Instructions

**1. Install Node**

To install this template system, you first need to install Node/NPM on your computer. The LTS version is recommended.

[https://nodejs.org/en/](https://nodejs.org/en/)


**2. Clone repository**

Next, clone (or fork) this repository using the Terminal program on your Mac (command line). It is recommended to change your directory using the `cd` command to a location where you want to serve and work on your project. i.e. `cd ~/Desktop` before running the command below.

```
$ git clone https://github.com/jrue/web-template.git
```

**3. Install this template system**

Next, move into the directory you just cloned, and run the command below to install all of the dependencies. This only installs them within this folder. 

```
$ cd web-template

$ npm install
```

Now, you're ready to work on the project. Open the folder in Sublime. 

## Installing Grunt (Optional)

It's easiest to install Grunt globally, so that you can use simple grunt tasks. I've added a couple of scripts in case you wish not to install globally.

```
$ npm install -g grunt-cli
```

**If you don't want to install Grunt globally**, to run the two grunt commands I've setup use `npm run`.

```
$ npm run grunt
```

Open your web browser to the url given and work on the project!

