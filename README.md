# git-test

这个是一个 git 测试仓库，用于测试各种 git 操作，有空会上传一些 git 教程。

测试 git

环境：VScode

## 第一章

`git clone` 下来项目，然后是要 VScode 打开，然后进行修改。

文件变成绿色，右边存在 U 标志，表示该文件被修改了，只不过没有提交

<p align="center">
  <img src="https://cwrisingimage.oss-cn-beijing.aliyuncs.com/img/20240325162503.png" alt="图片描述">
</p>

在 Git 中，"M"和"U"表示不同的状态：

1. **M（Modified）**：表示文件已经被修改，并且这些修改已经被添加到暂存区（Staged）。这意味着你对文件进行了更改，并且使用了`git add`命令将这些更改添加到了暂存区。

2. **U（Untracked）**：表示文件是未跟踪的。这意味着该文件存在于工作区中，但并未被 Git 跟踪。通常情况下，未跟踪的文件不会被包含在版本控制中。比如，你新建了一个文件，或者修改了这个文件的名字,都会显示 U。

总之，在 Git 中，"M"表示文件已被修改并暂存，而"U"表示文件是未跟踪的。

## 第二章

写上备注，点击提交按钮，就会提交到暂存区。

<p align="center">
<img src="https://cwrisingimage.oss-cn-beijing.aliyuncs.com/img/20240325164505.png"/>
</p>
点击同步，会自动更新到github。
<p align="center">
<img src="https://cwrisingimage.oss-cn-beijing.aliyuncs.com/img/20240325164607.png"/>
</p>

## 第三章

Gitlens 插件

<p align="center">
<img src="https://cwrisingimage.oss-cn-beijing.aliyuncs.com/img/20240325165029.png"/>
</p>

分支合并，在 Main 的枝干下面，然后进行分支合并。

<p align="center">
<img src="https://cwrisingimage.oss-cn-beijing.aliyuncs.com/img/20240325165844.png"/>
</p>
