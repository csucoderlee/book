# book项目 主要是用来记录自己学习的一些零散知识点

## Markdown的一些常用语法
- 换行 敲键盘 两下空格 + 回车
- 缩进 &ensp
- 无序列表  *空格 或者 -空格
- 有序列表 1.空格
- 引用 >
- 插入链接 []()
- 插入图片 ![]()
- 粗体与斜体 ** code **
- 代码引用 ``
- 分割线 ***




## FastJson
- fastjson为什么so fast?
- fastjson的不足

## Spring消息转换机制
> 请求报文 -> 对象 -> 响应报文	

## Spring bean注入
- 有状态的bean用prototype 无状态的bean用singleton

## 程序员必备情商
- 心态好
- 不焦虑
- 善于表达

## 程序员软实力
- 快速学习的能力
- 追踪热点技术
- 深入原理

## 经验之谈
- 调研设计-编码-测试反馈修订 5-3-2
- 再好的设计，也要看是什么人来编码实现，想保证自己所设计系统的稳定和性能有很多必不可少的步骤比如code review
- 产品的需求一定要细化，最好细化，边细化边写伪代码

## java
- javadoc 生成文档API

## 服务器问题排查
- top -c
- top -Hp
- jstack -pid > temp.txt

## 最近安排
看完《大型网站系统与Java中间件实践》

## 笔记太多太乱怎么办 ？
试试定期归档

## java 核心技术
- java是解释执行吗？
	java 是在编译期，将代码编译为字节码(bytecode)，而不是像C/C++那样直接编译为机器码，字节码和JVM是跨平台的基础，Write once, run anywhere。
	但是解释执行这句话不太准确，编写完代码，javac编译为字节码，然后，JVM会通过内嵌的解释器将字节码转换为机器码，但是，大多数的JVM，都有JIT，即时编译器，可以直接编译热点代码为机器码，这部分代码就是编译执行的了。

## ubuntu
- 搞了新版本18.04


## 工程目录结构

### ./flink  该目录下是flink的学习笔记

#### ./flink/book  该文件夹下的内容是相关的flink书籍的读书笔记

##### MasteringApacheFlink 文件夹
此文件夹下的内容是 Mastering Apache Flink一书的相关内容
- Mastering Apache Flink
- 作者: Tanmay Deshpande 
- 出版社: Packt Publishing - ebooks Account 
- 出版年: 2017-3-6