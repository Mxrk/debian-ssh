# debian-ssh

Simple debian container with the sshd service.

# Why?
Every public dockerfile I found was outdated and didn't work, that's why I created
my own.

# How to use
`docker run -d -p 22:22 mxrkw/debian-ssh`


`ssh root@container -p 22`

The username is "root" and the password is "password". You can easily modify
it in the dockerfile.



