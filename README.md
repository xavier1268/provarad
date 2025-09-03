
Aluno@LAB25-PC25 MINGW64 ~
$ mkdir NovaPasta1

Aluno@LAB25-PC25 MINGW64 ~
$ cd Nov
bash: cd: Nov: No such file or directory

Aluno@LAB25-PC25 MINGW64 ~
$ cd NovaPasta1/

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1
$ git init
Initialized empty Git repository in C:/Users/Aluno/NovaPasta1/.git/

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ ls -la
total 20
drwxr-xr-x 1 Aluno 197121 0 Sep  2 21:58 ./
drwxr-xr-x 1 Aluno 197121 0 Sep  2 21:34 ../
drwxr-xr-x 1 Aluno 197121 0 Sep  2 21:58 .git/

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ vim programa1.java

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git config user.name "alexandre"

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git config user.email "alexandre@exemplo.com"

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git add .
warning: in the working copy of 'programa1.java', LF will be replaced by CRLF the next time Git touches it

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   programa1.java


Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git commit -m "criei esta pasta"
[master (root-commit) b58cd35] criei esta pasta
 1 file changed, 1 insertion(+)
 create mode 100644 programa1.java

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (master)
$ git branch -m main

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (main)
$ git add remote origin https://github.com/xavier1268/aulaprovaa.git
fatal: pathspec 'remote' did not match any files

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (main)
$ git remote add origin https://github.com/xavier1268/aulaprovaa.git

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 234 bytes | 234.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xavier1268/aulaprovaa.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (main)
$ ^C

Aluno@LAB25-PC25 MINGW64 ~/NovaPasta1 (main)
$
