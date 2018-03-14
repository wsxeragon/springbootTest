git仓库有两个分支master和test
master分支有文件a.txt，内容：123
test分支有文件a.txt，内容：456
合并a.txt为123456


本地新建文件夹
git init
git remote add origin http://... 关联远程库
git pull origin master
git branch test
git checkout test
git pull origin test
git checkout master
git merge test
手动解决冲突
git add a.txt
git commit -m "1"
git push origin master