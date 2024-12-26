# Git Command Guide
This README provides a basic guide to commonly used Git commands for version control.

1. Getting Started
   ```bash
   git clone https://github.com/HIMASIA/SGS-2025.git
   ```


2. cd nama_folder kemudian intialisasi tailwind
   ```bash
   npx tailwindcss init
      ```
3. Working with Changes
   Check Status
   View the current state of your repository (staged, unstaged, and untracked files).
   
   ```bash
    git status
   ```

   
4. Add Changes
   Stage changes for the next commit.
      
   ```bash   
   git add .                
   ```

   
5. Commit Changes
   Save staged changes to the repository with a message.
   
   ```bash
   git commit -m "Your commit message"
   ```


6. Working with Remote Repositories
   Add a Remote
   Link your local repository to a remote repository.

   ```bash
   git remote add origin https://github.com/HIMASIA/SGS-2025.git
   ```

   
7. Push Changes
   Upload your commits to the remote repository.
   
   ```bash
   git push origin <branch_name>
   ```

   
8. Pull Changes
   Fetch and integrate changes from the remote repository.
   ```bash
   git pull origin <branch_name>
   ```

   


🌐 Helpful Links

Git Documentation
GitHub Docs
