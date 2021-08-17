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

```bash
git add file_name
git commit -m "keword action | description "
```

```bash
$ git log file-name
commit cef2ea599779c4ab2d66c09946447dfdc2e3dc16 (HEAD -> master)
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Tue Aug 17 13:13:20 2021 -0500

    file create | first content

commit b104ea9169ae770c1a2d75d189acc8aaf0c439cc
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Tue Aug 17 13:12:16 2021 -0500

    file update | content added
```

```bash
git diff
```
#### usefull to compare staged with current working directory

```bash
$ git diff b104ea9169ae770c1a2d75d189acc8aaf0c439cc cef2ea599779c4ab2d66c09946447dfdc2e3dc16
diff --git a/README.md b/README.md
index dba62d9..1767b0b 100644
--- a/README.md
+++ b/README.md
@@ -3,10 +3,8 @@ repo to learn github
-remove/add new line
```

```bash
$ git-github > git show cef2ea599779c4ab2d66c09946447dfdc2e3dc16
commit cef2ea599779c4ab2d66c09946447dfdc2e3dc16 (HEAD -> master)
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Tue Aug 17 13:13:20 2021 -0500

    file create | first content

diff --git a/README.md b/README.md
index dba62d9..1767b0b 100644
--- a/README.md
+++ b/README.md
@@ -3,10 +3,8 @@ repo to learn github
-remove/add new line
```

#### copy from a previous version
