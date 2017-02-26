#	GitHub.com

GitHub 是 git 最著名的实例，它已经成为开源世界普遍认可的代码仓库，并与众多的平台实现了互联互通，成为程序员社交生态的重石之一。

##	了解 GitHub

推荐阅读：

*	[GitHub Help](https://help.github.com)  
	GitHub 官方帮助文档

*	[GotGitHub](http://www.kancloud.cn/kancloud/how-to-use-github)  
	by [看云文档小组](http://www.kancloud.cn/@kancloud)

##	GitHub API

https://developer.github.com/v3/

GitHub 是深爱程序员钟爱的社交舞台，因此，在常规的基于浏览器的 GUI 之外，通过 API 提供服务显然是必不可少的。我们来看几个简单的例子：

```bash
# 获取常用的 API URL（注意：并非全部）。
https://api.github.com/

# 获取用户基本信息。
# https://api.github.com/users/{username}
https://api.github.com/users/YounGoat

# 获取用户项目列表。
# https://api.github.com/users/{username(owner)}/repos
https://api.github.com/users/YounGoat/repos

# 获取项目详细信息。
# https://api.github.com/repos/{username(owner)}/{reponame}
https://api.github.com/repos/YounGoat/youngoat.github.io

# 获取我的信息。
curl -u "youngoat" https://api.github.com/user
# 将 youngoat 替换为你自己的账号，curl 命令会提示你输入密码。

```

###	基本原则

*	所有的访问都基于 HTTPS 协议。
	>	All API access is over HTTPS

*	所有的请求和响应数据都基于 JSON 格式。
	>	All data is sent and received as JSON.

###	，...

有关 GitHub API 的详细信息，请参阅官方文档：  
https://developer.github.com/v3/

##	GitHub Pages

https://pages.github.com

*Pages* 是 GitHub 官方提供的个人主页服务，每个 GitHub 用户可以在其账号下创建唯一的 Pages 项目，GitHub 针对该项目提供自动编译服务（如果基于官方指定的 Jekyll 模板引擎），并将结果发布为与该账号关联的个人主页。

##	GitHub Integrations

https://github.com/integrations
>	Use your favorite tools with GitHub.

GitHub 不是一个人在战斗，它是一个错综复杂的生态系统的一部分。我们永远也无法遍历这个世界的全部细节，但可以了解它的概貌，掌握它的法则，学习如何在其中自由穿行。
