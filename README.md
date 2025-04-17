============================================
🔥 GIT & GITHUB COMMAND CHEAT SHEET (VS CODE)
============================================

1️⃣ INIT & CLONE
----------------
git init                # Start new repo
git clone <url>         # Clone a repo

2️⃣ BASIC WORKFLOW
------------------
git status              # Check changes
git add <file>          # Stage a file
git add .               # Stage all changes
git commit -m "msg"     # Commit changes
git push                # Push to GitHub
git pull                # Pull latest changes

3️⃣ BRANCHING
-------------
git branch              # List branches
git branch <name>       # Create branch
git checkout <name>     # Switch branch
git checkout -b <name>  # Create + switch
git merge <branch>      # Merge branches
git branch -d <name>    # Delete branch

4️⃣ UNDO CHANGES
----------------
git restore <file>      # Discard unstaged changes
git reset <file>        # Unstage file
git reset --hard        # ⚠️ Wipe all local changes
git revert <commit>     # Undo a commit safely

5️⃣ REMOTE & GITHUB
-------------------
git remote -v           # List remotes
git push origin main    # Push to main branch
git push --force        # ⚠️ Overwrite remote (DANGER!)
git fetch               # Download remote changes

6️⃣ BACKUP & SYNC
-----------------
git push --all          # Push all branches
git tag v1.0            # Create version tag
git stash               # Save unstaged changes
git stash pop           # Restore stashed changes

7️⃣ LOG & HISTORY
-----------------
git log                 # Show commit history
git log --oneline       # Compact history
git diff                # See unstaged changes

============================================
💡 PRO TIPS:
- Use VS Code’s GUI (Source Control tab) for most actions!
- Always `git pull` before `git push` to avoid conflicts.
- Backup often: Commit + Push to GitHub daily!
============================================
