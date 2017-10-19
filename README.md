echo "# test" >> README.md
git init # init  git repository
git add README.md 
git commit -m "first commit"
git remote add origin https://github.com/yuki-yam/test.git
git push -u origin master
