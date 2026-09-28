# 1. Project folder එක ඇතුළේ Git initialize කරන්න
git init

# 2. Files සියල්ල staging area එකට එකතු කරන්න
git add .

# 3. Code එකට message එකක් එක්ක save (commit) කරන්න
git commit -m "Initial commit - First version of my project"

# 4. GitHub එකේ main branch එක rename කරන්න
git branch -M main

# 5. ඔබේ GitHub Repo link එක සම්බන්ධ කරන්න (URL එක ඔබේ Repo link එකෙන් වෙනස් කරන්න)
git remote add origin https://github.com/your-username/your-repo-name.git

# 6. Code එක GitHub එකට Upload කරන්න
git push -u origin main
