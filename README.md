BaseProject
===========

What is BaseProject ?
---------------------

BaseProject is an attempt at creating a simple way to manage project stubs with the help of git and the GitHub platform. This is done through a simple bash script that takes a lot of inspiration from [Yeoman](http://yeoman.io/).

Basically, you store some projects you want to use as bases on your GitHub repo. You configure the BaseProject to look up on that repo, and it will allow you to interactively clone, rename, scrap off the git history and start a new repo.

*Warning: this project is still in developement and is not really functionnal as it is.*

Getting BaseProject
-------------------

As of now, BaseProject is hosted on GitHub [here](https://github.com/Marneus68/BaseProject), that might change some day.

Using BaseProject
-----------------

```
bp
```

Command line parameters
-----------------------

```
-l | --login
```

```
-d | --default
```

```
-u | --update
```


Installation
------------

Dependencies
------------

BaseProject is designed to have a very limited number of dependencies, most of which are probably alredy present on your system if your using a UNIX-based OS. The only dependency that shouldn't be present on your system by defaulti is [git.](http://git-scm.com/).

The exhaustive list of dependencies is as follows: 

- bash
- curl
- sed
- tput
- git

FAQ
---

Footnote
--------

```
Bash for programming,
Pain and frustration,
Punching the screen.
```

