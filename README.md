# DataSci-Project

# Getting Started
1. Initialize a Git repo in the project directory in the local machine.
   ```bash
   git init
   ```
2. Connect local repository to GitHub repo online.
   ```bash
   git remote add origin https://github.com/jwinn19464/DataSci-Project.git
   ```
3. Create a branch called main
   ```bash
   git checkout main
   ```
4. Pull changes from online.
Do this to get the latest version before you start working on it.
   ```bash
   git pull
   ```
   If you are not on the main branch, this command can be used to pull the changes: (Not recommended, just stick to main)
   ```git
   git pull origin main
   ```
   
# Pushing changes to GitHub
1. Add the file to the staging.
   ```bash
   git add file_name
   ```
2. Put in a commit message to label the commit
   ```bash
   git commit -m "commit message"
   ```
3. Push changes to GitHub
   ```bash
   git push -u origin main
   ```
