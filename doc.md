---
layout: page
title: Documentation
author: Alex Gil
---

## Contents
{:.no_toc}

* ToC
{:toc}

---

## Prerequisites

This documentation was built with beginners in mind, but has the necessary information for more seasoned producers.

To install and use Ed you will be using your terminal. If you need a refresher, I highly recommend "[The Command Line Crash Course](http://cli.learncodethehardway.org/book/)." Working knowledge of HTML and CSS is also taken for granted. If you're new to HTML and CSS, you may want to check out the relevant courses on [codecademy.com](https://www.codecademy.com/learn/web).

Jekyll does not run very well on Windows machines for now. If you are using Windows, this theme won't work for you, but we hope that you simply deploy our principles, and parts of our stylesheet, on a system like [Hugo](https://gohugo.io/), which does work on Windows.

---

## Installing Ed: Easy

The easy way to do this is not necessarily the more robust, and may simply not work on your system. The easy way could also be called the 'lucky' way. It will work if your system is ready for Ed. Two major caveats to keep in mind if you go the easy route: a) You may run into problems later when some Ed components need updating; and, b) You may run into conflicts if you run several Ruby environments for different projects. That said, if you just want to quickly try Ed, and you don't run into problems installing, this is perhaps the best approach.


If you're using a Mac, make sure you have the appropriate version of [XCode command line tools](https://developer.apple.com/xcode/download/) for your OSX. Using the terminal's `cd` command, switch to the directory where you want to install your project. Once inside the folder, you are ready to download and start using Ed. Enter each of these lines into your terminal (remember to ignore the `$`):

~~~ bash
$ git clone https://github.com/elotroalex/ed.git
$ cd ed
$ gem install bundler
$ bundle install
~~~
