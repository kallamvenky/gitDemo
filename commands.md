git config --global user.name "kallam"
git config --global user.email "kallamvenky@gmail.com"

echo "# gitDemo" >> README.md
git init
git add README.md
git status
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/kallamvenky/gitDemo.git
git push -u origin master

or push an existing repo
git remote add origin https://github.com/kallamvenky/gitDemo.git
git branch -M master
git push -u origin master


To clone
git clone https://github.com/kallamvenky/gitDemo.git # onetime
git pull origin master # from subsequent runs
git checkout -b dev # to create branch
git branch # to check total number of branches

