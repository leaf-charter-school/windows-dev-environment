Setting up a Development Environment with Ubuntu - Git - Ruby - Vs Code
=============

Step 1 - installing Ubuntu
===============

* This is easy on windows these days - pick Ubuntu or any other distribution from the windows store as in this brief guide:
[https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

Step 2 - installing Visual Studio code
=================

* Download from : [https://code.visualstudio.com/](https://code.visualstudio.com/)

Step 3 - install git for windows
===============

* Download from: [https://git-scm.com/download/win](https://git-scm.com/download/win)

* Follow the install wizard

Step 4 - Configure VS Code to use Bash
================

* Open code -> preferences -> settings -> click on the little curly braces button in the top left corner and add this snippet to settings.json

```
"terminal.integrated.shell.windows": "C:\\WINDOWS\\sysnative\\bash.exe"
```

* Restart VS Code and use CTRL + ` (control plus the little curly wannabe quotation thing) to open the Integrated Terminal `

Step 5 - Install git on Linux using Terminal
=============

* Type this into terminal, pick you email and username from github:

```
sudo apt install git
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git config --global core.autocrlf input
```

Step 6 - Install ruby using terminal
==============

* Follow the instructions at this link until you get past the install ruby section:

[https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-16-04](https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-16-04)

Step 7 - Make a folder for you projects and stuff to live in:
==========

* In vs code terminal type : cd /mnt/c/Users/(your username)/Documents - put whatever you username is where (your username) is

* Make a new folder - in the vs code terminal type mkdir projects (or whatever name you want) - put all your projects here.

* This means whenever you want to open your terminal you need to type cd /mnt/c/Users/(your username)/Documents/projects to get to your files - or browse to your documents folder in windows explorer.

A lot of this information can be found here:
[https://daverupert.com/2018/04/developing-on-windows-with-wsl-and-visual-studio-code/](https://daverupert.com/2018/04/developing-on-windows-with-wsl-and-visual-studio-code/)
============

the FAQ - where do my files live has step 7.
