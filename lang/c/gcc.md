#	GCC, the GNU Compiler Collection

GCC 早期的全称是 GNUL C-language Complier，经过不断的扩展之后，它已经成为支持多种程序语言的一整套编译器，故其名称也变更为 GNU Complier Collection，但是毫无疑问，C++ 仍然是它的主战场。

## QUICK START

### 编译 C 代码

```bash
# foo.c supposed

# PREPROCESS
gcc -E foo.c > foo.i
# 输出经预处理器优化后的中间代码

# PREPROCESS + COMPILE
gcc -S foo.c -o foo.s
# 输出汇编语言代码

# PREPROCESS + COMPILE + ASSEMBLE
gcc -c foo.c -o foo.o
# 输出目标代码

# GENERATE
gcc foo.o -o foo
# 生成可执行文件

# ALL IN ONE
gcc foo.o -o foo
```

### 编译 C++ 代码

```bash
# foo.cpp supposed

# 可以使用 gcc 命令
gcc -l stdc++ foo.cpp -o foo

# 也可以直接使用 g++ 命令
g++ foo.cpp -o foo
```

##	相关命令

在目前（2017）的 Mac OS X 系统中，系统原生的 C/C++ 编译器是 Clang 而非 GCC，命令 ```gcc``` 不过是 ```clang``` 的别名。

| 命令 | 用途 |
| :------------- | :------------- |
| *ar* | create and maintain library archives |
| *clang* | the Clang C, C++, and Objective-C compiler |
| *clang++* | the Clang C++ compiler |
| *cc* | alias of clang |
| *c++* | alias of clang++ |
| *ld* | linker |
| *gcc* | alias of clang |
| *g++* | alias of clang++ |

##	SEE

*	官方网站  
	https://gcc.gnu.org
