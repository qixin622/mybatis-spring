## mybatis-spring

MyBatis 和 Spring 集成的项目。

`$ echo ” > .gitignore`
此时就会在当前目录下创建一个空的.gitignore 文件 。 

`$ git init`
执行完该命令后会在当前目录下创建一个隐藏的 . git 目录，这个目 录是 Git 用来跟踪当前版
本库的，切记不要轻易修改或删除该目录下的内容。 

`$ git add --all`
这个命令只是告诉 Git 要添加什么文件，还没有真正把这些文件添加到仓库中

`$ git status `

输入 git status 查看当前 的状态 

`$ git commit -m ’ 初始导入 ’ `

使用 git commit 命令提交文件的时候，必须通过－m 参数指定提交信息。 

一般情况下，添加远程仓库时通常使用 origin 作为远程仓库 的名字 ， 如
果按照上一节 Git 入门中的操作步骤添加过本地的远程仓库 ， 那么 origin 己经被使用了 ， 因此
要先通过以下命令删除之前创建的 origin 。 

`$ git remote remove origin `

`$ git remote -v `

删除后，再通过上述代码中的第二个命令查看 remote，此时会显示空。 

使用 下面的命令将刚刚创建的远程仓库配置为 origin 。

`git remote add origin https : //github . com/abel533/simple . git `

添加好远程仓库后 ， 执行如下命令将本地仓库的代码提交到服务器上。
`$ git push -u origin master `

