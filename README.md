[![PyPi Version](https://img.shields.io/pypi/v/mmdnn.svg)](https://pypi.org/project/mmdnn/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Linux](https://travis-ci.org/Microsoft/MMdnn.svg?branch=master)](https://travis-ci.org/Microsoft/MMdnn)
![Language](https://img.shields.io/badge/language-c++-brightgreen)

# 写在前面
>距离我提交该面试总结已经一年了，当初的想法就是能帮助更多的人去成体系的了解C++，有更多的朋友能够找到其中的错误并且改正。
虽然当初工作是朝着C++方向找的，但是事与愿违，最后去学了C#这门语言，俗话说的好：“学C++是理想，写C#是生活”，不过我还会抽空修改更正，希望该面试总结能帮助到更多的人！

看过市面上很多面经的总结，不论是github上上千star的或者是公众号上的，给我的感觉就是既没有深度也没有广度，仅仅是解释一个概念。如果面试官细问下去，而你仅仅是了解这个概念，很容易就gg了。所以我希望自己总结的这些，当大家看到后都能够发散和思考，找到自己的技术方向和知识框架体系。如有解释不深入的地方，希望每个人都可以自己顺着相关概念查下去，形成自己的一套知识体系。
时间精力有限有很多知识都没有涉及，希望大家谅解！

**提示tip：** 所有文章都用的是markdown编写，所以为了方便阅读可以直接下载一个typora（一个简洁的mk阅读和编辑器）。如果直接在网页上阅读的话，可以借助大纲功能来看，这样条理脉络都比较清晰

<hr>

# :notebook:C++后台开发方向的面经总结:black_nib: 
## [:memo:**C++**](https://github.com/guaguaupup/cpp_interview/blob/main/C%2B%2B.md)</br>
主要包含三部分内容。第一部分是c++和部分c相关的语言特性，针对这些特性和易错点都做了整理和发散。第二部分是STL知识，一些会被问到的问题的总结，源码的分析等等。第三部分是c++轮子部分，例如线程池、内存池这种写一个工具demo的问题也会被问到。本人2022暑期实习的时候被问到的最多的就是“写一个智能指针类”。

## [:memo:**Linux服务器**](https://github.com/guaguaupup/cpp_interview/blob/main/linux%E6%9C%8D%E5%8A%A1%E5%99%A8.md)</br>
这块会混合这操作系统的一部分内容，因为linux本身就是一种OS，所以范围限制的不是很死。这块很多东西都是服务器开发相关的知识，当然并不全是，还有一些linux系统相关的特性总结。

## [:memo:**操作系统**](https://github.com/guaguaupup/cpp_interview/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md)</br>
操作系统有关的知识点，进程线程、分页分表、死锁、线程调度机制等等都问的很多

## [:memo:**计算机网络**](https://github.com/guaguaupup/cpp_interview/blob/main/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md)</br>
TCP/IP协议栈是重点，一般面试官会问的比如：说一下TCP为什么可靠，这个时候需要成体系的说，此外就是应用层的很重要的http协议。协议的细节肯定不好记住，但是多看反复的看就会好很多。

## [:memo:**数据库**](https://github.com/guaguaupup/cpp_interview/blob/main/%E6%95%B0%E6%8D%AE%E5%BA%93.md)</br>
搞c++的基本很少跟数据库打交道，但是美团阿里用java的大厂都很喜欢问数据库，本人曾被问数据库问了一个小时。。。
该部分包含mysql和redis两大块，日后还需要更新索引优化相关的知识点。

## [:memo:**数据结构算法**](https://github.com/guaguaupup/cpp_interview/blob/main/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E5%8F%8A%E7%AE%97%E6%B3%95.md)</br>
不多说了，必背必备知识。

## [:memo:**手撕代码**](https://github.com/guaguaupup/cpp_interview/blob/main/%E6%89%8B%E6%92%95%E4%BB%A3%E7%A0%81.md)</br>
抽了一些会被经常问到的知识点的代码，经常会手撕，所以把这部分代码重新集合到一起看一些。我面试前就经常看，效果很好，基本都会问到而且很快都写出来了。

## [:memo:**离谱问题**](https://github.com/guaguaupup/cpp_interview/blob/main/%E7%A6%BB%E8%B0%B1%E9%97%AE%E9%A2%98.md)</br>
离谱问题、逆天问题都可，就是一些很发散的题目，刚开始肯定很没头绪，但是这些题目都是在面经中总结碰到的，看一看没坏处~

## [:memo:**设计模式**](https://github.com/guaguaupup/cpp_interview/blob/main/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md)</br>
现在越来越卷，刚找工作的小萌新都需要会设计模式了（话说这不是大牛才需要考虑的东西吗？）

## [:memo:**其他技术栈**](https://github.com/guaguaupup/cpp_interview/blob/main/%E5%85%B6%E4%BB%96%E6%8A%80%E6%9C%AF%E6%A0%88.md)</br>
辅助开发的工具类，云服务、协、嵌入式、python等广泛的技术热点！

<hr>

# :bookmark_tabs:书籍笔记总结
> 将看过的部分书的重要的知识点做了总结， 定时翻看可以对整本书的体系结构有一个比较清晰的认识。
## [:memo:**操作系统**](https://github.com/guaguaupup/cpp_interview/blob/main/%E4%B9%A6%E7%B1%8D%E7%AC%94%E8%AE%B0/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md)</br>
总结自电子工业出版社的现代操作系统

## [:memo:**c++ primer plus**](https://github.com/guaguaupup/cpp_interview/blob/main/%E4%B9%A6%E7%B1%8D%E7%AC%94%E8%AE%B0/c%2B%2B%E8%AF%AD%E8%A8%80%E6%A0%B8%E5%BF%83%E5%8F%8A%E8%BF%9B%E9%98%B6.md)</br>
那一本很厚的白色c++书，我都给翻成黑色的了

## [:memo:**高性能服务器**](https://github.com/guaguaupup/cpp_interview/blob/main/%E4%B9%A6%E7%B1%8D%E7%AC%94%E8%AE%B0/linux%E9%AB%98%E6%80%A7%E8%83%BD%E6%9C%8D%E5%8A%A1%E5%99%A8.md)</br>
游双老师的那一本

## [:memo:**汇编语言**](https://github.com/guaguaupup/cpp_interview/blob/main/%E4%B9%A6%E7%B1%8D%E7%AC%94%E8%AE%B0/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80.md)</br>
一些简单的汇编概念知识

<hr>

# :bookmark_tabs:刷题
## [连接在这里](https://github.com/guaguaupup/cpp_interview/blob/main/leetcode%E5%88%B7%E9%A2%98.md)
包含leetcode各种类型约300道，leetcode热题100， 牛客前100，剑指offer
