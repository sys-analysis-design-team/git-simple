# 我的Git学习笔记

## 第一次 Git 实验总结

1. `git add` 的作用是：
   add指令将工作区中修改过或新建的文件添加到暂存区，为下一次commit做准备。

2. `git commit` 的作用是：
   commit指令将暂存区中的内容保存为一次本地的暂时性记录，并且可以附带提交说明。

3. 本次实验中 `git restore notes.md` 的作用是：
   可以撤销notes.md在工作区中的临时修改，使文件恢复到上一次提交时的状态。保护文件的状态。

4. `commit` 与 `push` 的区别是：
   commit只修改保存到克隆到本地的Git仓库中；
   push是把本地已经提交的commit修改上传到远程GitHub仓库。