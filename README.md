# Big-Data-Interview
大数据面试知识点，多为网上公开资料，留以自用。
## 目录
- [Java基础篇](#Java基础篇)
    - [语言基础](#语言基础)
    - [锁](#锁)
    - [多线程](#多线程)
    - [并发容器](#并发容器)
- [JVM](#JVM)
    - [JVM内存结构](#JVM内存结构)
    - [堆和栈区别](#堆和栈区别)
    - [Java内存模型](#Java内存模型)
    - [垃圾回收](#垃圾回收)
    - [Java对象模型](#Java对象模型)
    - [HotSpot](#HotSpot)
    - [虚拟机性能监控与故障处理工具](#虚拟机性能监控与故障处理工具)
    - [类加载机制](#类加载机制)
- [Linux、IO](#Linux、IO)
    - [Linux基础](#Linux基础)
    - [IO](#IO)
- [分布式](#分布式)
    - [分布式理论](#分布式理论)
- [数据结构与算法](#数据结构与算法)
- [Redis](#Redis)
    - [Redis基础](#Redis基础)
    - [redis内部数据结构](#redis内部数据结构)
- [Git](#Git)
- [操作系统](#操作系统)
- [数据库](#数据库)
- [Meavn](#Meavn)
- [HBase](#HBase)
- [Hive](#Hive)
- [Spark](#Spark)
- [面试](#面试)
    - [计算机网络](#计算机网络)
    - [Spring](#Spring)
    - [Redis](#Redis)
    - [Elasticsearch](#Elasticsearch)
    - [分布式](#分布式环境)
    - [JVM](#JVM面试)
    - [设计模式](#设计模式)
    - [多线程](#多线程面试)
    - [JDK](#JDK)
    - [数据结构](#数据结构)
    - [编程](#编程)
 - [实习小记](#实习小记) 
 - [源码](#源码)
    - [MyBatis](#MyBatis)

## Java基础篇
### 语言基础
* #### [Java的面向对象](1.%20Java基础篇/1.%20语言基础/1.%20Java的面向对象.md)
* #### [Java语言的三大特征：封装、继承和多态](1.%20Java基础篇/1.%20语言基础/2.%20Java语言的三大特征：封装、继承和多态.md)
* #### [Java语言数据类型](1.%20Java基础篇/1.%20语言基础/3.%20Java语言数据类型.md)
* #### [Java的自动类型转换，强制类型转换](1.%20Java基础篇/1.%20语言基础/4.%20Java的自动类型转换，强制类型转换.md)
* #### [String的不可变性、虚拟机的常量池中的String字符串、String.intern()的底层原理](1.%20Java基础篇/1.%20语言基础/5.%20String的不可变性、虚拟机的常量池中的String字符串、String.intern()的底层原理.md)
* #### [Java语言中的关键字：final](1.%20Java基础篇/1.%20语言基础/6.%20Java语言中的关键字：final.md)
* #### [Java语言中的关键字：static](1.%20Java基础篇/1.%20语言基础/7.%20Java语言中的关键字：static.md)
* #### [Java语言中的关键字：transient](1.%20Java基础篇/1.%20语言基础/8.%20Java语言中的关键字：transient.md)
* #### [Java语言中的关键字：instanceof](1.%20Java基础篇/1.%20语言基础/9.%20Java语言中的关键字：instanceof.md)
* #### [Java语言中的关键字：volatile](1.%20Java基础篇/1.%20语言基础/10.%20Java语言中的关键字：volatile.md)
* #### [Java语言中的关键字：synchronized](1.%20Java基础篇/1.%20语言基础/11.%20Java语言中的关键字：synchronized.md)
* #### [Java中常用的集合类：ArrayList](1.%20Java基础篇/1.%20语言基础/12.%20Java中常用的集合类：ArrayList.md)
* #### [Java中常用的集合类：LinkedList](1.%20Java基础篇/1.%20语言基础/13.%20Java中常用的集合类：LinkedList.md)
* #### [Java中常用的集合类：SynchronizedList](1.%20Java基础篇/1.%20语言基础/14.%20Java中常用的集合类：SynchronizedList.md)
* #### [Java中常用的集合类：HashMap](1.%20Java基础篇/1.%20语言基础/15.%20Java中常用的集合类：HashMap.md)
* #### [Java中常用的集合类：Hashtable](1.%20Java基础篇/1.%20语言基础/16.%20Java中常用的集合类：Hashtable.md)
* #### [Java中常用的集合类：ConcurrentHashMap](1.%20Java基础篇/1.%20语言基础/17.%20Java中常用的集合类：ConcurrentHashMap.md)
* #### [动态代理的实现方式](1.%20Java基础篇/1.%20语言基础/18.%20动态代理的实现方式.md)
* #### [动态代理详解](1.%20Java基础篇/1.%20语言基础/19.%20动态代理详解.md)
* #### [泛型](1.%20Java基础篇/1.%20语言基础/20.%20泛型.md)
### 锁
* #### [CAS](1.%20Java基础篇/2.%20锁/1.%20CAS.md)
* #### [乐观锁与悲观锁](1.%20Java基础篇/2.%20锁/2.%20乐观锁与悲观锁.md)
* #### [分布式锁](1.%20Java基础篇/2.%20锁/3.%20分布式锁.md)
* #### [偏向锁](1.%20Java基础篇/2.%20锁/4.%20偏向锁.md)
* #### [轻量级锁](1.%20Java基础篇/2.%20锁/5.%20轻量级锁.md)
* #### [monitor](1.%20Java基础篇/2.%20锁/6.%20monitor.md)
* #### [锁消除和锁粗化](1.%20Java基础篇/2.%20锁/7.%20锁消除和锁粗化.md)
* #### [自旋锁](1.%20Java基础篇/2.%20锁/8.%20自旋锁.md)
* #### [可重入锁](1.%20Java基础篇/2.%20锁/9.%20可重入锁.md)
* #### [阻塞锁](1.%20Java基础篇/2.%20锁/10.%20阻塞锁.md)
* #### [死锁](1.%20Java基础篇/2.%20锁/11.%20死锁.md)
* #### [CountDownLatch](1.%20Java基础篇/2.%20锁/12.%20CountDownLatch.md)
* #### [CyclicBarrier](1.%20Java基础篇/2.%20锁/13.%20CyclicBarrier.md)
* #### [Semaphore](1.%20Java基础篇/2.%20锁/14.%20Semaphore.md)
### 多线程
* #### [并发和并行的区别、进程与线程的区别](1.%20Java基础篇/3.%20多线程/1.%20并发和并行的区别、进程与线程的区别.md)
* #### [线程的实现](1.%20Java基础篇/3.%20多线程/2.%20线程的实现.md)
* #### [线程的状态](1.%20Java基础篇/3.%20多线程/3.%20线程的状态.md)
* #### [线程的优先级](1.%20Java基础篇/3.%20多线程/4.%20线程的优先级.md)
* #### [线程调度](1.%20Java基础篇/3.%20多线程/5.%20线程调度.md)
* #### [守护线程](1.%20Java基础篇/3.%20多线程/6.%20守护线程.md)
* #### [自己设计线程池](1.%20Java基础篇/3.%20多线程/7.%20自己设计线程池.md)
* #### [submit()和execute()](1.%20Java基础篇/3.%20多线程/8.%20submit()和execute().md)
* #### [线程池原理](1.%20Java基础篇/3.%20多线程/9.%20线程池原理.md)
* #### [为什么不允许使用Executors创建线程池](1.%20Java基础篇/3.%20多线程/10.%20为什么不允许使用Executors创建线程池.md)
* #### [ThreadLocal变量](1.%20Java基础篇/3.%20多线程/11.%20ThreadLocal变量.md)
* #### [ThreadPoolExecutor创建线程池](1.%20Java基础篇/3.%20多线程/12.%20ThreadPoolExecutor创建线程池.md)
* #### [线程池关闭的方式](1.%20Java基础篇/3.%20多线程/13.%20线程池关闭的方式.md)
### 并发容器
* #### [CopyOnWriteArrayList](1.%20Java基础篇/4.%20并发容器/1.%20CopyOnWriteArrayList.md)
* #### [CopyOnWriteArraySet](1.%20Java基础篇/4.%20并发容器/2.%20CopyOnWriteArraySet.md)
* #### [ConcurrentSkipListSet](1.%20Java基础篇/4.%20并发容器/3.%20ConcurrentSkipListSet.md)
* #### [ConcurrentSkipListMap](1.%20Java基础篇/4.%20并发容器/4.%20ConcurrentSkipListMap.md)
* #### [ConcurrentLinkedQueue](1.%20Java基础篇/4.%20并发容器/5.%20ConcurrentLinkedQueue.md)
* #### [ConcurrentLinkedDeque](1.%20Java基础篇/4.%20并发容器/6.%20ConcurrentLinkedDeque.md)
* #### [ArrayBlockingQueue](1.%20Java基础篇/4.%20并发容器/7.%20ArrayBlockingQueue.md)
* #### [LinkedBlockingQueue](1.%20Java基础篇/4.%20并发容器/8.%20LinkedBlockingQueue.md)
* #### [LinkedBlockingDeque](1.%20Java基础篇/4.%20并发容器/9.%20LinkedBlockingDeque.md)
## JVM
### JVM内存结构
* #### [class文件格式](2.%20JVM/1.%20JVM内存结构/1.%20class文件格式.md)
* #### [运行时数据区：堆、栈、方法区](2.%20JVM/1.%20JVM内存结构/2.%20运行时数据区：堆、栈、方法区.md)
* #### [直接内存](2.%20JVM/1.%20JVM内存结构/3.%20直接内存.md)
* #### [运行时常量池](2.%20JVM/1.%20JVM内存结构/4.%20运行时常量池.md)
### 堆和栈区别
* #### [Java中的对象一定在堆上分配吗？](2.%20JVM/2.%20堆和栈区别/1.%20Java中的对象一定在堆上分配吗？.md)
### Java内存模型
* #### [Java内存模型与硬件内存架构关系](2.%20JVM/3.%20Java内存模型/1.%20Java内存模型与硬件内存架构关系.md)
* #### [缓存一致性](2.%20JVM/3.%20Java内存模型/2.%20缓存一致性.md)
* #### [可见性、原子性、顺序性（有序性）](2.%20JVM/3.%20Java内存模型/3.%20可见性、原子性、顺序性（有序性）.md)
* #### [内存屏障](2.%20JVM/3.%20Java内存模型/4.%20内存屏障.md)
* #### [final](2.%20JVM/3.%20Java内存模型/5.%20final.md)
### 垃圾回收
* #### [标记清除](2.%20JVM/4.%20垃圾回收/1.%20标记清除.md)
* #### [引用计数](2.%20JVM/4.%20垃圾回收/2.%20引用计数.md)
* #### [复制算法](2.%20JVM/4.%20垃圾回收/3.%20复制算法.md)
* #### [标记压缩](2.%20JVM/4.%20垃圾回收/4.%20标记压缩.md)
* #### [分代回收](2.%20JVM/4.%20垃圾回收/5.%20分代回收.md)
* #### [增量式回收](2.%20JVM/4.%20垃圾回收/6.%20增量式回收.md)
* #### [GC参数](2.%20JVM/4.%20垃圾回收/7.%20GC参数.md)
* #### [对象存活的判定](2.%20JVM/4.%20垃圾回收/8.%20对象存活的判定.md)
* #### [垃圾收集器](2.%20JVM/4.%20垃圾回收/9.%20垃圾收集器.md)
### Java对象模型
* #### [oop-klass](2.%20JVM/5.%20Java对象模型/1.%20oop-klass.md)
* #### [对象头](2.%20JVM/5.%20Java对象模型/2.%20对象头.md)
### HotSpot
* #### [即时编译器](2.%20JVM/6.%20HotSpot/1.%20即时编译器.md)
* #### [编译优化](2.%20JVM/6.%20HotSpot/2.%20编译优化.md)
* #### [HotSpot的启动](2.%20JVM/6.%20HotSpot/3.%20HotSpot的启动.md)
* #### [类加载机制流程](2.%20JVM/6.%20HotSpot/4.%20类加载机制流程.md)
* #### [JVM源码分析之Java类加载过程](2.%20JVM/6.%20HotSpot/5.%20JVM源码分析之Java类加载过程.md)
* #### [HotSpotVM对象机制实现浅析](2.%20JVM/6.%20HotSpot/6.%20HotSpotVM%20对象机制实现浅析.md)
* #### [JVM源码分析之Java对象的创建过程](2.%20JVM/6.%20HotSpot/7.%20JVM源码分析之Java对象的创建过程.md)
* #### [JVM内存布局](2.%20JVM/6.%20HotSpot/8.%20JVM内存布局.md)
### 虚拟机性能监控与故障处理工具
* #### [jps、jstack、jmap、jstat、jconsole、jinfo、jhat](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/1.%20jps、jstack、jmap、jstat、jconsole、jinfo、jhat.md)
* #### [javap](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/2.%20javap.md)
* #### [btrace](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/3.%20btrace.md)
* #### [TProfiler](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/4.%20TProfiler.md)
* #### [Arthas](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/5.%20Arthas.md)
* #### [JVM的GC日志详解](2.%20JVM/7.%20虚拟机性能监控与故障处理工具/6.%20JVM的GC日志详解.md)
### 类加载机制
* #### [classLoader](2.%20JVM/8.%20类加载机制/1.%20classLoader.md)
* #### [类加载过程](2.%20JVM/8.%20类加载机制/2.%20类加载过程.md)
* #### [双亲委派（破坏双亲委派）](2.%20JVM/8.%20类加载机制/3.%20双亲委派（破坏双亲委派）.md)
* #### [模块化_jboss_modules](2.%20JVM/8.%20类加载机制/4.%20模块化_jboss_modules.md)
* #### [模块化_osgi](2.%20JVM/8.%20类加载机制/5.%20模块化_osgi.md)
* #### [模块化_jigsaw](2.%20JVM/8.%20类加载机制/6.%20模块化_jigsaw.md)
## Linux、IO
### Linux基础
* #### [Linux的常用命令](3.%20Linux、IO/1.%20Linux基础/1.%20Linux的常用命令.md)
* #### [远程登录](3.%20Linux、IO/1.%20Linux基础/2.%20远程登录.md)
* #### [系统目录](3.%20Linux、IO/1.%20Linux基础/3.%20系统目录.md)
* #### [文件和目录操作](3.%20Linux、IO/1.%20Linux基础/4.%20文件和目录操作.md)
* #### [Linux下的权限体系](3.%20Linux、IO/1.%20Linux基础/5.%20Linux下的权限体系.md)
* #### [压缩和打包](3.%20Linux、IO/1.%20Linux基础/6.%20压缩和打包.md)
* #### [Shell脚本的编写](3.%20Linux、IO/1.%20Linux基础/7.%20Shell脚本的编写.md)
* #### [管道操作](3.%20Linux、IO/1.%20Linux基础/8.%20管道操作.md)
* #### [理解Linux的进程，线程，PID，LWP，TID，TGID](3.%20Linux、IO/1.%20Linux基础/9.%20理解Linux的进程，线程，PID，LWP，TID，TGID.md)
### IO
* #### [用户空间以及内核空间](3.%20Linux、IO/2.%20IO/1.%20用户空间以及内核空间.md)
* #### [阻塞、非阻塞、信号驱动式、同步、异步IO](3.%20Linux、IO/2.%20IO/2.%20阻塞、非阻塞、信号驱动式、同步、异步IO.md)
* #### [零拷贝（ZeroCopy）](3.%20Linux、IO/2.%20IO/3.%20零拷贝（ZeroCopy）.md)
* #### [BIO、NIO、AIO](3.%20Linux、IO/2.%20IO/4.%20BIO、NIO、AIO.md)
* #### [缓冲区Buffer](3.%20Linux、IO/2.%20IO/5.%20缓冲区Buffer.md)
* #### [通道Channel](3.%20Linux、IO/2.%20IO/6.%20通道Channel.md)
* #### [反应堆（Reactor）](3.%20Linux、IO/2.%20IO/7.%20反应堆（Reactor）.md)
* #### [选择器（Selector）](3.%20Linux、IO/2.%20IO/8.%20选择器（Selector）.md)
* #### [AIO](3.%20Linux、IO/2.%20IO/9.%20AIO.md)
## 分布式
### 分布式理论
* #### [分布式中的一些基本概念](4.%20分布式/1.%20分布式理论/1.%20分布式系统的一些基本概念.md)
* #### [分布式系统理论基础：一致性、2PC和3PC](4.%20分布式/1.%20分布式理论/2.%20分布式系统理论基础：一致性、2PC和3PC.md)
* #### [分布式系统理论基础：时间、时钟和事件顺序](4.%20分布式/1.%20分布式理论/3.%20分布式系统理论基础：时间、时钟和事件顺序.md)
* #### [分布式系统理论进阶：Paxos](4.%20分布式/1.%20分布式理论/4.%20分布式系统理论进阶：Paxos.md)
* #### [分布式系统理论进阶：Raft、Zab](4.%20分布式/1.%20分布式理论/5.%20分布式系统理论进阶：Raft、Zab.md)
* #### [分布式系统理论进阶：选举、多数派和租约](4.%20分布式/1.%20分布式理论/6.%20分布式系统理论进阶：选举、多数派和租约.md)
* #### [分布式锁的解决方案](4.%20分布式/1.%20分布式理论/7.%20分布式锁的解决方案.md)
## 数据结构与算法
* #### [背包九讲——Java详解](5.%20数据结构与算法/1.%20背包九讲——Java详解.md)
## Redis
### Redis基础
* #### [缓存异常问题](6.%20Redis/Redis基础/0.%20缓存异常问题.md)
* #### [什么是Redis](6.%20Redis/Redis基础/1.%20什么是Redis.md)
* #### [Redis功能一览](6.%20Redis/Redis基础/2.%20Redis功能一览.md)
* #### [访问 Redis 中的海量数据—scan](6.%20Redis/Redis基础/3.%20访问%20Redis%20中的海量数据—scan.md)
* #### [Redis 事务](6.%20Redis/Redis基础/4.%20Redis%20事务.md)
* #### [Redis中的事件驱动模型](6.%20Redis/Redis基础/5.%20Redis%20中的事件驱动模型.md)
* #### [Redis主从复制](6.%20Redis/Redis基础/6.%20Redis主从复制.md)
* #### [Redis内存淘汰](6.%20Redis/Redis基础/7.%20Redis内存淘汰.md)
* #### [Redis缓存模式](6.%20Redis/Redis基础/8.%20Redis缓存模式.md)
* #### [Redis命令的执行过程](6.%20Redis/Redis基础/9.%20Redis命令的执行过程.md)
* #### [Redis事务浅析与ACID特性介绍](6.%20Redis/Redis基础/10.%20Redis事务浅析与ACID特性介绍.md)
* #### [Redis如何处理客户端连接](6.%20Redis/Redis基础/11.%20Redis如何处理客户端连接.md)
* #### [浅析Redis主从复制](6.%20Redis/Redis基础/12.%20浅析Redis主从复制.md)
* #### [使用快照和AOF将Redis数据持久化到硬盘中](6.%20Redis/Redis基础/13.%20使用快照和AOF将Redis数据持久化到硬盘中.md)
* #### [数据库redisDb与键过期删除策略](6.%20Redis/Redis基础/14.%20数据库redisDb与键过期删除策略.md)
* #### [Redis分布式锁](6.%20Redis/Redis基础/16.%20Redis%20分布式锁.md)
* #### [Redis分布式锁进化史](6.%20Redis/Redis基础/17.%20Redis分布式锁进化史.md)
* #### [Redis面试常见问题](6.%20Redis/Redis基础/18.%20Redis面试常见问题.md)
* #### [Redis高并发](6.%20Redis/Redis基础/19.%20Redis高并发.md)
### redis内部数据结构
* #### [Redis的基础数据结构概览](6.%20Redis/redis内部数据结构/Redis%20的基础数据结构概览.md)
* #### [探索Redis设计与实现2：Redis内部数据结构详解——dict](6.%20Redis/redis内部数据结构/探索Redis设计与实现2：Redis内部数据结构详解——dict.md)
* #### [探索Redis设计与实现3：Redis内部数据结构详解——sds](6.%20Redis/redis内部数据结构/探索Redis设计与实现3：Redis内部数据结构详解——sds.md)
* #### [探索Redis设计与实现4：Redis内部数据结构详解——ziplist](6.%20Redis/redis内部数据结构/探索Redis设计与实现4：Redis内部数据结构详解——ziplist.md)
* #### [探索Redis设计与实现5：Redis内部数据结构详解——quicklist](6.%20Redis/redis内部数据结构/探索Redis设计与实现5：Redis内部数据结构详解——quicklist.md)
* #### [探索Redis设计与实现6：Redis内部数据结构详解——skiplist](6.%20Redis/redis内部数据结构/探索Redis设计与实现6：Redis内部数据结构详解——skiplist.md)
* #### [探索Redis设计与实现7：Redis内部数据结构详解——intset](6.%20Redis/redis内部数据结构/探索Redis设计与实现7：Redis内部数据结构详解——intset.md)
## Git
* #### [合并](7.%20Git/1、合并.md)
* #### [git回退](7.%20Git/3、git回退.md)
* #### [git stash](7.%20Git/4、git%20stash.md)
* #### [Git忽略文件.gitignore的使用](7.%20Git/6、Git忽略文件.gitignore的使用.md)
## 操作系统
* #### [虚拟内存](8.%20操作系统/1、虚拟内存.md)
* #### [进程虚拟地址空间的区域划分](8.%20操作系统/2、进程虚拟地址空间的区域划分.md)
* #### [Linux进程的创建与管理](8.%20操作系统/3、Linux进程的创建与管理.md)
* #### [Linux内核内存管理算法Buddy和Slab](8.%20操作系统/4、Linux内核内存管理算法Buddy和Slab.md)
* #### [Linux线程](8.%20操作系统/5、Linux线程.md)
* #### [PCB控制块](8.%20操作系统/6、PCB控制块.md)
* #### [页表](8.%20操作系统/7、页表.md)
* #### [写时拷贝](8.%20操作系统/8、写时拷贝.md)
* #### [Unicode字符编码](8.%20操作系统/9.%20Unicode字符编码.md)
## 数据库
* #### [Hive group by操作](9.%20数据库/1、Hive%20group%20by操作.md)
* #### [MySql执行计划explain](9.%20数据库/2、MySql执行计划explain.md)
* #### [聚合函数](9.%20数据库/3、聚合函数.md)
* #### [groupby函数](9.%20数据库/4、groupby函数.md)
* #### [笛卡尔积](9.%20数据库/5、笛卡尔积.md)
* #### [索引使用](9.%20数据库/6、索引使用.md)
* #### [数据库底层](9.%20数据库/8、数据库底层.md)
* #### [索引分类](9.%20数据库/9、索引分类.md)
* #### [join](9.%20数据库/10、join.md)
* #### [change buffer架构](9.%20数据库/11、change%20buffer架构.md)
* #### [InnoDB体系架构详解](9.%20数据库/12、InnoDB体系架构详解.md)
## Meavn
* #### [meavn插件](10.%20Meavn/2、meavn插件.md)
## HBase
* #### [Hbase简介](11.%20HBase/1.%20Hbase简介.md)
* #### [Hbase系统架构及数据结构](11.%20HBase/2.%20Hbase系统架构及数据结构.md)
* #### [Hbase定位](11.%20HBase/3.%20Hbase定位.md)
* #### [Hbase_Shell](11.%20HBase/4.%20Hbase_Shell.md)
* #### [Hbase API的使用](11.%20HBase/5.%20Hbase%20API%20的使用.md)
* #### [Hbase_Java_API](11.%20HBase/6.%20Hbase_Java_API.md)
* #### [Hbase的SQL中间层-Phoenix](11.%20HBase/7.%20Hbase的SQL中间层-Phoenix.md)
* #### [Hbase过滤器详解](11.%20HBase/8.%20Hbase过滤器详解.md)
* #### [Hbase如何设计rowkey](11.%20HBase/9.%20Hbase如何设计rowkey.md)
* #### [HBase冷热分离](11.%20HBase/10.%20HBase冷热分离.md)
* #### [Hbase容灾与备份](11.%20HBase/11.%20Hbase容灾与备份.md)
* #### [Hbase协处理器详解](11.%20HBase/12.%20Hbase协处理器详解.md)
## Hive
* #### [Hive简介及核心概念](12.%20Hive/1.%20Hive简介及核心概念.md)
* #### [Hive的数据存储—表](12.%20Hive/2.%20Hive的数据存储—表.md)
* #### [Hive分区表和分桶表](12.%20Hive/3.%20Hive分区表和分桶表.md)
* #### [Hive视图和索引](12.%20Hive/4.%20Hive视图和索引.md)
* #### [Hive数据查询详解](12.%20Hive/5.%20Hive数据查询详解.md)
* #### [Hive适用场景](12.%20Hive/6.%20Hive适用场景.md)
* #### [Hive常用DDL操作](12.%20Hive/7.%20Hive常用DDL操作.md)
* #### [Hive常用DML操作](12.%20Hive/8.%20Hive常用DML操作.md)
* #### [HiveCLI和Beeline命令行的基本使用](12.%20Hive/9.%20HiveCLI和Beeline命令行的基本使用.md)
* #### [Hive之Java API](12.%20Hive/10.%20Hive%20之%20Java%20API.md)
* #### [HiveToMR](12.%20Hive/11.%20HiveToMR.md)
* #### [Impala和hive的查询有哪些区别](12.%20Hive/12.%20Impala和hive的查询有哪些区别.md)
* #### [调优1](12.%20Hive/13.%20调优1.md)
* #### [调优2](12.%20Hive/14.%20调优2.md)
## Spark
* #### [spark基本概念](13.%20Spark/1、spark基本概念.md)
* #### [spark宽依赖与窄依赖](13.%20Spark/2、spark宽依赖与窄依赖.md)
* #### [spark分区策略](13.%20Spark/3、spark分区策略.md)
* #### [reduceByKey和groupByKey](13.%20Spark/4、reduceByKey和groupByKey.md)
* #### [Spark通信机制](13.%20Spark/6、Spark通信机制.md)
* #### [Driver、Master、Worker](13.%20Spark/7、Driver、Master、Worker.md)
* #### [Spark 运行原理](13.%20Spark/8、Spark%20运行原理.md)
* #### [Spark DAG](13.%20Spark/9、Spark%20DAG.md)
* #### [Spark blockManager](13.%20Spark/10、Spark%20blockManager.md)
* #### [BlockManager初始化](13.%20Spark/11、BlockManager初始化.md)
* #### [BlockManager之block数据的读写](13.%20Spark/12、BlockManager之block数据的读写.md)
* #### [Spark MapOutputTracker浅析](13.%20Spark/13、Spark%20MapOutputTracker浅析.md)
* #### [数据本地化级别](13.%20Spark/14、数据本地化级别.md)
* #### [SparkContext、SparkConf、SparkSession](13.%20Spark/15、SparkContext、SparkConf、SparkSession.t.md)
* #### [Spark YARN启动流程源码分析一](13.%20Spark/16、Spark%20On%20YARN启动流程源码分析一.md)
* #### [Spark On YARN（Yarn-Cluster模式）启动流程源码分析（二）](13.%20Spark/17、Spark%20On%20YARN（Yarn-Cluster模式）启动流程源码分析（二）.md)
* #### [SparkContext执行](13.%20Spark/18、SparkContext执行.md)
## 面试
### 计算机网络
* #### [HTTPS的加密机制](面试/计算机网络/1.%20HTTPS的加密机制.md)
* #### [三次握手与四次挥手](面试/计算机网络/2.%20三次握手与四次挥手.md)
### Spring
* #### [Spring Boot中的注解](面试/Spring/1.%20Spring%20Boot中的注解.md)
* #### [Spring Boot中的AOP及日志记录应用](面试/Spring/2.%20Spring%20Boot中的AOP及日志记录应用.md)
### Redis
* #### [Redis的IO多路复用](面试/Redis/1.%20Redis的IO多路复用.md)
### Elasticsearch
* #### [为什么用Elasticsearch做全文搜索而不用MySQL](面试/Elasticsearch/1.%20为什么用Elasticsearch做全文搜索而不用MySQL.md)
### 分布式环境
* #### [分布式锁](面试/分布式/1.%20分布式锁.md)
* #### [数据库与缓存数据一致性问题](面试/分布式/2.%20数据库与缓存数据一致性问题.md)
* #### [压缩算法性能对比](面试/分布式/3.%20压缩算法性能对比.md)
### JVM面试
* #### [JVM](面试/JVM/JVM调优.md)
* #### [java中的static关键字](面试/JVM/2.%20java中的static关键字.md)
### 设计模式
* #### [单例模式](面试/设计模式/1.%20单例模式.md)
### 多线程面试
* #### [Synchronized与ReentrantLock区别](面试/多线程/1.%20Synchronized与ReentrantLock区别.md)
### JDK
* #### [ArrayList与LinkedList区别](面试/JDK/1.%20ArrayList与LinkedList区别.md)
### 数据结构
* #### [B树和B%2B树的插入、删除](面试/数据结构/B树和B%2B树的插入、删除.md)
### 编程
* #### [LeetCode-9-回文数](面试/编程/1.%20LeetCode-9-回文数.md)
* #### [LeetCode-面试题40-最小的k个数](面试/编程/2.%20LeetCode-面试题40-最小的k个数.md)
## 实习小记
* #### [Guava的Lists与Maps](实习小记/1.%20Guava的Lists与Maps.md)
## 源码
### MyBatis
* #### [调试环境搭建](源码/MyBatis/1.%20调试环境搭建.md)
* #### [项目结构一览](源码/MyBatis/2.%20项目结构一览.md)
* #### [解析器模块](源码/MyBatis/3.%20解析器模块.md)
* #### [反射模块](源码/MyBatis/4.%20反射模块.md)
