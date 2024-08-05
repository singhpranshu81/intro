# intro
Agile --  req gathering(user story) -> analysis --> design (Db-er diagram , app- uml(usecase diagram) -> implementation  
Junit(functional testing) --> QA & devops -->testing--> deployment --> maintanance




kickoff meet 
sprint call- updates daily


pranshu.singh@WKSCHE03TRNG015 MINGW64 ~
$ pwd
/c/Users/pranshu.singh

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~
$ ^C

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~
$ cd gitfolder/

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder
$ git init
Initialized empty Git repository in C:/Users/pranshu.singh/gitfolder/.git/

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git config --global user.name singhpranshu81

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git config --global user.name
singhpranshu81

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git config --global user.email thescholar02@gmail.com

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git config --global core.editor code

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git clone https://github.com/singhpranshu81/mpjava.git
Cloning into 'mpjava'...
warning: You appear to have cloned an empty repository.

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ echo Hi>file.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file.txt
        mpjava/

nothing added to commit but untracked files present (use "git add" to track)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git add file.txt
warning: in the working copy of 'file.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   file.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        mpjava/


pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git add .
error: 'mpjava/' does not have a commit checked out
fatal: adding files failed

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git commit -m "my first commit"
[master (root-commit) f4fe947] my first commit
 1 file changed, 1 insertion(+)
 create mode 100644 file.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        mpjava/

nothing added to commit but untracked files present (use "git add" to track)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder (master)
$ cd mpjava

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ echo Hello>file1.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git satus
git: 'satus' is not a git command. See 'git --help'.

The most similar command is
        status

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.txt

nothing added to commit but untracked files present (use "git add" to track)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'file1.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "first commit"
[main (root-commit) 135f528] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 file1.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ code

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add file1.txt
warning: in the working copy of 'file1.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "added eve"
[main 12f9891] added eve
 1 file changed, 1 insertion(+), 1 deletion(-)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ echo heeljhffj raja>file2.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file2.txt

nothing added to commit but untracked files present (use "git add" to track)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'file2.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "more file added"
[main 3a6b73e] more file added
 1 file changed, 1 insertion(+)
 create mode 100644 file2.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    file1.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hguhf.txt

no changes added to commit (use "git add" and/or "git commit -a")

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'hguhf.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "fns"
[main 9496082] fns
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename file1.txt => hguhf.txt (100%)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ ^C

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    hguhf.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        f1.txt

no changes added to commit (use "git add" and/or "git commit -a")

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add f1.txt
warning: in the working copy of 'f1.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "modifies"
\[main ae550f1] modifies
 1 file changed, 1 insertion(+)
 create mode 100644 f1.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ \git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    hguhf.txt

no changes added to commit (use "git add" and/or "git commit -a")

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add hguhf.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "bfd"
[main bc23abb] bfd
 1 file changed, 1 deletion(-)
 delete mode 100644 hguhf.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ rm f1.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    f1.txt

no changes added to commit (use "git add" and/or "git commit -a")

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "bd"
[main 3f29151] bd
 1 file changed, 1 deletion(-)
 delete mode 100644 f1.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git echo cdcd>fr.txt
git: 'echo' is not a git command. See 'git --help'.

The most similar command is
        fetch

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "fnj"
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fr.txt

nothing added to commit but untracked files present (use "git add" to track)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "d"
[main 8e15a27] d
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fr.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git mv fr.txt file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    fr.txt -> file22.txt


pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "jfdfjd"
[main 61bd1a9] jfdfjd
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename fr.txt => file22.txt (100%)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 872 bytes | 13.00 KiB/s, done.
From https://github.com/singhpranshu81/mpjava
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git merge
fatal: refusing to merge unrelated histories

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch and 'origin/main' have diverged,
and have 9 and 1 different commits each, respectively.
  (use "git pull" if you want to integrate the remote branch with yours)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log
commit 61bd1a93a4e451d36341525caccee05107e9a7f7 (HEAD -> main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:07:28 2024 +0530

    jfdfjd

commit 8e15a272d3e00a7beeca9f0986e42365bdf11b7f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:06:27 2024 +0530

    d

commit 3f29151f3c3e69a69cbf80602527a74ac3a0385d
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:52:55 2024 +0530

    bd

commit bc23abb255f9dfbd4a487cfcb08a97ef830154a5
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:48:36 2024 +0530

    bfd

commit ae550f140b03b00b667b797f055dde576774444f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:47:09 2024 +0530

    modifies

commit 9496082d866d1f63a827aebadac5fd84f7c91d39
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:40:28 2024 +0530

    fns

commit 3a6b73ef42be59be85c01f1b62f16b71dfeb5755
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:36:13 2024 +0530

    more file added

commit 12f9891f7dc028cb71a4d3283bb8d2eff2a5280b
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:32:26 2024 +0530

    added eve

commit 135f52864327e62eeb0b37893da4c5424e22dada
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 11:48:00 2024 +0530

    first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --oneLine
fatal: unrecognized argument: --oneLine

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --one Line
fatal: ambiguous argument 'Line': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --oneline
61bd1a9 (HEAD -> main) jfdfjd
8e15a27 d
3f29151 bd
bc23abb bfd
ae550f1 modifies
9496082 fns
3a6b73e more file added
12f9891 added eve
135f528 first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log -p
commit 61bd1a93a4e451d36341525caccee05107e9a7f7 (HEAD -> main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:07:28 2024 +0530

    jfdfjd

diff --git a/fr.txt b/file22.txt
similarity index 100%
rename from fr.txt
rename to file22.txt

commit 8e15a272d3e00a7beeca9f0986e42365bdf11b7f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:06:27 2024 +0530

    d

diff --git a/fr.txt b/fr.txt
new file mode 100644
index 0000000..e69de29

commit 3f29151f3c3e69a69cbf80602527a74ac3a0385d
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:52:55 2024 +0530

    bd

diff --git a/f1.txt b/f1.txt
deleted file mode 100644
index 97a3fd4..0000000
--- a/f1.txt
+++ /dev/null
@@ -1 +0,0 @@
-Hello  Pranshu

commit bc23abb255f9dfbd4a487cfcb08a97ef830154a5
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:48:36 2024 +0530

    bfd

diff --git a/hguhf.txt b/hguhf.txt
deleted file mode 100644
index 97a3fd4..0000000
--- a/hguhf.txt
+++ /dev/null
@@ -1 +0,0 @@
-Hello  Pranshu

commit ae550f140b03b00b667b797f055dde576774444f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:47:09 2024 +0530

    modifies

diff --git a/f1.txt b/f1.txt
new file mode 100644
index 0000000..97a3fd4
--- /dev/null
+++ b/f1.txt
@@ -0,0 +1 @@
+Hello  Pranshu

commit 9496082d866d1f63a827aebadac5fd84f7c91d39
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:40:28 2024 +0530

    fns

diff --git a/file1.txt b/hguhf.txt
similarity index 100%
rename from file1.txt
rename to hguhf.txt

commit 3a6b73ef42be59be85c01f1b62f16b71dfeb5755
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:36:13 2024 +0530

    more file added

diff --git a/file2.txt b/file2.txt
new file mode 100644
index 0000000..541d470
--- /dev/null
+++ b/file2.txt
@@ -0,0 +1 @@
+heeljhffj raja

commit 12f9891f7dc028cb71a4d3283bb8d2eff2a5280b
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:32:26 2024 +0530

    added eve

diff --git a/file1.txt b/file1.txt
index e965047..97a3fd4 100644
--- a/file1.txt
+++ b/file1.txt
@@ -1 +1 @@
-Hello
+Hello  Pranshu

commit 135f52864327e62eeb0b37893da4c5424e22dada
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 11:48:00 2024 +0530

    first commit

diff --git a/file1.txt b/file1.txt
new file mode 100644
index 0000000..e965047
--- /dev/null
+++ b/file1.txt
@@ -0,0 +1 @@
+Hello

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git pull --allow-unrelated-histories
Merge made by the 'ort' strategy.
 README.md | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --author=thescholar02@gmail.com
commit bea29d5450da18f2f15e0914bafb288e3a592fdb (HEAD -> main)
Merge: 61bd1a9 cd3bf38
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:47:50 2024 +0530

    Merge branch 'main' of https://github.com/singhpranshu81/mpjava

commit cd3bf38c39cb758eca40082c6003336e1e173a48 (origin/main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:24:15 2024 +0530

    Create README.md

commit 61bd1a93a4e451d36341525caccee05107e9a7f7
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:07:28 2024 +0530

    jfdfjd

commit 8e15a272d3e00a7beeca9f0986e42365bdf11b7f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:06:27 2024 +0530

    d

commit 3f29151f3c3e69a69cbf80602527a74ac3a0385d
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:52:55 2024 +0530

    bd

commit bc23abb255f9dfbd4a487cfcb08a97ef830154a5
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:48:36 2024 +0530

    bfd

commit ae550f140b03b00b667b797f055dde576774444f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:47:09 2024 +0530

    modifies

commit 9496082d866d1f63a827aebadac5fd84f7c91d39
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:40:28 2024 +0530

    fns

commit 3a6b73ef42be59be85c01f1b62f16b71dfeb5755
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:36:13 2024 +0530

    more file added

commit 12f9891f7dc028cb71a4d3283bb8d2eff2a5280b
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:32:26 2024 +0530

    added eve

commit 135f52864327e62eeb0b37893da4c5424e22dada
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 11:48:00 2024 +0530

    first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --reverse
commit 135f52864327e62eeb0b37893da4c5424e22dada
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 11:48:00 2024 +0530

    first commit

commit 12f9891f7dc028cb71a4d3283bb8d2eff2a5280b
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:32:26 2024 +0530

    added eve

commit 3a6b73ef42be59be85c01f1b62f16b71dfeb5755
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:36:13 2024 +0530

    more file added

commit 9496082d866d1f63a827aebadac5fd84f7c91d39
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:40:28 2024 +0530

    fns

commit ae550f140b03b00b667b797f055dde576774444f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:47:09 2024 +0530

    modifies

commit bc23abb255f9dfbd4a487cfcb08a97ef830154a5
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:48:36 2024 +0530

    bfd

commit 3f29151f3c3e69a69cbf80602527a74ac3a0385d
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:52:55 2024 +0530

    bd

commit 8e15a272d3e00a7beeca9f0986e42365bdf11b7f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:06:27 2024 +0530

    d

commit 61bd1a93a4e451d36341525caccee05107e9a7f7
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:07:28 2024 +0530

    jfdfjd

commit cd3bf38c39cb758eca40082c6003336e1e173a48 (origin/main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:24:15 2024 +0530

    Create README.md

commit bea29d5450da18f2f15e0914bafb288e3a592fdb (HEAD -> main)
Merge: 61bd1a9 cd3bf38
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:47:50 2024 +0530

    Merge branch 'main' of https://github.com/singhpranshu81/mpjava

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git branch ps_branch

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git branch psttt_branch

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git branch -l
* main
  ps_branch
  psttt_branch

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git checkout ps_branch
Switched to branch 'ps_branch'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git checkout psttt_branch
Switched to branch 'psttt_branch'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git branch -l
  main
  ps_branch
* psttt_branch

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 10 commits.
  (use "git push" to publish your local commits)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ ls
README.md  file2.txt  file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git ls-files
README.md
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git checkout ps_branch
Switched to branch 'ps_branch'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ echo from ps_branch>f3.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git ls-files
README.md
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ ls
README.md  f3.txt  file2.txt  file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git add .
warning: in the working copy of 'f3.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git commit -m "adding branch"
[ps_branch 03b23d8] adding branch
 1 file changed, 1 insertion(+)
 create mode 100644 f3.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git status
On branch ps_branch
nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git ls-files
README.md
f3.txt
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (ps_branch)
$ git checkout psttt_branch
Switched to branch 'psttt_branch'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git ls-files
README.md
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 10 commits.
  (use "git push" to publish your local commits)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git ls-files
README.md
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git merge ps_branch
Updating bea29d5..03b23d8
Fast-forward
 f3.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 f3.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git ls-files
README.md
f3.txt
file2.txt
file22.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git branch -a
* main
  ps_branch
  psttt_branch
  remotes/origin/main

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ echo fdf>f.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ echo df>g.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'f.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'g.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "added two files"
[main a3826b4] added two files
 2 files changed, 2 insertions(+)
 create mode 100644 f.txt
 create mode 100644 g.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 12 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ vim f.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'f.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "updated"
[main 464ac68] updated
 1 file changed, 1 insertion(+), 1 deletion(-)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ vim g.txt i
2 files to edit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git add .
warning: in the working copy of 'g.txt', LF will be replaced by CRLF the next time Git touches it

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git commit -m "updatedd"
[main 09fe11e] updatedd
 1 file changed, 1 insertion(+), 1 deletion(-)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --oneline
09fe11e (HEAD -> main) updatedd
464ac68 updated
a3826b4 added two files
03b23d8 (ps_branch) adding branch
bea29d5 (psttt_branch) Merge branch 'main' of https://github.com/singhpranshu81/mpjava
cd3bf38 (origin/main) Create README.md
61bd1a9 jfdfjd
8e15a27 d
3f29151 bd
bc23abb bfd
ae550f1 modifies
9496082 fns
3a6b73e more file added
12f9891 added eve
135f528 first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log HEAD
commit 09fe11e3ddc1b29cbf616142d65e1936783517eb (HEAD -> main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:57:59 2024 +0530

    updatedd

commit 464ac68ffe3b2743447b5ae78f064815f97996ac
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:56:52 2024 +0530

    updated

commit a3826b429e5749bd8cede166f2eaa5f677bb5855
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:52:37 2024 +0530

    added two files

commit 03b23d80bf7be0310d2cc84c80cba4b1e0d4288d (ps_branch)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:05:41 2024 +0530

    adding branch

commit bea29d5450da18f2f15e0914bafb288e3a592fdb (psttt_branch)
Merge: 61bd1a9 cd3bf38
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:47:50 2024 +0530

    Merge branch 'main' of https://github.com/singhpranshu81/mpjava

commit cd3bf38c39cb758eca40082c6003336e1e173a48 (origin/main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:24:15 2024 +0530

    Create README.md

commit 61bd1a93a4e451d36341525caccee05107e9a7f7
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:07:28 2024 +0530

    jfdfjd

commit 8e15a272d3e00a7beeca9f0986e42365bdf11b7f
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 14:06:27 2024 +0530

    d

commit 3f29151f3c3e69a69cbf80602527a74ac3a0385d
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:52:55 2024 +0530

    bd

commit bc23abb255f9dfbd4a487cfcb08a97ef830154a5
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 13:48:36 2024 +0530


pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git show HEAD~1
commit 464ac68ffe3b2743447b5ae78f064815f97996ac
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:56:52 2024 +0530

    updated

diff --git a/f.txt b/f.txt
index a1a7b99..cda59ea 100644
--- a/f.txt
+++ b/f.txt
@@ -1 +1 @@
-fdf
+bdjbkjbk jd jkdj kckkjkkkckkjckjckckckckjckjckjckcv jkkkccccj fdf

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git reset -hard HEAD~1
error: did you mean `--hard` (with two dashes)?

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git reset --hard HEAD~1
HEAD is now at 464ac68 updated

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --oneline
464ac68 (HEAD -> main) updated
a3826b4 added two files
03b23d8 (ps_branch) adding branch
bea29d5 (psttt_branch) Merge branch 'main' of https://github.com/singhpranshu81/mpjava
cd3bf38 (origin/main) Create README.md
61bd1a9 jfdfjd
8e15a27 d
3f29151 bd
bc23abb bfd
ae550f1 modifies
9496082 fns
3a6b73e more file added
12f9891 added eve
135f528 first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git checkout psttt_branch
Switched to branch 'psttt_branch'

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ touch two.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git add .

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git commit -m "crreated two from psttt branch"
[psttt_branch 0129330] crreated two from psttt branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 two.txt

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git log --oneline
0129330 (HEAD -> psttt_branch) crreated two from psttt branch
bea29d5 Merge branch 'main' of https://github.com/singhpranshu81/mpjava
cd3bf38 (origin/main) Create README.md
61bd1a9 jfdfjd
8e15a27 d
3f29151 bd
bc23abb bfd
ae550f1 modifies
9496082 fns
3a6b73e more file added
12f9891 added eve
135f528 first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (psttt_branch)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 13 commits.
  (use "git push" to publish your local commits)

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git rebase psttt_branch
Successfully rebased and updated refs/heads/main.

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log --oneline
9e12323 (HEAD -> main) updated
765b2f9 added two files
b89339d adding branch
0129330 (psttt_branch) crreated two from psttt branch
bea29d5 Merge branch 'main' of https://github.com/singhpranshu81/mpjava
cd3bf38 (origin/main) Create README.md
61bd1a9 jfdfjd
8e15a27 d
3f29151 bd
bc23abb bfd
ae550f1 modifies
9496082 fns
3a6b73e more file added
12f9891 added eve
135f528 first commit

pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)
$ git log -p
commit 9e12323858116e711e79e8b5c52c6cfde43d9db4 (HEAD -> main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:56:52 2024 +0530

    updated

diff --git a/f.txt b/f.txt
index a1a7b99..cda59ea 100644
--- a/f.txt
+++ b/f.txt
@@ -1 +1 @@
-fdf
+bdjbkjbk jd jkdj kckkjkkkckkjckjckckckckjckjckjckcv jkkkccccj fdf

commit 765b2f93cf7557fe2eda49a8ccf9670643ae982c
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:52:37 2024 +0530

    added two files

diff --git a/f.txt b/f.txt
new file mode 100644
index 0000000..a1a7b99
--- /dev/null
+++ b/f.txt
@@ -0,0 +1 @@
+fdf
diff --git a/g.txt b/g.txt
new file mode 100644
index 0000000..781e137
--- /dev/null
+++ b/g.txt
@@ -0,0 +1 @@
+df

commit b89339d9d564f823e8727f99d8c704a253bad772
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:05:41 2024 +0530

    adding branch

diff --git a/f3.txt b/f3.txt
new file mode 100644
index 0000000..25f792a
--- /dev/null
+++ b/f3.txt
@@ -0,0 +1 @@
+from ps_branch

commit 0129330b422482e8e6b4bea1e160a70111933fe0 (psttt_branch)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 17:34:39 2024 +0530

    crreated two from psttt branch

diff --git a/two.txt b/two.txt
new file mode 100644
index 0000000..e69de29
:
commit 9e12323858116e711e79e8b5c52c6cfde43d9db4 (HEAD -> main)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:56:52 2024 +0530

    updated

diff --git a/f.txt b/f.txt
index a1a7b99..cda59ea 100644
--- a/f.txt
+++ b/f.txt
@@ -1 +1 @@
-fdf
+bdjbkjbk jd jkdj kckkjkkkckkjckjckckckckjckjckjckcv jkkkccccj fdf

commit 765b2f93cf7557fe2eda49a8ccf9670643ae982c
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:52:37 2024 +0530

    added two files

diff --git a/f.txt b/f.txt
new file mode 100644
index 0000000..a1a7b99
--- /dev/null
+++ b/f.txt
@@ -0,0 +1 @@
+fdf
diff --git a/g.txt b/g.txt
new file mode 100644
index 0000000..781e137
--- /dev/null
+++ b/g.txt
@@ -0,0 +1 @@
+df

commit b89339d9d564f823e8727f99d8c704a253bad772
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 16:05:41 2024 +0530

    adding branch

diff --git a/f3.txt b/f3.txt
new file mode 100644
index 0000000..25f792a
--- /dev/null
+++ b/f3.txt
@@ -0,0 +1 @@
+from ps_branch

commit 0129330b422482e8e6b4bea1e160a70111933fe0 (psttt_branch)
Author: singhpranshu81 <thescholar02@gmail.com>
Date:   Mon Aug 5 17:34:39 2024 +0530

    crreated two from psttt branch

diff --git a/two.txt b/two.txt
new file mode 100644
index 0000000..e69de29


pranshu.singh@WKSCHE03TRNG015 MINGW64 ~/gitfolder/mpjava (main)

