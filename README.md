hub for Windows
============

This is a Windows fork of [hub tool](https://github.com/defunkt/hub).

hub is a command line tool that wraps `git` in order to extend it with extra
features and commands that make working with GitHub easier.

~~~ sh
$ hub clone rtomayko/tilt

# expands to:
$ git clone git://github.com/rtomayko/tilt.git
~~~

hub can aliased as `git`, so you can type `$ git <command>` in the shell and
get all the usual `hub` features.


Installation on Windows
------------

Dependencies:

* **git 1.7.3** or newer
* **Ruby 1.8.6** or newer


### Installation with MSYS Bash:

1.  Install [msysgit](http://msysgit.github.com/)
2.  Install Ruby with [RubyInstaller](http://rubyinstaller.org/)
3.  Add ruby\bin\ to your system `PATH` variable
4.  Download [hub](http://yradtsevich.github.com/hub-windows/hub) into your git\bin\ folder

### Installation without MSYS Bash:

1.  Install Git
2.  Add git\bin\ to your system `PATH` variable
3.  Install Ruby with [RubyInstaller](http://rubyinstaller.org/)
4.  Add ruby\bin\ to your system `PATH` variable
5.  Create 'hub' folder and download [hub](http://yradtsevich.github.com/hub-windows/hub) and [hub.bat](http://yradtsevich.github.com/hub-windows/hub.bat) into it
6.  Add hub\ to your system `PATH` variable

### Set editor for pull requests
**Full path** to a Git editor **must** be specified. To do it, you may use one of the following commands:
~~~ sh
$ git config --global core.editor "C:/Windows/notepad.exe"
$ git config --global core.editor "C:/Program Files/Git/share/vim/vim73/vim.exe"
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
~~~ 

More Info
---------------
Original hub tool: <https://github.com/defunkt/hub>