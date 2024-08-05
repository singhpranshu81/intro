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
$
