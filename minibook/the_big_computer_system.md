# THE BIG COMPUTER SYSTEM - A GAME CODER'S VIEW

游戏程序员眼中的计算机体系

```
+------------------------------------------------------------------------------+
|                     Software Architecture Principle(L9)                      |
+------------------------------------------------------------------------------+

+------------------------------------------------------+        +--------------+
|                Game / Game Engine(L7)                |        |              |
+------------+------------------------+----------------+ <====> |              |
|   GUI(L4)  |      Network/DB(L5)    |   2D/3D (L6)   |        | Programming  |
+------------+------------------------+----------------+ <====> |   Languages  |
|      System API(L2)       |   Compiler & Linker(L3)  |        |     (L8)     |
+------------------------------------------------------+ <====> |              |
|               Hardware/Operating System(L1)          |        |              |
+------------------------------------------------------+        +--------------+
```


## Road To the Kernel (L1/L2)

 * CPU Architecture
 * Embedded System Development
 * Kernel Developer


## Compiler & Linker & Debugger (L3)

 * My C Compiler
 * clang / llvm


## Database Demystify (L5)

 * database fundamental
 * transaction
 * sqlite
 * mysql
 * mongodb


## Network and Game Server (L5/L7)

 * TCP/IP Stack
 * libuv
 * zmq
 * Handmade Game Server


## Uncharted Waters - Big Data

 * zookeeper
 * hadoop
 * spark


## About Client - 2D/3D Game Engine (L4/L7)

 * 2d game engine
 * 3d game engine
 * UE4
 * asset producting pipeline (model editor / particle editor / world editor)


## Language Zoo (L8)

 * Assembly
 * C / C++
 * C# / Go
 * Python / Typescript


## Software Architecture Principle (L9)

重剑无锋，大巧不工。

 * [SAP01 - Actor Model][2]


## NOTE

**2018.11.26**

最近在填自己挖的坑《[Road To the Kernel][1]》，和顾QQ吹牛说：

```
从 CPU 到 OS，
从 assembler 到 compiler，
从 filesystem 到 database，
从 TCP/IP stack 到 game server，
最后再到 zookeeper/hadoop/spark。
全部撸一遍，打通整个计算机体系的任督二脉。
```

顾QQ不屑："你丫是个理想主义者。"

就理想一次吧。:-) 索性把"个人技术体系refactoring"的战线扩大。

《The Big Computer System》，我的计算机系统 hack 之路。Just for fun~


[1]:https://github.com/kasicass/blog/blob/master/minibook/road_to_the_kernel.md
[2]:https://github.com/kasicass/blog/blob/master/design-principle/2018_11_28_actor_model.md
