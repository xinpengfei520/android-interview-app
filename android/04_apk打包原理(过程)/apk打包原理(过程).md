# apk打包原理(过程)

1.将 xml 资源文件和清单文件进行编译和处理；

2.将 Java 源代码编译成 .class 文件，然后将多个 .class 文件压缩成 .dex 文件；

3.将上面两部分合并成 apk ，然后才可以安装和运行；