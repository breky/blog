# Breky's Blog

使用 Hexo + Github 搭建的静态博客，本机使用的是 Manjaro 系统。

改用 Ubuntu 22.04 LTS 了

## 安装 Hexo

Hexo 的详细安装过程在官网文档（及其中涉及的链接）中可以找到（[传送门](https://hexo.io/zh-cn/docs/)），以下仅记录 Manjaro 系统的安装过程。

### 安装前提

安装 Hexo 前必需安装 **Node.js** 和 **Git**，一般 Manjaro 系统自带 Git，以下是 Nodejs 的安装命令：

```shell
sudo pacman -S nodejs npm
```

其他 Linux 系统可以在[这里](https://nodejs.org/en/download/package-manager)查找，Ubuntu 22.04 LTS 可以在商店中安装，并且不用单独安装 npm。

### 安装 Hexo

使用 npm 安装 Hexo，在 terminal 中输入以下命令：

```shell
npm install hexo-cli
```

## 待记录

- [ ] Github Pages Custom Domain
- [x] [Backup and Recovery](https://blog.breky.win/cn/Hexo/BackupAndRecovery/)