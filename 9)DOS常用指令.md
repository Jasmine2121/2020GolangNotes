# DOS常用指令

DOS： Disk Operating System 磁盘操作系统

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582947142667.png)

## DOS操作基本原理

原理：

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582967771150.png)

## 常用指令

https://blog.csdn.net/qq_37131111/article/details/82079083



### 目录操作

- **绝对路径：从当前盘符的最上面开始定位**
- **相对路径：从当前位置定位，去找对应的目录**

1） dir–显示指定路径上所有文件或目录的信息
它的格式为”dir [盘符：][路径][文件名] [参数]”，比如”DIR E:\FF.M3U”。

2） md(mkdir)–建立目录
它的格式为”md [盘符][路径]”，例如”MD TEMP”。**可以多个，空格键**隔开就行

3） rd(rmdir)–删除目录
格式为”RD [盘符][路径]”。
注意：该命令只能删除**空目录**，并且不能删除当前目录。

不带询问删：![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582968534882.png)

**/q/s**

**/s 带询问**

4） cd–进入指定目录
格式为” CD [路径]”，例如”CD HAPPY”。
注意：只能进入当前盘符中的目录。其中”CD\”为**回到根目录**，”CD..”为回到上一层目录。

5） copy–拷贝文件
格式为”COPY [源目录或文件] [目的目录或文件]”，比如”COPY C:*.COM D:\”
注意：使用该命令进行文件拷贝时，**目的目录一定要存在**。

6） del–删除文件
格式为”DEL [盘符][路径][文件名] [参数]”，比如”DEL C:\DATA*.BAK”。**它有一个参数：”/P”**，可以使用户在删除多个文件时对每个文件都显示删除询问

7） ren(rename)–改名
格式为”REN [原名] [现名]”，7.0以后版本的DOS都支持对**文件名和目录名的修改**，而以前的DOS只能修改文件名。

8） type–显示文本文件
格式为”TYPE [文件名]”，能对**文本文件进行查看**。

9) discopy–磁盘复制

[功能] 复制出一个和原来**磁盘内容一模一样**的磁盘

[格式] diskcopy　源驱动器名　目的驱动器名

[说明] 它的主要用途就是**用来备份**。

10) deltree–删除目录树

[格式] [C:][path]DELTREE [C1:][path1] [[C2:][path2] […]]

[说明] 这个命令将整个指定目录树全部消灭，而**不管它是否是只读、隐藏与否**。

11) mem–查看你的计算机内存有多少，以及内存的使用情况。

[格式] mem

12) **chkdsk–检查你的磁盘的使用情况**。

[格式] chkdsk　磁盘名

[说明] 例如要检查A盘使用情况，就输入chkdsk　A: ，检查c盘使用情况，就输入chkdsk　C: ，如果直接输入chkdsk，就检查**当前磁盘**的使用情况。

### 文件操作

- cd dir : 切换目录
- cd … : 返回上级目录
- cd / : 返回根目录
- cls ； 清屏
- pause : 暂停

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582968747606.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582968825629.png)

echo创建文件

copy拷贝文件 使用原文件名

move移动文件![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582969004179.png)

del 删除文件

删除全部文件![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582969082997.png)

tab键补全

### 其他指令

- cls清屏
- exit退出



![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582969186072.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582969235160.png)

![](https://raw.githubusercontent.com/Jasmine2121/images/master/1582969247677.png)

da6dfc4e229978c673a9f29936fcb2dca10cc48a（图床）