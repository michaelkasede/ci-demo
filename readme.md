# Resolve divergent branches issues

- You have divergent branches and need to specify how to reconcile them.

git remote add origin <remote-repo-url>

git fetch origin

git merge origin/main --allow-unrelated-histories

git push origin main
