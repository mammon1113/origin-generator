---
title: 如何建立hexo
date: 2017-10-04 23:58:54
tags:
---
### 使用 Hexo + GitHub 可以轻松搞出一个好看的博客，以下是步骤。

1.在 GitHub 上新建一个空 repo，repo 名称是「你的用户名.github.io」（请将你的用户名替换成真正的用户名）
2.npm install -g hexo-cli，安装 Hexo
3.hexo init myBlog
4.cd myBlog
5.npm i
6.hexo new 开博大吉，你会看到一个 md 文件的路径
7.start xxxxxxxxxxxxxxxxxxx.md，编辑这个 md 文件，内容自己想
8.start _config.yml，编辑网站配置
 1.1把第 6 行的 title 改成你想要的名字
 1.2把第 9 行的 author 改成你的大名
 1.3把最后一行的 type 改成 git(type: git)
 1.4在最后一行，与 type 平齐，加上一行 repo: 仓库地址 （请将仓库地址改为「你的用户名.github.io」对应的仓库地址，仓库地址以 git@github.com: 开头你知道吧？不知道？不知道的话现在你知道了）
9.npm install hexo-deployer-git --save，安装 git 部署插件
10.hexo deploy
11.进入「你的用户名.github.io」对应的 repo，打开 GitHub Pages 功能，如果已经打开了，就直接点击预览链接
12.你现在应该看到了你的博客！
                                            ----摘自饥人谷xiedaimala.com