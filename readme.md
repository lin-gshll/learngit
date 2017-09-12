## 创建版本库
   + 初始化版本库的命令:git init;
   + 将文件添加到仓库:git add [文件名];
   + 将文件提交到仓库:git commit -m "一些备注";
## 简单操作
   + 查看文件状态:git status;
   + 查看文件以前的修改:git diff readme.txt;
   + 查看提交日志:git log
   + 滚回到某个版本: git reset --hard [版本前缀]
   + 删除文件: rm [文件名];
## 远程仓库
   + 首先在githup官网上创建自己的远程仓库:如:
   + 然后在本地创建README.MD文件
   + 之后执行 git remote add origin https://github.com/lin-gshll/learngit.git
   + 推送到远程仓库：git push origin master