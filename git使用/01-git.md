
1. 首先 在新电脑上创建ssh密钥
2.  ssh-keygen -t rsa -C "574169815@qq.com"
3.  在 .ssh/文件下面找到 **id_ras.pub** ，复制密钥放在 github **settings**下的**ssh keys** 中
4. 添加远程仓库 ``git remote add origin https://github.com/MGRookie/VUElearn.gi``  **origin** 是远程仓库的名字， 一个仓库对应一个名字。后面会通过**git push origin master** 上传代码。其中的 **origin** 是仓库名， **master**是分支名。
5. git push origin main  
6. git pull origin main