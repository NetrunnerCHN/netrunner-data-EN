# 《矩阵潜袭》英文卡牌数据仓库镜像

## 项目简介

本仓库是 [NetrunnerDB/netrunner-cards-json](https://github.com/NetrunnerDB/netrunner-cards-json) 的镜像分支仓库，原仓库为 [NetrunnerDB](https://netrunnerdb.com) 提供《矩阵潜袭》英文卡牌数据。

由于原仓库是《矩阵潜袭》最权威的卡牌数据库，因此本仓库理论上只作为原仓库的镜像。创建本仓库只是为了避免开发组的其它项目在需要使用卡牌数据时依赖于不归属于开发组管理的仓库，以及在必须进行某些修改时有权限对仓库中的内容进行修改与提交。

## 维护说明

本仓库的 `master` 分支保持与原仓库同步，不允许进行任何提交。

本仓库的 `mirror` 分支为开发分支，虽然我们强烈不建议在本仓库进行任何修改，但对于确实无法避免的改动，应提交到 `mirror` 分支。其它项目对本项目的引用（如：`git submodule`）也应当通过 `mirror` 分支进行。

`master` 分支上的变更都需要合并、同步到 `mirror` 分支。
