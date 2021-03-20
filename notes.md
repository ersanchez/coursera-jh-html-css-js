# Introduction

These are my set up notes for using GNU/Linux (Ubuntu 20.04 desktop) to take the Coursera/Johns Hopkins course, HTML, CSS, and Javascript for Web.

## Web Sites

### Github

You need a Github account to submit your assignments.

If you don't already, have a [github](https://github.com) account, create one now.

## Software

### Sublime Text 3

Go to the Sublime [Linux downloads](https://www.sublimetext.com/docs/3/linux_repositories.html) page: 

Follow the directions for your distribution

### Git

This is in your package manager.

For Ubuntu, here are the installation steps:

	$ sudo apt install git
  
Follow the steps in the [Git Book](https://git-scm.com/book/en/v2), section 1.6 to get git setup

### NodeJS

NodeJS will also be available in your package manager.

For Ubuntu, here are the steps:

	$ sudo apt install nodejs

### Browser-Sync

Next we'll install this cool app that watches a file and updates the webpage whenever you make a change to the HTML file.

In your terminal type:

	$ sudo npm install -g browser-sync

That `-g` will install browser-sync for all users on your computer.

To run it, first create a directory where you will put all of your course files.Change directory to this new directory and create a basic `index.html` file.

When you have your basic HTML file, just launch `browser-sync` as a server:

	$ browser-sync start --server --directory --files "*"

## Helpful Sites

### JSfiddle

https://jsfiddle.net

Share your HTML, CSS, and Javascript or just use this to write/test your code.

### CodePen

https://codepen.io

This site is very similar to JSfiddle.

### CSS Tricks

https://css-tricks.com

Another Chris Coyier site - this time dedicated to CSS.

