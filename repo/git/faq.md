#	Git FAQ

0.	__What does push.default "matching" and "simple" mean?__  
	在 Git 2.0+ 版本中，本地分支与远端分支未关联，是 push 失败的常见的原因。命令行提示中讲得很清楚：
	> its implicit value has changed in Git 2.0 from 'matching' to 'simple'.  
	> ...  
	> When push.default is set to 'matching', git will push local branches to the remote branches that already exist with the same name.
	>
	> Since Git 2.0, Git defaults to the more conservative 'simple' behavior, which only pushes the current branch to the corresponding remote branch that 'git pull' uses to update the current branch.

0.	__Why the files just pulled from remote are "unstaged"?__   

0.	__如何从版本库中移除文件的同时，不执行物理删除？__  
	```bash
	# 从暂存区删除。
	git rm <path> -r --cached

	# 立即提交，切勿再执行 git add 命令。
	git commit -m "..."
	```
