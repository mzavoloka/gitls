Lists current git directory in pretty human readable format.
Shows file name, when it was changed, abbreviated commit hash, author and commit message. Just like github.com does, but a little bit better!

This is a modification of a script that was provided in this stackoverflow.com question:
http://stackoverflow.com/questions/17359370/git-show-last-commit-date-and-message-for-each-file-in-directory-like-github

I have the following alias in my .bashrc:
alias gitls="bash ~/scripts/gitls"

![Pretty git ls-tree](/gitls.png?raw=true "Example output")

Tested only in gnome-terminal on Ubuntu 14.10
