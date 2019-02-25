# test

在本地安装了Git ，弄清楚了基本的上传和下载。

上传到gitHub：
        打开需要上传的文件夹 点右键 打开命令行 Git Bash Here  

        git init  （在该目录中 创建一个 Git 仓库了）

        git status

        git remote add origin https://github.com/WxmDe/springBoot.git  （添加远程仓库）

        git remote -v (显示fetch 和push的地址，可以看到是否是自己想要上传的地址)

                origin  https://github.com/WxmDe/springBoot.git (fetch)

                origin  https://github.com/WxmDe/springBoot.git (push)

        git add . (提交到缓存区)

        git commit -m "v1..0" （提交到head）

        git push -u origin master （提交到远程仓库）
下载到本地 ：
        git init 
        git clone 资源地址

