# Terms

Repository (Repo)
Branch (A repo contain many branches depend on the activity we make, the default branch is master)
Conflict
Local (all things that locates on your computer)
Remote (the things that locate on other server)

# Commands

- git init
- git status (status of repo)
- git add (add file to the buffer to wait to be push to git)
- git reset (reset all things happen and return to the status when git init)
- git commit -m 'ghi chu'
- git log (get the id commit and see who change the repo and the date happen)
- git log --oneline
- git checkout idCommit (when run log, we will get the ID of each commit phase and if we want to return to the period of time when some commit happen we only need git checkout idCommit)
- git checkout branch_name (return to what branch, if you want to return to the period before git checkout idCommit you use git checkout master)
- git branch (get all name of branch in repo)
- git checkout -b {branch_name} (create new branch) (before create we must save all previous)
- git checkout {branch_name} (switch to the branch named branch_name)
- git merge {branch_name} (Lưu ý nếu ta commit file trong branch nào thì khi chuyển sang branch khác file đó sẽ không xuất hiện, muốn file thuộc branch này xuất hiện tại branch khác thì tại branch đích ta phải sử dụng git merge để ghép 2 branch lại)
- git branch -d {branch_name} (delete branch)
- git push (push local repo to remote repo in GitHub)
