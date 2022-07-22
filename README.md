# git_training_repo


RBhavsar3@SLB-4QXQLN3 MINGW64 ~
$

RBhavsar3@SLB-4QXQLN3 MINGW64 ~
$ git --version
git version 2.37.1.windows.1

RBhavsar3@SLB-4QXQLN3 MINGW64 ~
$ ped
bash: ped: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~
$ pwd
/c/Users/Rbhavsar3

RBhavsar3@SLB-4QXQLN3 MINGW64 ~
$ cd desktop

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop
$ pwd
/c/Users/Rbhavsar3/desktop

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop
$ mkdir project

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop
$ cd project

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project
$ pwd
/c/Users/Rbhavsar3/desktop/project

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project
$ lc
bash: lc: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project
$ ls

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project
$ get init
bash: get: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project
$ git init
Initialized empty Git repository in C:/Users/Rbhavsar3/Desktop/project/.git/

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ mv project project_git
mv: cannot stat 'project': No such file or directory

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ cd..
bash: cd..: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ pwd
/c/Users/Rbhavsar3/desktop/project

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ ls -l
total 0

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ la -la
bash: la: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git init
Reinitialized existing Git repository in C:/Users/Rbhavsar3/Desktop/project/.git/

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ la -la
bash: la: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ ls -la
total 4
drwxr-xr-x 1 RBhavsar3 1049089 0 Jul 22 10:01 ./
drwxr-xr-x 1 RBhavsar3 1049089 0 Jul 22 10:01 ../
drwxr-xr-x 1 RBhavsar3 1049089 0 Jul 22 10:05 .git/

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ touch file1.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ ls
file1.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ touch hello.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ ls
file1.java  hello.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ vi file1.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ vi hello.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ cat file1.java
public class MyFirstJavaProgram {

   /* This is my first java program.
    * This will print 'Hello World' as the output
    */

   public static void main(String []args) {
      System.out.println("Hello World"); // prints Hello World
   }
}

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ vi file1.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ cat file1.java
public class MyFirstJavaProgram {

   /* This is my first java program.
    * This will print 'Hello World' as the output
    */

   public static void main(String []args) {
      System.out.println("Hello World"); // prints Hello World
   }
}

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ vi file2.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git commit -m "initial code"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.java
        file2.java
        hello.java

nothing added to commit but untracked files present (use "git add" to track)

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.java
        file2.java
        hello.java

nothing added to commit but untracked files present (use "git add" to track)

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git add .
warning: in the working copy of 'file1.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'file2.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'hello.java', LF will be replaced by CRLF the next time Git touches it

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git commit -m "initial code"
[master (root-commit) 3334ccf] initial code
 Committer: Riya Bhavsar <RBhavsar3@slb.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 3 files changed, 28 insertions(+)
 create mode 100644 file1.java
 create mode 100644 file2.java
 create mode 100644 hello.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git status
On branch master
nothing to commit, working tree clean

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ rm firle1.java
rm: cannot remove 'firle1.java': No such file or directory

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ rm file.java
rm: cannot remove 'file.java': No such file or directory

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ rm file1.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ ls
file2.java  hello.java

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git checkout file1.java
Updated 1 path from the index

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ get init
bash: get: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git init
Reinitialized existing Git repository in C:/Users/Rbhavsar3/Desktop/project/.git/

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ goit commit -m "first commit"
bash: goit: command not found

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git commit -m "first commit"
On branch master
nothing to commit, working tree clean

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (master)
$ git branch -M "main"

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$ git remote add origin https://github.com/ray17062000/git_training_repo.git

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$ git push -u origin "main"
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 627 bytes | 627.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/ray17062000/git_training_repo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$ git push -u origin "main"
Everything up-to-date
branch 'main' set up to track 'origin/main'.

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$ git log
commit 3334ccf663e175486947903376402cdca48dbdd1 (HEAD -> main, origin/main)
Author: Riya Bhavsar <RBhavsar3@slb.com>
Date:   Fri Jul 22 10:15:11 2022 +0530

    initial code

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$ ^C

RBhavsar3@SLB-4QXQLN3 MINGW64 ~/desktop/project (main)
$
