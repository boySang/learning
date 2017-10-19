git add "添加文件"

git reset --hard HEAD^  //恢复版本

git reflog  //查看以前提交的记录

git status  //查看当前暂存区

git checkout --textme.txt  //撤销工作区的修改

对dev分支修改

git checkout -b dev  //创建并且换到dev分支

git branch dev   //创建dev分支

git checkout dev   //切换到dev分支

git branch -d dev  //删除dev分支

git checkout master;
git branch -d dev;	//合并dev分支到master

继续新分支