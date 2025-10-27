test git operations

…or create a new repository on the command line
echo "# tv9" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kpap2504/tv9.git
git push -u origin main