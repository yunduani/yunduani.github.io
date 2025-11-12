+++
date = '2025-11-10T14:30:00+08:00'
draft = false
title = '2025.11.10' 
categories = ['学习']  
description = '这是一篇关于docker中的openlist 和1panel使用的学习笔记'  
+++
# 操作指令与流程

## 1Panel 安装与卸载
### 安装
bash -c "$(curl -sSL https://resource.fit2cloud.com/1panel/package/v2/quick_start.sh)"

### 卸载
1pctl uninstall
### 这个是查看1panel的登陆IP
1panel-core user-info  

## Openlist 注意事项
- 本地挂载的路径是镜像路径，不是宿主机路径！！！
- 根文件夹路径：/opt/openlist/data/本地网盘


## Hugo 博客自动化更新（第 10 步）
1. 新建文章
hugo new post/xxx/xxx.md

2. 编辑内容
（直接编辑生成的 .md 文件）

3. 本地预览
hugo server -D

4. 满意后提交
git add .
git commit -m "add hello world post"
git push





