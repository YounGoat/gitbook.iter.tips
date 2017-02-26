#	FAQ

##	编译

###	ld: library not found for -lcrt0.o

*	OS: __Mac OS X__ Sierra

```bash
g++ helloworld.cpp -o helloworld -static
# OUTPUT：
# ld: library not found for -lcrt0.o
# clang: error: linker command failed with exit code 1 (use -v to see invocation)
```

>	Static linking does not work on mac os x with the llvm/clang gcc.  
>	@cite https://github.com/crosstool-ng/crosstool-ng/issues/31
