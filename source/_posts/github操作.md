---
title: github操作
date: 2018-09-24 13:51:12
tags:
---
# github操作 #
## 本地仓库推送到github上 ##   
0.本地仓库  
`git init`  
1.关联远端  
`git remote add origin https://github.com/xxx`  
2.先更新一下  
`git pull --rebase origin master `  
3.本地操作  
`git add .` add全部  
`git commit -m "提交的说明"`  
4.查看状态  
`git status`  
5.推送到github  
`git push -u origin master`  
期间会需要输入username和password  
**完成推送**