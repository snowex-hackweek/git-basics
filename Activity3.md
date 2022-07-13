# Git branches: Activity 3

Let's make a merge conflict and fix it. Note, I am showing this using the `jupyterlab-git` GUI. This is a bit clunky in this GUI. Other GUIs are much better.

1. Switch to main. *make sure you have no changes staged or untracked*
2. Edit your file, save and commit the change.
3. Switch to your branch.
4. Make a change to your file **on the same line**, save and commit the change.
5. Merge main into your branch
    * Git > Merge Branch > select `main`
    * Oh no! Merge conflict!
6. In the Git tab, look for conflicted files, click on the little icon of a file with +/- next to the conflicted files.
    * You will see a file with Current, Result, Incoming
    * Work in the Result (middle) and fix up the file. When you are happy with the fixes, and you can fix however you want, click Resolved (upper right).
7. Commit the changes.
8. Switch back to main. If you want the branch changes from the branch into main, then do a merge.
    * Git > Merge Branch > select your branch
    
    
    
Note, if you don't want to use the `jupyterlab-git` merge conflict widget, then do the following.

* Open up the file with the merge conflicts
* You'll see `>>>>>>>>>` and `========`
* Get rid of all that and fix the file however you want. Just make sure there are no `>>>>>>>>` and `=========` stuff left.
* Get into the terminal and do `git add filemname`. Replace `filename` with the name of the conflicted file. So I would do `git add eli.md`
* Go back to Git tab and you'll see the staged files. Commit those.




