# Git使用教程

前置教程

## [git配置GitHub推荐教程 ](https://www.cnblogs.com/linshengqian/p/15065553.html)

如果使用代理导致无法连接的情况,直接关闭代理检查
> git config --global http.sslVerify false





1、创建dev分支

```bash
git checkout -b dev
```

<mark>2、将本地的 demo 分支进行本地的 commit 提交：</mark>

```bash
git add .
git commit -m "完成了 dev 的开发"
```

<mark>3、将本地的 dev 分支推送到远程仓库进行保存：</mark>

```bash
git push -u origin dev
```

4、将本地的 dev 分支合并到本地的 main 分支：

```bash
git checkout main
git merge dev
```

5、如果步骤3无法推送，可能是冲突导致，可以用`git pull`先从远程仓库同步到本地，实在不行就随意先建一个新的分之推上去等我来解决



##  使用第图形化工具

- vscode 和 Jetbrains（推荐）
- [Fork](https://git-fork.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [![Sourcetree logo](https://wac-cdn.atlassian.com/dam/jcr:f32681c1-355d-4806-b29c-319b0c6ecb06/Sourcetree-blue.svg?cdnVersion=1227)](https://www.sourcetreeapp.com/)

