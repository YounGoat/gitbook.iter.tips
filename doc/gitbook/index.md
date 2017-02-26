#	GitBook

##	QUICKSTART

```bash
# 安装
npm install -g gitbook

# 安装完成后，将在系统中创建 gitbook 命令
type gitbook

# 显示关于 gitbook 命令管理和维护的帮助信息
gitbook -h

# 显示关于 gitbook 使用的帮助信息
gitbook help

# 初始化目录
cd /path/to/book
gitbook init

# ...

# 编译，将生成 _book 子目录，可作为电子书的 webroot
gitbook build

gitbook versions
```

## 	FAQ

*	__无法在 Mac OS X 中输出 PDF 格式？__

	在 Mac OS X 系统中试图输出 PDF 格式文件时，可能会遇到以下提示：
	```
	$ gitbook pdf
	...
	Error: Need to install ebook-convert from Calibre
	```

	需要先安装 Calibre，然后创建其命令行转换工具 ebook-convert 的软链接：
	```
	$ ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin
	```

##	SEE

*	官方网站  
	https://www.gitbook.com/

*	*GitBook Design Styleguide*  
	http://styleguide.gitbook.com

*	*GitBook Help Center*  
	https://help.gitbook.com

*	*GitBook Toolchain Documentation*  
	https://toolchain.gitbook.com

*	*Nunjucks*  
	https://mozilla.github.io/nunjucks/
	>	A rich and powerful templating language for JavaScript.

##	FAQ

*	*How can I include custom CSS?*  
	https://help.gitbook.com/content/how-can-i-include-css.html
