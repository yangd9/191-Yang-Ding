# 191-Yang-Ding

basic-commits

1. Use git status to see which branch you are on.
2. What does git log look like?
fatal: your current branch 'master' does not have any commits yet

3. Create a file
4. What does the output from git status look like now?
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	file.txt

nothing added to commit but untracked files present (use "git add" to track)

5. add the file to the staging area
6. How does git status look now?
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   file.txt

7. commit the file to the repository
8. How does git status look now?
On branch master
nothing to commit, working tree clean

9. Change the content of the file you created earlier
10. What does git status look like now?
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   file.txt

no changes added to commit (use "git add" and/or "git commit -a")

11. add the file change
12. What does git status look like now?
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   file.txt
  
13. Change the file again
14. Make a commit
15. What does the status look like now? The log?
On branch master
nothing to commit, working tree clean

commit 601fdc38fee045cf38736081520116298e46cecc (HEAD -> master)
Author: Yang Ding <yangd9@uci.edu>
Date:   Fri Jan 24 21:59:34 2020 -0800

    another commit

commit 5c48f88d7f801b05b4f9c6cd59f04f6a6c2de42b
Author: Yang Ding <yangd9@uci.edu>
Date:   Fri Jan 24 21:57:13 2020 -0800

    first commit
