merge (working dir) +  fetch (local repo) = git pull

git push

git clone

commit -am includes git add to already created files
git commit -am "foo | bar"

** this change is in main branch
git branch new_branch_name

git checkout new_branch_name

** this change is in foobranch branch

after commit changes inside the branch then:

```bash
git merge foobranch
```

```bash
$ git log 03-branches.md
commit 997f96490bccbb121a83b4ea4abc94ae7980e2b2 (HEAD -> main)
Merge: 9b57697 e0b8291
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:40:17 2021 -0500

    My first merge with solved conflict | Merge branch 'foobranch' into main

commit 9b5769799e5f4e9a64f538d39be6355f0065ee4b
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:35:50 2021 -0500

commit 997f96490bccbb121a83b4ea4abc94ae7980e2b2 (HEAD -> main)
Merge: 9b57697 e0b8291
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:40:17 2021 -0500

    My first merge with solved conflict | Merge branch 'foobranch' into main

commit 9b5769799e5f4e9a64f538d39be6355f0065ee4b
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:35:50 2021 -0500

    file update | commit from main

commit e0b82916a94669fd38816705f2f12773aca5c35d (foobranch)
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
:...skipping...
commit 997f96490bccbb121a83b4ea4abc94ae7980e2b2 (HEAD -> main)
Merge: 9b57697 e0b8291
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:40:17 2021 -0500

    My first merge with solved conflict | Merge branch 'foobranch' into main

commit 9b5769799e5f4e9a64f538d39be6355f0065ee4b
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:35:50 2021 -0500

    file update | commit from main

commit e0b82916a94669fd38816705f2f12773aca5c35d (foobranch)
Author: Alejandro Franco Cedeño <afrancocedeno@gmail.com>
Date:   Thu Aug 26 16:05:59 2021 -0500

    file update | inside foobranch

commit 0a2643fab2a906ea19d2dd8647d1e206e82ebb3e (origin/main)
:
```