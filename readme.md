#TESTING LOCAL BRANCH CLEANUP

Test different behaviours of `git branch --merged | grep -v \* | xargs git branch -D`

Make sure it only deletes local branch, not active remote ones
