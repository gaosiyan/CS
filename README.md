

# 目标文件格式
&emsp;&emsp;目前PC平台流行的可执行文件格式(Executable),主要是Windows下的PE(Portable Executable)和Linux下的ELF(Executable Linkable Format),它们都是COFF(Common file format)格式的变种.目标文件就是源代码编译后,但没有经过链接的那些中间文件(Windows下的`.obj`和Linux下的`.o`),目标文件的内容与结构和可执行文件几乎是一样的.不光是目标文件,动态链接库(DLL,Dynamic Linking Library,Windows下的`.dll`和Linux下的`.a`)以及静态链接库(Static Linking Library,windows下的`.lib`和Linux下的`.a`)都是按照这种格式存放的.

