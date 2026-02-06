# My-step-by-step-guideline
This is the first time I create a guideline to pull anything on Github. I want to save it.
First, create a repository in Github. Then clone it by opening Desktop Git and then VS Code 
Or use this code in terminal: git clone <HTTPS>
Then check where you are
Code: git status (should be in main)
Check remote connection (important)
Code: git remote -v 
Expected output:
origin  git@github.com:username/repo-name.git (fetch)
origin  git@github.com:username/repo-name.git (push)
✅ This means your local repo is connected to GitHub.
Create a new branch: 
Code: git switch -c <branch name>
Make code changes or write new code
Then, save: Command + S