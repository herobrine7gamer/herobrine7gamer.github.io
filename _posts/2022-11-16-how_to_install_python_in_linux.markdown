---
layout: posts
title:  "How to install python in Linux"
date:   2022-11-16 17:24:2 +0400
---
The process of installing python on linux distributions is really easy . Most distros will package python by default , or offer it in their repository .
if you can't find python in your package manager , you might have to download it from source , or compile it .
The tutorial will go through the installation process of python 3.10 . it should work with all python 3 versions .

# Requirements
You will need :
- Sudo root privileges .
- A good internet connection .
- Simple knowledge of package management and terminals .

# Ubuntu and Debian based distros (apt)
Distros like Ubuntu , Debian , Pop Os , Elementary os and others should have python preinstalled .
if not , type in terminal :
{% highlight ruby %}
$ sudo apt update && sudo apt upgrade
#=> install python and pip with apt .
$ sudo apt install python3 python3-pip
#=> check your python version
$ python3 --version
Python 3.10.6
{% endhighlight %}

# Arch based distros (pacman)
For Arch , Manjaro , Endeavour os and others :
{% highlight ruby %}
$ sudo pacman -S python python-pip
#=> check your python version
$ python3 --version
Python 3.10.6
{% endhighlight %}

# Fedora based distros (dnf)
Fedora , AlmaLinux , Qubes os and others :
{% highlight ruby %}
$ sudo dnf install python3-pip python3-wheel
#=> check your python version
$ python3 --version
Python 3.10.6
{% endhighlight %}

# OpenSUSE (zypper)
{% highlight ruby %}
$ sudo zypper install python3-pip python3-setuptools python3-wheel
#=> check your python version
$ python3 --version
Python 3.10.6
{% endhighlight %}

