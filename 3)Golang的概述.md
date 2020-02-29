# Golang的概述

## 什么是程序？

 程序：完成某一个功能的指令的集合。

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852151691.png)

## 什么是指令？

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852194324.png)

## 为什么Go语言？

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852217872.png)



## Go语言发展历史

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852270624.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852668735.png)

### 为什么创造GO语言

- 多核CPU，浪费硬件优势
- 缺乏足够简洁高效的语言（现有的编程语言1.风格不统一2.计算能力不够3.处理大并发不够好）
- 同时拥有运行（编译）速度和开发速度

### 发展简史

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582852977729.png)

1.9.2 ////15年独树一帜了

## Go语言的特点

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582853156667.png)



#### 简介

- 静态编译的安全和性能（C）
- 动态语言开发维护的高效率（Python）

#### 特点

###### 1）举例：Go语言的指针怎么使用

```go
package main

func testPtr(num *int){

	*num = 20

}
```

###### 2）包的概念（每一个文件都要归属于一个包，否则不能编译）

```go
package main//一个Go文件需要在一个包

import"fmt"

func sayOK(){

	//输出一句话

	fmt.Println("OK")

}
```

###### 3）内存自动回收（更关注于逻辑本身）

###### 4）很重要！！天然并发

支持上千上万并发，so easy

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582854041964.png)

###### 5）管道通信

###### 6）函数可以返回多个值

```go
//写一个函数，实现同时返回和，差

//Go函数支持返回多个值

func getSumAndSub(n1 int, n2 int) (int, int ) {

sum := n1 + n2 //go语句后面不用带分号

sub := n1 - n2

return sum, sub

}
```

###### 7)创新

- 切片slice
- 延时执行defer
- ...



