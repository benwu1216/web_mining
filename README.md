## 1. 初始化本地git仓库

在project所在目录下进vscode终端，输入git init初始化本地git仓库

## 2. 创建并切换到自己的分支

输入git checkout -b wzy(wzy为自己名字的缩写)  
意思为创建并切换到自己的分支

## 3. 添加远程仓库（只需要第一次使用时执行）

git remote add origin https://github.com/benwu1216/web_mining.git

## 4. 发起一次更改并提交

git add 修改的文件  
git commit -m "修改文件对应的说明信息"

如：  
git add README.md  
git commit -m "Add README file to the repository."

## 5. 将提交发送到远程仓库

git push -u origin wzy(wzy为自己名字的缩写)  
-u 表示跟踪，下一次push的时候只需要git push即可

## 6. 在github网页上Create pull request

根据github网页提示完成即可！

## 7. 第一次执行以后的工作流程

- git checkout -b wzy(对应自己名字缩写)
- 修改项目文件a
- git add a
- git commit -m "xxx"
- git push -u origin wzy(或直接git push) 