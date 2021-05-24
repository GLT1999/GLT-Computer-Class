```c++
Git部署连接Github
    $ cd ~/.ssh/	//默认文件夹
    $ git config --global user.name "GLT1999"
    $ git config --global user.email "2664578341@qq.com"
    $ ssh-keygen -t rsa -C "2664578341@qq.com"
    $ cat id_rsa.pub //key
```

```c++
初始化：git init
添加远程库：git remote add origin url
添加文件：git add filename
查看当前状态：git status
创建说明：git commit -m "xx"
推送代码到远端：git push
从远端拉取代码：git pull
```

