# IDETips

git的用法

1、下载git

2、cd到某个目录，然后在终端输入  git clone git地址  将项目复制下来

3、终端输入git init，初始化创建.git文件夹

4、修改后输入git status查看命令

5、使用git add建立跟踪

6、如果此时输入git status，会显示如下

    Changes to be committed:
    
     (use "git reset HEAD <file>..." to unstage)

        modified:   readme.md       

7、使用git commit提交到本地，输入一段描述后wq保存即可(如果不输入描述会导致失败Aborting commit due to empty commit message.）
    再观察git status
    此时会提示nothing added to commit but untracked files present (use "git add" to track)
