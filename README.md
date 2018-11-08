"# idealProject" 
echo "# idealProject" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:abcguozhitao/idealProject.git
git push -u origin master


#新建分支dev
git checkout -b dev 
git push origin dev
两条命令执行完后，就可以看到本地仓库和远程仓库都新建了一个名为dev的分支