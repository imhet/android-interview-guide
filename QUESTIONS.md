
## 一、计算机基础


### 1.1 网络

- 简单介绍下网络七层协议
- 介绍一下 http 协议
- cookie 和 session
- get 和 post 的区别
- http 常见状态码
- https 请求过程
- http 与 https 的区别
- tcp 三次握手和四次挥手
- 为什么是三次握手不是两次握手
- tcp 和 udp 的区别以及使用场景
- tcp 和 udp 如何实现可靠传输
- 谈谈你对 WebSocket 的理解？
- 什么是大小端?网络通信中的大小端问题如何解决?
- 输入网址到网页呈现背后到底发生了什么


### 1.2 操作系统

- 死锁的四个必要条件
- 怎么避免死锁
- 实现生产者消费者问题
- 线程和进程的区别
- Linux 的用户空间和内核空间

### 1.3 数据库

- 关系型数据库中的主键是什么?
- 主键和唯一键有什么区别？
- UNION 和 UNION ALL 有什么区别？
- 数据库如何短时间高效批量插入数据？
- 简述数据库索引的实现原理
- 如何做查询优化

### 1.4 数据结构和算法

- 如何用数组实现队列
- 给出根节点和目标节点，找出二叉树中从根节点到目标节点的路径
- 二叉树中序遍历
- 判断平衡二叉树
- 如何从一百万个数里面找到最小的一百个数，考虑算法的时间复杂度和空间复杂度
- 一个二维数组，数组中的内容非0即1，0代表海洋，1代表陆地，求所给二维数组代表的区域中陆地面积的最大值
- 如何反转链表？
- 20亿个qq号码，如何判断其中是否存在某一个？
- 快排的思想，最好、最坏时间复杂度
- 求给定数组中和最大的连续子串的最大和的值
- 如何快速获取链表的倒数第 a 个节点
- 描述下快速排序的思想，时间复杂度？什么场景对应着最坏情况？
- 给定无序数组和一个值，找到两个数和为值的元素，不能使用额外空间复杂度（不要使用HashMap）
- 递归非递归反转链表
- 打印回环数组
- 找到一个无序数组中第一次出现最多次数的元素
- 找到一个字符串中出现最多的字母
- 平衡二叉树、二叉查找树、红黑树
- 排序算法有哪些？写出你所知道的排序算法及时空复杂度，稳定性

### 1.5 设计模式

- 你知道哪些 JDK 中用到的设计模式
- 你知道哪些 Android 源码中用到的设计模式
- 你平时在工作中用过哪些设计模式
- 观察者模式
- 适配器模式
- 代理模式
- 工厂方法模式
- 抽象工厂模式
- 单例模式
- 命令模式


## 二、Java 知识


### 2.1 Java 基础

#### 基础

- 抽象类和接口的关系
- 重载和重写的区别
- java 运行时异常与一般异常有何异同
- error 和 exception 有什么区别
- 如果 try 或者 catch 中进行了 return，finally 是否还会执行
- equals 与 == 的区别
- String、StringBuilder、StringBuffer 的异同
- String 类为什么具有不可变性？它是如何实现不可变性的？
- String 不可变有什么好处？
- String[] 是不是 Object 的子类
- Object 类有哪些共有方法？
- 内部类访问局部变量的时候，为什么变量必须加上 final 修饰
- java 静态方法是否可以被重写？
- java 中类的某些成员变量没有被用到，是否可以随意删除
- 字节流和字符流的区别
- NIO 与 IO 的区别
- 说说你对反射的理解
- 说说你对注解的理解
- 说说你对泛型的理解
- 动态代理的原理
- java 的四种引用
- 你了解哪些 JDK1.8 的新特性
- 什么是深拷贝和浅拷贝

#### 集合

- 集合框架层次结构是怎么样的
- 为什么在 for-each 中增加或者删除元素会抛出异常
- HashMap 的实现原理
- HashMap 的 key 值要是为类对象则该类需要满足什么条件
- TreeMap 的实现原理
- ArrayList 和 LinkedList 对比
- Set 的实现原理
- ConcurrentMap 和 HashMap 区别
- 线程安全的集合类有哪些


### 2.2 Java 进阶


#### 线程与并发

- java 中有几种方法可以实现一个线程
- i++ 在多线程环境下是否存在问题，如果存在怎么解决
- 在 A 线程中调用 B 线程的 sleep，休眠的是哪个线程
- ReentrantLock Synchronized 和 volatile 的区别 或者 java 中保持线程同步的三种方式比较
- synchronized 对普通方法和静态方法加锁有什么区别
- 谈谈 volatile 关键字的作用
- java 中原子性、可见性、有序性问题的本质
- Lock 和 Synchronized 有什么区别？
- Thread 的 sleep、yield 和 Object 的 wait 的异同
- 如何停止一个线程
- 什么是线程池，如何使用

