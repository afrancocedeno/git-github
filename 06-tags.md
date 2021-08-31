# how to handle the version of a project in git

git log

git log --all

graph

decorate + one line
```bash
git log --all --graph --decorate --oneline
```

create a tag
```bash
git tag -a <tag name> -m "message id" <tag_id>
$ git tag -A version-0.1 -m "the commit change description" 1b56158
```

how to see wich commit correspond to a tag
```bash
git show-ref --tags
```
git push origin --tags
git tag -d <tag name>

## Does not being deleten by the host?
```bash
git push origin :refs/tags/foobranch-tag
```
