# WizNote for Mac/Linux


## cross-platform cloud based note-taking client
WizNote is an open-sourced project, published under GPLv3 for individual/personal users and custom commercial license for company users.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.


## Introduction

The project is based on Qt, aimed to provide an excellent PKM(personal knowledge management) desktop environment based on cloud usage. At present, we only have Wiz cloud backend(our company) on the table. but we strong encourage developers to contribute to this project to add more cloud backend for different cloud providers like evernote, youdao, etc...even offline usage.

PKM should be an very important thing cross through one person's life, it's unwise to stick yourself to a fixed service provider or jump around and leave your collected info/secrets behide. PKM should be the same as your mind, fly over the ocean but never splash the waves.

freedom, means knowledge, means PKM, means this WizNote client.

if you are windows or portable platform users, we have WizNote for windows, ios, android from our [Homepage](http://www.wiznote.com)


## Compile

visit: (http://wiznote-qt.com)

Different distributions or platforms
---

### Mac OSX

[Download](http://www.wiz.cn/wiznote-maclinux.html) from our homepage or install from [AppStore](https://itunes.apple.com/cn/app/wiznote/id863771545?l=zh&ls=1&mt=12).

### Ubuntu

install from [PPA](https://launchpad.net/~wiznote-team/+archive/ppa) is much more convenient:

    $ sudo add-apt-repository ppa:wiznote-team
    $ sudo apt-get update
    $ sudo apt-get install wiznote

Also, App Store is not so far!


### Fedora 19/20/21/rawhide

    $ sudo yum install dnf-plugins-core
    $ sudo dnf copr enable mosquito/myrepo
    $ sudo yum install wiz-note

Thanks for mosquito's contribution, [more Fedora/CentOS soft.](https://copr.fedoraproject.org/coprs/mosquito/myrepo/)


### RHEL/CentOS 7

    $ sudo yum-config-manager --add-repo=https://copr.fedoraproject.org/coprs/mosquito/myrepo/repo/epel-7/mosquito-myrepo-epel-7.repo 
    $ sudo yum install epel-release 
    $ sudo yum install wiz-note


### others

Read the compile section and compile for your own flavor!


*All things done, enjoy!*
