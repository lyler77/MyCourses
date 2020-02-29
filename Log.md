# 项目日志

## 20200229
- 目的：学习docsify+github pages搭建文档网站

- 任务：将本学期的课程笔记整理到网站上去，未来会整理更多其他笔记

- 参考：https://www.cnblogs.com/happyone/p/12152566.html

- 基本步骤（基本来自以上参考）

  - 前提：git+node

  - 安装docsify-cli工具：
    `npm i docsify-cli -g`

  - 打开cmd，cd到项目目录(如E:\mypro)，执行

    `docsify init ./docs`

  - 启动项目，http://localhost:3000 预览

    `docsify serve docs`

  - [可选]配置左侧导航栏、配置封面（暂时没做因为觉得不方便查看文档）

  - 部署到github上

    - 创建一个仓库
    - 进入项目目录(E:\mypro)，git bash here
    - `git init`
    - `git add -A`
    - `git commit -m "first commit"`
    - `git remote add origin https://github.com/xxxxx/xxx.git`
    - `git push -u origin master`
    - 在gtihub仓库的settings中，找到github pages，在source下面选择master branch / docs folder
    - 完成，同时提示你网站地址

- 感想：按照这个步骤做下来不难，后期遇到点问题是git了一遍，后面从另一个地址git，然后出现了各种问题(docs

  文件夹不能正常显示)，删了仓库，又重新弄，总之可以了。之后就可以用这个方法构建文档站点了，整理笔记方便多了~

