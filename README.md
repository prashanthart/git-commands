# git-commands
- `git clone <repo_url>`
- `git branch <branch_name>` // it will create only branch with <branch_name>
- `git checkout <branch_name>`// it will checkout to <branch_name>
# (create + checkout) (mostly used)
- `git checkout -b <branch_name>` //this will create branch and checkout to <branch_name>
# Command	Meaning
- `git switch -c branch`  // Create + switch (same like git checkout -b <branch_name>) (-c means create)
- `git switch branch`	// Just switch (same like git checkout <branch_name>)
# example 
- `git checkout -c feature/login`
# -----------------------------
1) I am actually on `main` branch (initial branch got from repo cloned)
2) do  `git checkout main`
3) make some changes on main branch
4) do `git status` //to check the status, what files got changed
5) do `git add .` // It stages all changes in the current directory. ✅ New files,✅ Modified files, ✅ Deleted files
6) (to add only single file) `git add <file_name>`
7) do `git commit -m 'commit message' `
8) do `git push origin main`
# experiment
- making changes on main branch
# experiment 2
I am doing changes in branch_2
# reverting
push to revert
# pushed again after the branch_2 committed in local