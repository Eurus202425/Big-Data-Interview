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
