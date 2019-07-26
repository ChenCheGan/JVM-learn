# JVM-learn


## 1 JVM体系结构概述

### 1.1 类装载器子系统Class loader

> 负责加载class文件，class文件在文件开头有<span style="color: red">特定的文件标示</span>，将class文件字节码内容加载到内存中，并将这些内容转换成方法区中的运行时数据结构并且ClassLoader只负责class文件的加载，至于它是否可以运行，则由Execution Engine决定

这个特定的文件标示是coffee babe

### 1.2 类装载器

1. 虚拟机自带的加载器

   - 启动类加载器（Bootstrap）
   - 扩展类加载器(Extension)
   - 应用程序类加载器(AppClassLoader),也叫系统类加载器，加载当前应用到的classpath的所有类

2. 用户自定义的加载器

   java.lang.ClassLoader的子类，用户可以定制类的加载方式





