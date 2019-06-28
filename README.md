##cat

##提交
git init
git add .
git commit -m "提交类容概括"
git remote add origin https://github.com/depth-cat/community.git
git push -u origin master

##修改提交
git add .
git commit --amend --no-edit
git push
