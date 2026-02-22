# git-commands
> git clone <repo_url>
> git branch <branch_name> // it will create only branch with <branch_name>
> git checkout <branch_name> // it will checkout to <branch_name>
# -------------------------------
# (create + checkout) (mostly used)
> git checkout -b <branch_name> //this will create branch and checkout to <branch_name>
# -----------------------------
# Command	Meaning
> git switch -c branch  // Create + switch (same like git checkout -b <branch_name>) (-c means create)
> git switch branch	// Just switch (same like git checkout <branch_name>)
# example 
> git checkout -c feature/login