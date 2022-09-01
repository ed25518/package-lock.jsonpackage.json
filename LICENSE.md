echo "# package-lock.jsonpackage.json" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ed25518/package-lock.jsonpackage.json.git
git push -u origin main
