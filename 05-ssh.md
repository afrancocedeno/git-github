> visit: [how to ssh with $ git](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

# LINUX:

Algorithm id:
4096
ed25519

```bash
ssh-keygen -t rsa -b <algorithm id> -C "email@mail.com"
```


```bash
eval "$(ssh-agent -s)"
```

# Add a new ssh to your github account

# install gh
>visit: [gh on linux](https://github.com/cli/cli/blob/trunk/docs/install_linux.md)
```bash
$ ssh-add ~/.ssh/id_rsa
```

```bash
$ gh ssh-key add key-file --title "personal laptop"
```

```bash
$ git remote set-url origin <repo-url>
```

```bash
$ git remote -v
```

## Testing your SSH connection


```bash
$ ssh -T git@github.com
:
> Are you sure you want to continue connecting (yes/no)?
```