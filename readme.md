echo "# git-test" >> README.md
git init
git add README.md
git commit -m "первый коммит"
git branch -M main
git remote add origin https://github.com/Shved127/git-test.git
git push -u origin main
