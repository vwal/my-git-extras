
my-git-extras
=============

Various documented Git aliases and scripts I have found useful in everyday Git use. Some of the scripts have been written by me, others (like git-wtf) have not.


To install
----------

1) Clone from GitHub

2) Include the my-git-extras/.gitconfig from your ~/.gitconfig, like so:

```
[user]
        name = Your Name
        email = your@email.com

[include]
        path = /opt/my-git-extras/.gitconfig
```


Alias dependencies
------------------

Currently the only external dependency (besides the scripts in this repository) that some aliases refer to are some **git whistles** (https://github.com/mezis/git-whistles, install with: `rvm @global do gem install git-whistles`) commands.


Other recommended Git extensions
--------------------------------

**git-extras**  
https://github.com/tj/git-extras

**git-up**  
https://github.com/aanand/git-up<br />
(install with: `rvm @global do gem install git-up`)


**Adam's git shortcuts and environment**  
https://github.com/aspiers/git-config

**git-mv-with-history**  
https://gist.github.com/emiller/6769886


Note
----

As of writing of this I'm using these aliases and scripts on Ubuntu 14.04 and 16.04 with Git 2.10.1 (from [Launchpad PPA](https://launchpad.net/~git-core/+archive/ubuntu/ppa), **ppa:git-core/ppa**). Most will likely work with Git 1.8.0+ or Git 1.7.0+, as well as on other platforms (OSX, etc..), but I have not tested them outside of Ubuntu, so as always, YMMV.
