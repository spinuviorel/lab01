First command: git init 
git clone <URL>

git status
git add <FILE>
git commit
git commit -m "MESAGE"
git log
git log --oneline

git diff
git diff --staged
git diff HEAD~2
git diff [hash] : after git log --oneline

git restore --source <HASH or HEAD> <FILE>
git checkout <HASH or HEAD> FILE
git checkout <HAS or HEAD> : if you forget the FILE, you and up in detach HEAD
git checkout master : go back to master
git switch master


