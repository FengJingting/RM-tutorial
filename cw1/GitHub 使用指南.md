### GitHub 使用指南

1. 创建本地仓库并提交到远程仓库、

   ```
   # 配置个人信息
   git config --global user.name "username"
   git config --global user.email "email@xxx.com"
   
   # 初始化仓库
   git init
   
   # 暂存修改
   git add .
   
   # 提交修改
   git commit -m "first commit"
   
   # 查看历史纪录
   git log
   
   # 撤销某个文件的修改
   git checkouut -- filename
   
   # 添加远程仓库
   git remote add origin https://gitee.com/liyifan2002/train2022fall.git
   
   # push到远程
   git push 
   
   # 查看远程仓库
   git remote -v
   
   # pull到本地
   git pull 
   
   # pull 指定分支 origin main 
   git pull origin main 
   ```

   

