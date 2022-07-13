# Tips for working with branches

## The very most important thing when working with branches

1. **Always know what branch you are on**
2. Use `git status` a lot.
3. In on the JupyterHub, click on the Git tab (to left) and look at Current Branch

## More tips

3. Commit changes before switching branches. Or set up Git to not move your changes with you when you switch branches.
4. In the JupyterHub, close files before switching branches.
5. Keep your branch synced with main. Don't let things get too out of sync.
6. Short work iterations work best. Do work in branch, merge into main (or dev branch), work in branch, merge. Once your branch starts diverging far from main, life gets harder.
7. Git will not delete your files unless you do `git reset --hard`. If you (because you were poking around on stackoverflow) think `git reset` is the only way out, stop and take a break. Come back and try
    * Try `git status`. Where are you in your repo? Read the suggestions that it gives. Often it'll give you a hint of how to get out of your predicament.
    * Try `git log`. What has been committed to your repo?
    * Try `git reflog`. Get out of it with `q`. This gives you a really detailed view of the repo activity.
    * What were you doing right before you got stuck?