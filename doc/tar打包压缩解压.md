## 简介

#### tar是打包.压缩.解压缩命令

参数：

-c	:建立一个压缩档案的参数指令(create 的意思)；

-x	:解开一个压缩档案的参数指令！

-t	:查看 tarfile 里面的档案！

*特别注意，在参数的下达中， c/x/t 仅能存在一个！不可同时存在！因为不可能同时压缩与解压缩。*

-z	:是否同时具有 gzip 的属性，亦即是否需要用 gzip 压缩(.gz)；

-j	:是否同时具有 bzip2 的属性，亦即是否需要用 bzip2 压缩(.bz2)；



-v	:压缩的过程中显示档案！这个常用，但不建议用在背景执行过程！

-f	:使用档名，请留意，**在 f 之后要立即接档名**！不要再加参数！



#### 常用

> 基本格式：tar [option]... [file]...
>
> * tar -cvf xxxx.tar xxxx	
> * tar -czvf xxxx.tar.gz xxxx
> * tar -xvf xxxx.tar
> * tar -xzvf xxxx.tar.gz 