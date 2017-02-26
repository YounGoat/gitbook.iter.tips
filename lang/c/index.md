#	C 与 C++

##	GCC, Clang and LLVM

>	The name "LLVM" itself is not an acronym; it is the full name of the project.

虽然LLVM 官方这样强调，但直到现在，很多人仍然认为 LLVM 是 Low Level Virtual Machine 的缩略语。LLVM 在编译器（前端[^1]）与操作系统（后端）之间承上启下，作用有点类似于 JVM，只不过后者前端面向的不是编译器，而是运行时环境。

Clang 是由苹果公司发起的，基于 LLVM 的 C 基语言编译器。

##	SEE

*	*C++ Language*  
	English http://www.cplusplus.com/doc/tutorial/  
	中文版 http://www.prglab.com/cms/

##	REF

*	*LLVM 与 Clang 介绍*  
	https://linuxtoy.org/archives/llvm-and-clang.html

[^1]: 在编译语言领域，“前端”这一术语被广泛使用，指代基于通用虚拟机的、面向特定程序语言的编译工具。web 开发领域的“前端”程序员在介入编译语言开发时，需要重新认识这一术语。
