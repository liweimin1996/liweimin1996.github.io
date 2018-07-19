---
layout:     post
title:      hello,world
subtitle:   花式语言输出hello,world
date:       2018-07-16
author:     Min
header-img: img/post-bg-hello.jpg
catalog: true
tags:
    - hello,world
    - Python
    - Java
    - C++
---

## 前言

Hello,World，几乎是程序猿学习各种语言的第一个程序，如果你说你不知道hello world，我觉得你就没有必要点进来了，下面是用各种编程语言输出hello world，你都认识吗？
下面给出源码，和图片格式的源码，方便大家复制和浏览。


### 具体代码

C语言版

#include<stdlib.h>

int main()
{
    system("echo HelloWorld");
    return 0;
 }

 

c++版

#include<iostream>
using namespace std;

int main()
{
    cout<<"HelloWorld";
    return 0;
 }

java版

package initial;

public class HelloWorld {

    public static void main(String[] args) {
            System.out.println("HelloWorld");
    }

}


python版

print 'HelloWorld'

//你没看错，就是这么短一句

 

html版

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
    </head>
    <body>
        HelloWorld
    </body>
</html>
//你要是愿意的话还可以加点样式

 

pascal版

program hello;

Begin

　　writeln("HelloWorld");

　　readln;

End.

 

RuMin版

puts "HelloWorld"

//和python一样只有一句话

 

javascript版//别看他叫javascript，他和java没半毛钱关系，想想雷峰塔和雷锋

console.log("HelloWorld");

PHP版

<?

echo"HelloWorld";

?>

 

c#版

using system;

 

namespace HelloWorld

{

　　class programe

　　{

　　static void main(String[] args)

　　{

　　Console.WriteLine("HelloWorld");

　　Console.ReadKey();

}

}

}

//有没有感觉很像java

 

Go语言

package main

import "fmt"

 

func main()

{

　　  fmt.printf("HelloWorld")

}


### 总结
　以上就是各大热门语言的最简单程序，一个helloworld并不能学会一个语言，但是还是可以看出一个语言的一些结构的，有的语言以main函数作为入口，有的语言却没有，有的语言句尾有分号，有的语言没有，各个语言都有各自的优势。

　　在我看来，一个合格的程序员不一定能精通许多语言，但是他一定能够读懂许多语言，所以，希望这篇文章能够帮助你对各种语言的结构有个大概的认识。