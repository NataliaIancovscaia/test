
nirut@LAPTOP-30KNAH0B MINGW64 ~
$ cd C:

nirut@LAPTOP-30KNAH0B MINGW64 /c
$ cd git
bash: cd: git: No such file or directory

nirut@LAPTOP-30KNAH0B MINGW64 /c
$ cd users

nirut@LAPTOP-30KNAH0B MINGW64 /c/users
$ cd nirut

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd git
bash: cd: git: No such file or directory

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd github

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ git clone https://github.com/drblue/fed24-javascript-1.git
Cloning into 'fed24-javascript-1'...
remote: Enumerating objects: 149, done.
remote: Counting objects: 100% (149/149), done.
remote: Compressing objects: 100% (130/130), done.
remote: Total 149 (delta 62), reused 106 (delta 19), pack-reused 0 (from 0)
Receiving objects: 100% (149/149), 47.72 KiB | 3.41 MiB/s, done.
Resolving deltas: 100% (62/62), done.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ https://github.com/drblue/fed24-javascript-1.git .
bash: https://github.com/drblue/fed24-javascript-1.git: No such file or directory

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ git clone https://github.com/drblue/fed24-javascript-1.git .
fatal: destination path '.' already exists and is not an empty directory.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ git clone  https://github.com/drblue/fed24-javascript-1.git.
fatal: could not create work tree dir 'fed24-javascript-1.git.': Invalid argument

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ cd..
bash: cd..: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/github
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git clone https://github.com/drblue/fed24-javascript-1.git git
Cloning into 'git'...
remote: Enumerating objects: 149, done.
remote: Counting objects: 100% (149/149), done.
remote: Compressing objects: 100% (130/130), done.
remote: Total 149 (delta 62), reused 106 (delta 19), pack-reused 0 (from 0)
Receiving objects: 100% (149/149), 47.72 KiB | 137.00 KiB/s, done.
Resolving deltas: 100% (62/62), done.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd git

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/git (main)
$ git clone git@github.com:NataliaIancovscaia/fed24-myfirstrepo.git
Cloning into 'fed24-myfirstrepo'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/git (main)
$ cd..
bash: cd..: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/git (main)
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git clone git@github.com:NataliaIancovscaia/fed24-myfirstrepo.git git
Cloning into 'git'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd git
bash: cd: git: No such file or directory

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git clone https://github.com/NataliaIancovscaia/fed24-myfirstrepo.git git
Cloning into 'git'...
warning: You appear to have cloned an empty repository.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git clone https://github.com/NataliaIancovscaia/fed24-myfirstrepo.git
fatal: destination path 'fed24-myfirstrepo' already exists and is not an empty directory.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd..
bash: cd..: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users
$ git clone https://github.com/NataliaIancovscaia/fed24-myfirstrepo.git
fatal: could not create work tree dir 'fed24-myfirstrepo': Permission denied

nirut@LAPTOP-30KNAH0B MINGW64 /c/users
$ cd nirut

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git clone https://github.com/NataliaIancovscaia/test.git
Cloning into 'test'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd test

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ git status
fatal: not a git repository (or any of the parent directories): .git

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd test

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git add ^C

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git add  README.md

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git commit -m "test read"
[main 31006f9] test read
 1 file changed, 1 insertion(+), 1 deletion(-)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git add .

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git commit -m "second"
[main 728c9ee] second
 1 file changed, 4 insertions(+), 1 deletion(-)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 504 bytes | 252.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NataliaIancovscaia/test.git
   987ac1f..728c9ee  main -> main

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd fed24-myfirstrepo

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index/index.html
        modified:   index/work.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index/11.js

no changes added to commit (use "git add" and/or "git commit -a")

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ git add .

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index/11.js
        modified:   index/index.html
        modified:   index/work.js


nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ git commit -m "change"
[main 005f06f] change
 3 files changed, 117 insertions(+), 2 deletions(-)
 create mode 100644 index/11.js

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ git push
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 8 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (19/19), 4.80 KiB | 1.20 MiB/s, done.
Total 19 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/NataliaIancovscaia/fed24-myfirstrepo.git
 * [new branch]      main -> main

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ cd..
bash: cd..: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/fed24-myfirstrepo (main)
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd new folder
bash: cd: too many arguments

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd New folder
bash: cd: too many arguments

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd Newfolder

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder
$ git status
fatal: not a git repository (or any of the parent directories): .git

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder
$ touch test.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder
$ git init
Initialized empty Git repository in C:/Users/nirut/Newfolder/.git/

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.txt

nothing added to commit but untracked files present (use "git add" to track)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git add .

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   test.txt


nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git commit -m"he"
[master (root-commit) 2cc52f9] he
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ ls-la
bash: ls-la: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ ls -la
total 16
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:34 ./
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:27 ../
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:36 .git/
-rw-r--r-- 1 nirut 197609 0 Oct 29 23:30 test.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote -v

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote add original https://github.com/NataliaIancovscaia/newfolder.git

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote -v
original        https://github.com/NataliaIancovscaia/newfolder.git (fetch)
original        https://github.com/NataliaIancovscaia/newfolder.git (push)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git push original master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 218 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NataliaIancovscaia/newfolder.git
 * [new branch]      master -> master

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote add duplicated https://github.com/NataliaIancovscaia/lesson2.git

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote -v
duplicated      https://github.com/NataliaIancovscaia/lesson2.git (fetch)
duplicated      https://github.com/NataliaIancovscaia/lesson2.git (push)
original        https://github.com/NataliaIancovscaia/newfolder.git (fetch)
original        https://github.com/NataliaIancovscaia/newfolder.git (push)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ touch  test1.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git add .

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git commit -m "file"
[master 376402c] file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test1.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ ls -la
total 16
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:51 ./
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:27 ../
drwxr-xr-x 1 nirut 197609 0 Oct 29 23:52 .git/
-rw-r--r-- 1 nirut 197609 0 Oct 29 23:30 test.txt
-rw-r--r-- 1 nirut 197609 0 Oct 29 23:51 test1.txt

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git push duplicated
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 389 bytes | 194.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/NataliaIancovscaia/lesson2.git
 * [new branch]      master -> master

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote remove duplicated

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git.remote -v
bash: git.remote: command not found

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ git remote -v
original        https://github.com/NataliaIancovscaia/newfolder.git (fetch)
original        https://github.com/NataliaIancovscaia/newfolder.git (push)

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/Newfolder (master)
$ cd ..

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut
$ cd test

nirut@LAPTOP-30KNAH0B MINGW64 /c/users/nirut/test (main)
