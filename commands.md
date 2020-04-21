## Git commands
```
git clone ....

git checkout master / git co
git status / git st
git add . 
git commit -m 'sessage' / git ci ..
git tree
git log
git checkout -b new-branch / git co -b create and checkout
git branch new-branch /only create
git merge new-branch / merge to head
git reset  243dd4g3 / undo commit.. 

git push / pushing to github
git fetch / checking whats on github
git pull / checking and downloading changes from github

```
------

## Git config
Add the following to a file called `~/.gitconfig`

```
[alias]
	st = status
	ci = commit
	co = checkout
	br = branch
	tree = log --oneline --decorate --graph --color
	amend = commit --amend -C HEAD
	pop = stash pop

```

## Terminal commands

```
$ ls 		#list files
$ ls -a 	#list also hidden files
$ ls -l 	#list data about files
$ cd my-dir	#change directory
$ cd - 		#change back to previous directory
$ cat my-file.txt # print file to terminal
$ pwd		#print working directory
$ touch my-file #creates an empty file

```
