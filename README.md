IMPORTANT: Outputs correctly only for git of version 1.8.3 and later!!!

Lists git directories in pretty human readable format.
Shows file name, when it was changed, abbreviated commit hash, author and commit message.
This information is really useful when you're getting acquainted with some repository that is unfamiliar to you. 

This is a modification of a script that was provided in one of the answers to this stackoverflow.com question:
http://stackoverflow.com/questions/17359370/git-show-last-commit-date-and-message-for-each-file-in-directory-like-github

Clone this repo and add bash alias in your .bashrc that will point to `gitls` file. Like this one:
```shell
alias gitls="bash ~/your-github-repos/gitls/gitls"
```

![Pretty git ls-tree](/gitls.png?raw=true "Example output")

You can pass arguments to gitls. If you pass no arguments, it will try to list only current working directory. If passed argument is a directory that belongs to some git repo, it will be "gitlsed".

Tested:
- in gnome-terminal on Ubuntu 14.10
- in gnome-terminal on Ubuntu 12.04.5 LTS (with upgraded git version 2.6.3!)
- in urxvt on Ubuntu 14.04
- in roxterm on Ubuntu 14.04
- in xterm on Ubuntu 14.04
