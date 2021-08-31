## Warm up
```bash
$ git init
$ touch file.txt
$ git add file.txt
$ # or git add .
$ git commit -m "foo bar"
$ git status
$ git commit -m "version update | first commit and file create"
$ git show
$ # or git show --stat
$ git log
$ # or git log --all --graph --decorate --oneline
```
___
## config
```bash
$ git-github > git config
usage: git config [<options>]

Config file location
    --global              use global config file
:
```
```bash
$ git-github > git config --global user.name "Alejandro Franco Cedeño"
```
```bash
$ git-github > git config --global user.email "afrancocedeno@gmail.com"
```

```bash
$ git-github > git config --list
user.email=afrancocedeno@gmail.com
user.name=Alejandro Franco Cedeño
:
```

```bash
$ git-github > git config --list --show-origin
file:/home/afrancocedeno/.gitconfig     user.email=afrancocedeno@gmail.com
file:/home/afrancocedeno/.gitconfig     user.name=Alejandro Franco Cedeño
:
```
___
# add
git add makes git track the file waiting for a commit

```bash
git add file_name
git commit -m "keword action | description "
```

#### copy from a previous version
root state
other change
