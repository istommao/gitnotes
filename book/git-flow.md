# git flow 工作流

> https://github.com/nvie/gitflow
> https://danielkummer.github.io/git-flow-cheatsheet/index.zh_CN.html

## 安装

```bash
# OSX
brew install git-flow-avh

# Linux
apt-get install git-flow

# Windows (Cygwin)
wget -q -O - --no-check-certificate https://raw.github.com/petervanderdoes/gitflow-avh/develop/contrib/gitflow-installer.sh install stable | bash
```

## 基本步骤

```bash
git flow init

# feature
git flow feature start gitflow
git flow feature finish gitflow

# hotfix
git flow hotfix start bug
git flow hotfix finish bug

# release
git flow release start v1
git flow release finish v1
```