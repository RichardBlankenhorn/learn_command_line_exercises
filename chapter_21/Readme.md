# English Questions

What is your shell set to?

> I can type env and hit enter. From here, I can scroll down to SHELL, which is currently set to /bin/bash.

What directory are you in?

> I can type echo $PWD to obtain the current directory or I can type env and hit enter.
> From the list that appears below, I can scroll down to PWD.
> Typing env | grep richardblankenhorn would allow me to locate PWD faster.

What is your home directory set to?

> I can type env | grep richardblankenhorn and then scroll down to HOME, which is set to /Users/richardblankenhorn

Can you set your environment to have DEBUG set to true?

> I can type export DEBUG=true to set DEBUG to true. If I then type echo $DEBUG, the result is true.

Explain how you would change your PATH on your computer

> I can type export PATH=$PATH:/path/to/dir1:/path/to/dir2.
> An example could be export PATH=$PATH:/user/local/bin