#### JVM

- JVM 体系架构
- JVM 类加载模型
- JVM 内存结构
- JVM 内存模型
- java 对象模型
- 垃圾回收原理
- 常见的垃圾回收器
- 两个对象相互引用会不会被 GC ？
- 堆内存和栈内存的区别
- java 四种引用类型


## 三、 Android

### 3.1 Android 基础

#### 四大组件

- Activity 的生命周期
- Android 屏幕旋转时的生命周期
- A启动B和B返回A的生命周期执行过程（A 和 B 都是 Activity）
- Activity 执行 finish 后对应的生命周期
- Activity 启动的四种模式
- 如何加速 Activity 启动？
- Activity 和 Service 的区别是什么？
- Service 和 Activity 的通信方式
- Service 的生命周期
- Service 的 onBindService 和 startService 的区别
- 如何保活 Service ?
- 为什么有时需要在 Service 中创建子线程而不是 Activity ?
- IntentService 有什么作用？
- ContentProvider 是如何实现数据共享的？
- ContentProvider 、ContentResolver 与 ContentObserver 之间的关系是什么？
- ContentProvider 的操作是在哪个线程中运行？
- BroadcastReceiver 的分类
- BroadCastReceiver 如何处理耗时操作
- 广播传输的数据是否有限制
- 本地广播实现原理？
- 在两个 Activity 之间传递对象需要注意？
- 如何退出APP？

#### Fragment

- Fragment 生命周期
- Fragment 有什么优点
- Fragment 和 View 异同
- Fragment 的启动和回退栈
- 有没有使用过嵌套 Fragment ？
- 项目开发中遇到过哪些关于 Fragment 的问题，如何处理的？


#### View

- 如何自定义 View
- 为什么自定义 View 执行 invalidate 方法有时候不会回调 onDraw() ？
- View 的绘制流程
- View 的 measureSpec 由谁决定? 根 View 呢？
- View 的 invalidate 、postInvalidate 和 requestLayout 方法
- View 和 viewGroup 的区别
- View 事件的分发机制
- onTouchEvent 、onTouch 、onClick 、onLongClick 的先后顺序
- View 的生命周期
- 如何处理 View 滑动冲突？
- View 的多点触控
- ListView 与 RecyclerView 区别
- RecyclerView 的缓存机制
- View、SurfaceView 和 GLSurfaceView 的区别
- 常见 View 的布局有哪些
- TextView 怎么改变局部颜色
- Activity、View 及 Window 之间关系
- Android 中 layout-sw600dp、layout-w600dp 和 layout-h600dp 的区别

#### 消息通信

- AsyncTask 的实现原理
- 使用 AsyncTask 有需要注意的地方？如何进行并行操作？
- Android 为什么不允许在非 UI 线程更新 UI？
- Android 中的 Handler 实现原理
- Looper 消息机制，postDelay 的 Message 怎么处理，Looper 中的消息是同步还是异步？什么情况下会有异步消息
- Looper 的工作原理
- 如何在子线程使用 Handler
- ThreadLocal 的工作原理
- HandlerThread 的使用及实现
- Android 中 Handler 声明非静态对象会发出警告，为什么非得是静态的？
- 主线程 Looper 在没有消息处理的时候，为什么不会导致主线程卡死？
- Android 中如何自己实现跨线程的通信
- 一个线程中可以有几个 handler ？几个 Looper ？几个messageQueue ？
- Handler.postDelayed 中的 run 是工作在主线程还是子线程
- Android 中除了线程池还有哪些异步线程（多线程）的实现方式？
- Android 跨进程（IPC）传递数据的几种方案

#### 数据存储


- Android 中的数据存储方式都有哪些
- SharedPreference 是否是进程同步的？如何实现进程同步？
- SharedPreference 的方法 commit 和 apply 的区别
- Parcelable 和 Serializable 区别
- 在 sqlite 中如何进行大量的数据插入？
- 如何导入外部数据库？
- 如何保证多线程操作数据库的安全性？
- sqlite 实现原理

#### JNI 和 NDK

