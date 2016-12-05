#	ATOM

##	Atom Package 开发

参考资料：
*	*Atom Flight Manual, Package: Word Count*  
	http://flight-manual.atom.io/hacking-atom/sections/package-word-count/

###	STEP 1，初始化包  

我们可以利用 Package Generator 来创建一个包。Package Generator 本身也是一个 Atom 包，可以通过以下菜单调用：
```
Packages / Package Generator / Generate Atom Package  
```
或者，使用快捷键 ```Command + Shift + P``` 打开命令面板（Command Palette），输入名称检索。

除了搭建包的骨架之外，Package Generator 还把包目录链接到 ~/.atom/packages/ 目录下，如果不出意外，Atom 可以即时加载到新创建的包，你可以在 Packages 菜单下找到它。


##	FAQ

*	__为什么有时候不能识别 git 仓库？__  
	这种问题并非“偶然”，其实是有规律的。@see  
	-	[Atom does not recognize git worktree repositories](https://github.com/atom/atom/issues/8168	)  
	-	[Git integration doesn't work if .git/ not in top level](https://github.com/atom/atom/issues/2203)

##	在线资源

*	*Atom Flight Manual*  
	http://flight-manual.atom.io
