#### 分支

##1. 查看分支<br />
git branch（本地）<br />
git branch -r（远程）<br />
git branch -a（所有分支）

##2. 删除分支<br />
git branch -D(--delete) branchName（本地）<br />
git branch -r -D origin/BranchName（本地的远程分支）<br />
git push origin -d(--delete) BranchName（远程删除git服务器上的分支）<br />

##3. 远程clone和拉取分支<br />
git pull origin 远程分支<br />
git clone 项目地址

##4. 创建分支并切换
git branch 分支名

git checkout 分支名

git checkout -b 分支名（创建并切换分支）

git push origin 分支名


##5. 本地保存提交上传<br />
git add .

git commit -m "init panda"

git push origin panda

##6. 查看远程库信息（远程库默认名为origin)
git remote

git remote -v

