## selective git repos

> Git remote add origin git

```bash
$ git init

$ git add .
or..
$ git add -A

$ git commit -m "first comment"

$ git remote add origin git@`<host id>`:skyinnkTech/markdown.git

$ git push -u origin <branch>
($ git push -u origin master)
$ git pull
```

- use `git restore <file>...` to discard changes in working directory)

## Default git repos

> …or create a new repository on the command line echo "# test" >> README.md

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:skyinnkTech/test.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin git@github.com:skyinnkTech/test.git
git branch -M main
git push -u origin main
```

## Generating public/private ed25519 key pair.

```bash
skyde@SEL MINGW64 ~
$ ssh-keygen -t ed25519 -C "yourEmail"

Enter file in which to save the key (/c/Users/skyde/.ssh/id_ed25519): /c/Users/skyde/.ssh/id_ed25519_<alies>

Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/skyde/.ssh/id_ed25519_<alies>
Your public key has been saved in /c/Users/skyde/.ssh/id_ed25519_<alies>.pub
The key fingerprint is:
SHA256:84F6149qR4HJRoHYA2vY12hJZzrS5DovPuryhGgg5sE <email>
The key's randomart image is:
+--[ED25519 256]--+
|      .+o.+.     |
|     o.*+B.      |
|    . = X+.o     |
|.    . = o= .    |
|oE    o S..  .   |
|=...   + o o.    |
|.o. . o o o..    |
|. .. ..o .. .o   |
|   ++... ..o. .  |
+----[SHA256]-----+

skyde@SEL MINGW64 ~
$
```
