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

`ssh-keygen -t ed25519 -C "skyinnk.----@gmail.com"`

```bash
Microsoft Windows [Version 10.0.19044.2251]
(c) Microsoft Corporation. All rights reserved.

C:\Users\skyde>ssh-keygen -t ed25519 -C "skyinnk.----@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\skyde/.ssh/id_ed25519): C:\Users\skyde/.ssh/id_ed25519_<aliesname>
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\skyde/.ssh/id_ed25519_<aliesname>.
Your public key has been saved in C:\Users\skyde/.ssh/id_ed25519_<aliesname>.pub.
The key fingerprint is:
SHA256:NLANruQKLIHUcRwoRqcZMbxCLHBMpVs7q31SgJsTvvo skyinnk.sel@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|*O=+=o+          |
|+BB+.o =         |
|*o+.o o +        |
|ooo=.o . .       |
|+o.+=.  S        |
|..=. o.          |
|  .o..           |
|  .o. .          |
|.oE .o           |
+----[SHA256]-----+

C:\Users\skyde>

```
