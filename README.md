# gitcommands

Stephanies-MacBook-Pro:paulstephaudiocontrol stephaniegao$ git clone https://github.com/stephyli/customfadercontrol.git
Cloning into 'customfadercontrol'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
Checking connectivity... done.
Stephanies-MacBook-Pro:paulstephaudiocontrol stephaniegao$ cd customfadercontrol
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Stephanies-MacBook-Pro:paulstephaudiocontrol stephaniegao$ pwd
/Users/stephaniegao/paulstephaudiocontrol
Stephanies-MacBook-Pro:paulstephaudiocontrol stephaniegao$ mv customfadercontrol ..
Stephanies-MacBook-Pro:paulstephaudiocontrol stephaniegao$ cd ..
Stephanies-MacBook-Pro:~ stephaniegao$ ls
Applications		Movies			customfadercontrol.git
Desktop			Music			demo
Documents		Pictures		paulstephaudiocontrol
Downloads		Public			project1
Library			customfadercontrol
Stephanies-MacBook-Pro:~ stephaniegao$ rm -rf customfadercontrol.git
Stephanies-MacBook-Pro:~ stephaniegao$ ls
Applications		Movies			demo
Desktop			Music			paulstephaudiocontrol
Documents		Pictures		project1
Downloads		Public
Library			customfadercontrol
Stephanies-MacBook-Pro:~ stephaniegao$ cd customfadercontrol/
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ ls
README.md		customfaders.html
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ pwd
/Users/stephaniegao/customfadercontrol
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ ls
README.md		customfaders.html
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git pull 
Already up-to-date.
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git clone https://github.com/stephyli/randomdata.git
Cloning into 'randomdata'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ cd randomdata
Stephanies-MacBook-Pro:randomdata stephaniegao$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Stephanies-MacBook-Pro:randomdata stephaniegao$ pwd
/Users/stephaniegao/Desktop/customfadercontrol/randomdata
Stephanies-MacBook-Pro:randomdata stephaniegao$ cd ~/desktop
Stephanies-MacBook-Pro:desktop stephaniegao$ cd randomdata/
Stephanies-MacBook-Pro:randomdata stephaniegao$ git pull
remote: Counting objects: 2, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), done.
From https://github.com/stephyli/randomdata
   66bfecf..3c5f52a  master     -> origin/master
Updating 66bfecf..3c5f52a
Fast-forward
 randomdata.html | 47 +++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 47 insertions(+)
 create mode 100644 randomdata.html
Stephanies-MacBook-Pro:randomdata stephaniegao$ pwd
/Users/stephaniegao/desktop/randomdata
Stephanies-MacBook-Pro:randomdata stephaniegao$ cd customfadercontrol
-bash: cd: customfadercontrol: No such file or directory
Stephanies-MacBook-Pro:randomdata stephaniegao$ cd ~/desktop
Stephanies-MacBook-Pro:desktop stephaniegao$ cd customfadercontrol
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   customfaders.html

no changes added to commit (use "git add" and/or "git commit -a")
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git commit
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
	modified:   customfaders.html

no changes added to commit
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ gitadd
-bash: gitadd: command not found
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ gitadd.
-bash: gitadd.: command not found
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git add.
git: 'add.' is not a git command. See 'git --help'.

Did you mean this?
	add
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git add .
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git commit
Aborting commit due to empty commit message.
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git commit -m "test changes"
[master bd9aef9] test changes
 1 file changed, 2 insertions(+), 1 deletion(-)
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git push 
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 352 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
To https://github.com/stephyli/customfadercontrol.git
   11f6f25..bd9aef9  master -> master
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ git config --global push.default simple
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ pwd
/Users/stephaniegao/desktop/customfadercontrol
Stephanies-MacBook-Pro:customfadercontrol stephaniegao$ cd ~/desktop
Stephanies-MacBook-Pro:desktop stephaniegao$ cd randomdata
Stephanies-MacBook-Pro:randomdata stephaniegao$ gitadd .
-bash: gitadd: command not found
Stephanies-MacBook-Pro:randomdata stephaniegao$ git add .
Stephanies-MacBook-Pro:randomdata stephaniegao$ git commit -m"test changes"
[master 3fb9253] test changes
 1 file changed, 10 insertions(+), 10 deletions(-)
Stephanies-MacBook-Pro:randomdata stephaniegao$ git push
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 352 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
To https://github.com/stephyli/randomdata.git
   3c5f52a..3fb9253  master -> master
Stephanies-MacBook-Pro:randomdata stephaniegao$ 
