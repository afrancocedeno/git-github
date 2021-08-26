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
git add makes git track the file waiting for a commit

```bash
git add file_name
git commit -m "keword action | description "
```

#### copy from a previous version
root state
other change
