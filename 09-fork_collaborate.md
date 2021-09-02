
# pull request
compare branches

como mantener mi rama fork conectada con la del autor?
con remote upstream and origin handle video 25
* original va cambiando, el fork se va quedando atras
```bash
$ # fredy
$ git pull origin master
$ # make some changes in the leader repo

$ # anita (otra fuente para hacer pull)
$ git remote - v
> origin https:...anita/... (...)
$ # branch than bring original repo not fork
$ git remote add <keyword different from origin> https:...freddy/... (...)
$ git remote -v
> origin anita
> upstream fredy
```
```bash
# bring remote
git pull upstream master
# fusion fork
git push origin master
```
