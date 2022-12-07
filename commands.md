git config --global user.name "kallam"
git config --global user.email "kallamvenky@gmail.com"

echo "# gitDemo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kallamvenky/gitDemo.git
git push -u origin main

or push an existing repo
git remote add origin https://github.com/kallamvenky/gitDemo.git
git branch -M main
git push -u origin main