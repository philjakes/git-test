user@JAKESPRIME-01TP4HB MINGW64 ~ (master)
$ cd git-test

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ touch READ.md

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ ls
READ.md  git-test/

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git init
Initialized empty Git repository in C:/Users/user/git-test/.git/

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ ls -f
./  ../  .git/  git-test/  READ.md

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git config user.name "Phil Jakes"

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git config user.email "philjakes43@gmail.com"

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git config --list
diff.astextplain.textconv=astextplain
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
user.name=Phil Jakes
user.email=philjakes43@gmail.com

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git add READ.md

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git commit -m "Adding a readme file"
[master (root-commit) 74a3755] Adding a readme file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 READ.md

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git log
commit 74a37551af26045949a20d85b8b5dd6370f2f43c (HEAD -> master)
Author: Phil Jakes <philjakes43@gmail.com>
Date:   Tue Jun 15 16:35:12 2021 +0300

    Adding a readme file

user@JAKESPRIME-01TP4HB MINGW64 ~/git-test (master)
$ git log --oneline
74a3755 (HEAD -> master) Adding a readme file

