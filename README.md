# apt-blog 使用说明

## 环境准备

[apt-blog](http://apt.artemisprojects.org) 使用[hexo](http://hexo.io)博客引擎，请使用`npm install hexo-cli -g`命令安装hexo环境


## clone现有代码

`git clone https://github.com/icsnju/apt-blog.git`

## 安装依赖包

`cd apt-blog`

`npm install`

## 添加、修改内容

使用`hexo new "article title"` 创建新文章或编辑source\\\_posts\目录下已有md文件修改既有文章内容

## 发布内容

使用`hexo generate` 命令重新生成网页内容，并使用`hexo deploy`命令发布生产的内容到网站。

## 提交更新内容

按git流程提交对blog-nap的hexo内容所做修改（`git add .` -> `git commit -a` -> `git push origin master`）。
然后执行`hexo d -g`，hexo由markdown文件生成静态html页，并将其push到`gh-pages`分支上去。

在此之前，当然你需要授权，请联系 [hub@artemisprojects.org](mailto:hub@artemisprojects.org)。
