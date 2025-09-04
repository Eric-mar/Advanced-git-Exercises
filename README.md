# Advanced Git

## part 1
``` bash
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git log
commit 3f0f916342ab7795a33cf50f05e75484994f82f5 (HEAD -> main, origin/main, origin/HEAD)
Merge: 075bf15 10ead13
Author: tuyishime eric <erictuyishime2004@gmail.com>
Date:   Thu Sep 4 09:35:51 2025 +0200

    Merge branch 'main' of https://github.com/Eric-mar/Advanced-git-Exercises

commit 075bf158c9b176817ab33c011fbfab50f0f6ba83
Author: tuyishime eric <erictuyishime2004@gmail.com>
Date:   Thu Sep 4 09:29:23 2025 +0200

    adding new items

commit 10ead13c46d1831c2ac495d8ef55b3ca2101b3b8
Author: tuyishime eric <erictuyishime2004@gmail.com>
Date:   Wed Sep 3 13:13:31 2025 +0200

    chore: Create third and fourth files

commit 812e51d9e3a219b5fee4ba63cbc56e19ee916b8b
Author: tuyishime eric <erictuyishime2004@gmail.com>
Date:   Wed Sep 3 13:13:14 2025 +0200
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git pull main   
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git add test4,md

fatal: pathspec 'test4,md' did not match any files
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git commit -m "adding test4"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git push
Everything up-to-date
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test5.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git add .
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git commit -m "adding the test5.md"     
[main 76299e2] adding the test5.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test5.md
PS C:\Users\Cococe Ltd\Desktop\Advanced-git-Exercises> git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 238 bytes | 13.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Eric-mar/Advanced-git-Exercises.git
   3f0f916..76299e2  main -> main
```