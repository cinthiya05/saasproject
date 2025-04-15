✅1. Create a GitHub repository
Go to github.com → Click New Repository → Fill in the details → Click Create repository.

✅2. Initialize Git in your project (if not already)
Open terminal in your project folder and run:
git init

✅ 3. Add your files and commit
git add .
git commit -m "Initial commit"

✅ 4. Link your local repo to GitHub
Copy the repo URL from GitHub (use HTTPS or SSH). Then:

git remote add origin https://github.com/your-username/your-repo-name.git
If you already have a remote and need to replace it:

git remote set-url origin https://github.com/your-username/your-repo-name.git

✅ 5. Push to GitHub

git push -u origin main
If your default branch is master, use:

git push -u origin master
