#	Chocolatey

>	The package manager for Windows  
>	Chocolatey - Software Management Automation

##	在线资源

*	官方网站  
	https://chocolatey.org

##	Get Started

```cmd
REM 安装指定版本
choco install nodejs --version=6.9.1

REM 显示本地已安装的软件
choco list -l
REM Here -l may be expanded to --lo, --localonly, or --local-only
```

##	FAQ

*	__怎样查询软件的安装目录？__  
	抱歉，每个软件的安装过程由其安装脚本自行决定，所以目前 choco 并不知道它被安装在哪里。
