---
title: "Linux c 编程"
collection: teaching
type: "Linux c 编程"
permalink: /teaching/2014-spring-teaching-1
venue: "Linux c 编程"
date: 2014-01-01
location: "City, Country"
---

通过学习https://edu.51cto.com/course/28903.html  
熟悉LINUX C 环境编程，对于理解php go java python node rust lua ...等语言运行在LINUX上的机制有极大帮助  
-  更好的理解和驾驭各种编程语言它们的运行机制
-  充分发挥使用strace,lstrace等工具分析各种编程语言写的程序，从而分析其运行原理，更好的驾驭编程
-  通过前2点知识，稍微举一反三，即可简单的逆向分析各种语言写的程序运行过程，从而进行开发，测试，BUG故障排查，API接口对接排查，硬件协议对接等场景
-  Linux 系统调用api的接口从1991年到今天没有怎么变（函数名，函数功能几乎没有变化）学习一次受益终身
-  strace可以用来查看系统调用的执行，使用strace php bf.php/java/golang/rust/node/lua/....，或者strace -p 进程ID。strace就可以帮助你透过现象看本质，掌握程序执行的过程。这个手段是在大型网站，大公司里最常用的。
strace其实也是对程序员基础的考验，如果没有实践过linux c 编程，肯定也达不到会用strace的程度。

   
