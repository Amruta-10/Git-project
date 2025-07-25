git config --global user.name "Amruta BS"
git config --global user.email "amruta@example.com"

mkdir my-first-git-project
cd my-first-git-project
echo "<h1>Hello Git!</h1>" > index.html

git init
git add index.html
git commit -m "Initial commit with index.html"

git remote add origin https://github.com/Amruta-10/Git-project.git
git branch -M main
git push -u origin main