- JNI 与 NDK 分别是什么
- JNIEnv 与 JavaVM
- JNI 中全局引用和局部引用的区别和使用
- 静态注册和动态注册的区别
- NDK 中的 attachCurrentThread 有什么用？
- so 的动态加载和静态加载 或 so文件有几种加载方式
- NDK 加载 so 时如何考虑32位和64位的不同，如何考虑不同的 arm 平台？
- 为什么要使用 extern C ？
- JNI 中全局引用和局部引用的区别和使用
- JNI 线程间数据怎么互相访问？
- JNI 开发中碰到什么问题么？
- 如何在 jni 中注册 native 函数，有几种注册方式?
- 怎么在 JNI 里面抛异常
- 怎么在 JNI 里面调用 Java 的方法
- 怎么定位 native crash？
- C++ 中参数传递有哪几种方式？
- C++ 和 java 有什么区别？

### 3.2 Android 开源库

- OkHttp 的实现原理
- Retrofit 的实现原理
- Fresco 的实现原理
- EventBus 的实现原理
- Glide 的实现原理
- OkHttp 的实现原理
- LeakCanry 的实现原理
- Rxjava 的实现原理

### 3.3 Android 优化

- Android 内存优化
- Android 启动优化
- Android 布局优化
- Android 卡顿优化
- Android 体积优化
- Android 网络优化
- Android 磁盘优化
- 什么是 ANR 以及如何避免？
- 如何分析和定位 ANR ？
- Android 中内存泄漏的常见原因以及如何避免？
- 如何制造 OOM 或 ANR ？
- Android 中如何捕获异常？如何捕获主进程异常让应用不奔溃？
- 如何优化 ListView ？
- 让你加载一个200M左右的GIF，如何实现及优化，不可降低画质
- Android 的内存管理机制
- Android 中如何查看一个对象的回收情况？
- Android 中为什么建议用 ArrayMap 和 SpareArray 替代 HashMap ？
- Android 中 Bitmap 的内存管理是演进的？
- Android 如何做进程保活?
- 如何在不压缩的情况下加载高清大图？

### 3.4 Android 框架

- Android 的系统架构是怎么样的
- Android 系统启动过程
- APK 的安装流程
- App 启动过程 或者 Activity 启动过程
- 如何理解 Android 中的 Context？
- Android 的屏幕刷新机制
- Application start Activity 为什么必须 new 一个Task
- 匿名共享内存实现原理？
- 如何理解 Binder ？为什么要使用 Binder？
- AIDL 的原理是什么？
- APK 的编译流程

### 3.5 Android 架构设计

- 如何从头设计一款 App 整体架构？
- 能画一下你的项目的架构图么？
- 你的项目的架构是如何演进的？
- 简述 MVC 、MVP 和 MVVM
- 谈谈你对组件化和模块化的理解
- 简述插件化和热修复的实现原理
- 使用多进程要注意什么？
- 如何设计一个网络请求框架？
- 如何设计一个图片加载框架？
- 如何实现断点续传？
- 如何设计一个下载管理框架？
- 如何设计一个广告SDK？
- 如何设计一个路由框架？
- 如何实现一个 json 解析器
- 开发一个 SDK 需要注意哪些地方，有没有做过SDK性能测试?
- 为什么 Android 中的单个 dex 方法数最多只能有 65535 ？
- Android 中的 classLoader 相比 java 中的 classLoader 有什么区别？

### 3.6 Android 安全

- 您的项目中安全是如何做的？
- 如何给 APP 进行加固？
- 如何加密 so?
- Android 常见漏洞有哪些？
- Android 中 的 APP 是如何实现沙箱化的？沙箱化有什么好处？
- ProGuard 的实现原理是什么？
- 概述 Android 反编译流程
- Smali 的数据类型和 Java 的对应关系
- root 的原理


### 3.7 Android 音视频

- 列举一些音视频编码常用的实现方案
- 谈谈你对 YUV 格式的理解
- 请叙述 MPEG 视频基本码流结构
- 预测编码的基本原理是什么
- 如何给视频加密？
- 简述播放器实现原理
- 如何定位和修复播放卡顿问题？
- 如何优化视频起播速度
- 回音消除的实现原理
- 如何提升视频播放质量


### 3.8 其它

- Android 各版本有哪些新特性？
- 应用怎么判断自己是处于前台还是后台？
- Android 中签名机制与多渠道打包
- JVM、Dalvik、ART的区别和联系
- Android 中如何生成设备唯一标识？
- Android 中有哪些方法实现定时和延时任务？
- LRU 算法原理
- 推送机制中影响 TCP 连接寿命的因素有哪些？
- Android 中的动画有哪几种？
- Android 应用正常启动有多少个线程?
- 如何理解协程？


## 四、其它

### 4.1 开放题

- Git 的实现原理
- 海盗分金问题
