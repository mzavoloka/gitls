IMPORTANT: Outputs correctly only for git of version 1.8.3 and later!!!

Lists current git directory in pretty human readable format.
Shows file name, when it was changed, abbreviated commit hash, author and commit message. Just like github does, but a little bit better!

This is a modification of a script that was provided in on of the answers to this stackoverflow.com question:
http://stackoverflow.com/questions/17359370/git-show-last-commit-date-and-message-for-each-file-in-directory-like-github

I have the following alias in my .bashrc:
```shell
alias gitls="bash ~/scripts/gitls"
```

![Pretty git ls-tree](/gitls.png?raw=true "Example output")

Tested:
- in gnome-terminal on Ubuntu 14.10
- in gnome-terminal on Ubuntu 12.04.5 LTS (with upgraded git version 2.6.3!)
- in urxvt on Ubuntu 14.04
- in roxterm on Ubuntu 14.04
