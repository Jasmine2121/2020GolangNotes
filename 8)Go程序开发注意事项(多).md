# Go程序开发注意事项（多）

## 语法要求

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582942712622.png)

一行写一条语句(5)

语句不用加；(他自动加的)

简洁性：(6)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582943356045.png)



## 转义字符escape char

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582943399473.png)

\表示转义

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582943585641.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582943917906.png)

```go
// \r从当前行的最前面插入开始输出，覆盖掉以前的内容
```

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582944188484.png)

**重复声明了main**（换包可以，但是main最好不要，所以新建文件夹即可）

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582944264132.png)



## Go开发常见错误和解决办法

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582944534681.png)



## Go注释(comment)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582944675645.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582945208255.png)



## 规范的代码风格要求

(1)行注释

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582945348241.png)

(2)gofmt格式化

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582945472276.png)

gofmt XX.go 不改变源码格式化，只是表面格式化

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582945778168.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582945813895.png)

输出照样符合要求（上图）



## 官方编程指南

Golang官方网站 https://golang.org/#

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582946053528.png)

见上图网址使用手册

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582946193340.png)

可以查看Golang所有包下的函数和使用



## Go语言标准库API(应用程序接口)

API： application program interface 应用程序编程接口

就是Golang的各个包的函数

例如Println就是一个API

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582946473204.png)

中文网（下图）

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582946522004.png)

里面有一系列包里面**定义的函数的源码**（下图）

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582946687795.png)

每个源文件还有里面的函数

**Golang中调用一个函数的方式：**

import包

使用包的函数

**包名.函数名**

没有写package的包就用不了

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582947115358.png)

