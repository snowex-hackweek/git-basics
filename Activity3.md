# Git branches: Activity 3

Let's make a merge conflict and fix it. Note, I am showing this using the `jupyterlab-git` GUI. This is a bit clunky in this GUI. Other GUIs are much better.

1. Switch to main. *make sure you have no changes staged or untracked*
2. Edit your file, save and commit the change.
3. Switch to your branch.
4. Make a change to your file **on the same line**, save and commit the change.
5. Merge main into your branch
    * Git > Merge Branch > select `main`
    * Oh no! Merge conflict!
6. In the Git tab, look for conflicted files, click on the little icon next to the conflicted files.
    * You will see a file with Online, Result, Incoming
    * 
Close the file in JupyterHub. Re-open and you'll see the merge conflict `>>>>>>>>>` lines.
7. Fix. Get rid of all that `>>>>>>` and `========` stuff.

Note is "following" behavior before committing on a branch is specific to Git on the JupyterHub. It is a setting in the Git config and you won't necessarily have this behavior when you use Git in other places. Note you can easily change this behavior by issuing a `git config` command.



