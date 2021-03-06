# GeekTimeProgramMathBasicNotes
**记录在《极客时间》平台上《程序员的数学基础课》专栏的学习笔记**  
**作者信息：黄申 LinkedIn资深数据科学家、前IBM研究科学家、前微软亚洲研究院研究员**    
**课程海报如下：欢迎扫描海报右下方二维码订阅（有优惠哦）**  

![课程海报](./picture/math.jpg ) 

# 目录 
* [开篇词 作为程序员，为什么你应该学好数学](#0)
* [导读：程序员应该怎么学数学？](#0-1)
* [第1讲 二进制：不了解计算机的源头，你学什么编程](#1)
* [第2讲 余数：原来取余数本身就是个哈希函数](#2)
* [第3讲 迭代法：不同编程语言的自带函数，你会如何计算平方根](#3)
* [第4讲 数学归纳法：如何用数学归纳提升代码的运行效率？](#4)
* [第5讲 递归（上）：泛化数学归纳，如何将复杂问题简单化](#5)
* [第6讲 递归（下）：分而治之，从归并排序到MapReduce](#6)
* [我们为什么需要反码和补码？](#6-1)
* [位操作的三个应用实例](#6-2)
* [第7讲 排序：如何让计算机学会“田忌赛马”？](#7)
* [第8讲 组合：如何让计算机安排世界杯的赛程？](#8)
* [第9讲 动态规划（上）：如何实现基于编辑距离的查询推荐？](#9)
* [第10讲 动态规划（下）：如何求得状态转移方程并进行编程实现？](#10)
* [第11讲 树的深度优先搜索（上）：如何才能高效率地查字典？](#11)
* [第12讲 树的深度优先搜索（下）：如何才能高效率地查字典？](#12)
* [第13讲 树的广度优先搜索（上）：人际关系的六度理论是真的吗？](#13)
* [第14讲 树的广度优先搜索（下）：为什么双向广度优先搜索的效率更高](#14)
* [第15讲 从树到图：如何让计算机学会看地图](#15)
* [第16讲 时间和空间复杂度（上）：优化性能是否只是“纸上谈兵”](#16)
* [未完待续……](#99)

# 正文
<h2 id="0">开篇词 作为程序员，为什么你应该学好数学</h2>
<h2 id="0-1">导读：程序员应该怎么学数学？</h2>
<h2 id="1">第1讲 二进制：不了解计算机的源头，你学什么编程</h2>
<h2 id="2">第2讲 余数：原来取余数本身就是个哈希函数</h2>
<h2 id="3">第3讲 迭代法：不同编程语言的自带函数，你会如何计算平方根</h2>
<h2 id="4">第4讲 数学归纳法：如何用数学归纳提升代码的运行效率？</h2>
<h2 id="5">第5讲 递归（上）：泛化数学归纳，如何将复杂问题简单化</h2>
<h2 id="6">第6讲 递归（下）：分而治之，从归并排序到MapReduce</h2>
<h2 id="6-1">我们为什么需要反码和补码？</h2>
<h2 id="6-2">位操作的三个应用实例</h2>
<h2 id="7">第7讲 排序：如何让计算机学会“田忌赛马”？</h2>
<h2 id="8">第8讲 组合：如何让计算机安排世界杯的赛程？</h2>
<h2 id="9">第9讲 动态规划（上）：如何实现基于编辑距离的查询推荐？</h2>
<h2 id="10">第10讲 动态规划（下）：如何求得状态转移方程并进行编程实现？</h2>
<h2 id="11">第11讲 树的深度优先搜索（上）：如何才能高效率地查字典？</h2>
<h2 id="12">第12讲 树的深度优先搜索（下）：如何才能高效率地查字典？</h2>
<h2 id="13">第13讲 树的广度优先搜索（上）：人际关系的六度理论是真的吗？</h2>
<h2 id="14">第14讲 树的广度优先搜索（下）：为什么双向广度优先搜索的效率更高</h2>
<h2 id="15">第15讲 从树到图：如何让计算机学会看地图</h2>
<h2 id="16">第16讲 时间和空间复杂度（上）：优化性能是否只是“纸上谈兵”</h2>
<h2 id="99">未完待续……</h2>

## 觉得有价值 感谢支持
![赞赏码](./picture/AppreciationCode.jpg ) 