# 1. Initialize Git in your project
git init

# 2. Add all your files (except the ones in .gitignore)
git add .

# 3. Save them with a commit message
git commit -m "Initial launch of Parth Posts"

# 4. Connect to your new GitHub repository
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/parth-posts.git

# 5. Push your code to the internet!
git push -u origin main