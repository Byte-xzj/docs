# 仓库

仓库（Repository）是集中存放镜像的地方。仓库概念的引入，为 Docker 镜像文件的分发和管理提供了便捷的途径。

一个容易混淆的概念是注册服务器（Registry）。实际上注册服务器是管理仓库的具体服务器，每个服务器上可以有多个仓库，而每个仓库下面有多个镜像。从这方面来说，仓库可以被认为是一个具体的项目或目录。例如对于仓库地址 store.docker.com/ubuntu 来说，store.docker.com 是注册服务器地址，ubuntu 是仓库名。大部分时候，并不需要严格区分这两者的概念。

仓库分为公有仓库和私有仓库。

公有仓库地址：

1. Docker Store 官方镜像库: https://store.docker.com/
2. 阿里云镜像库： https://dev.aliyun.com/search.html
3. DaoClound 镜像库： https://hub.daocloud.io/

私有仓库搭建与使用见： Harbor 私有仓库部署章节。 
