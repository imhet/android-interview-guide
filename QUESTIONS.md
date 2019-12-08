## 一、计算机基础


### 1.1 网络

- 输入网址到网页呈现背后到底发生了什么？
- 网络七层协议
- http 与 https 的区别
- http 协议的格式
- cookie 和 session
- get 和 post 的区别
- https 请求过程
- 为什么是三次握手不是两次握手？
- tcp 三次握手和四次挥手
- tcp 和 udp 的区别以及使用场景
- udp 如何实现可靠传输
- tcp 如何实现可靠传输 ?
- 什么是大小端?
- 介绍一下 http 协议
- http 各个状态码的意义
- 计算机网络中的重定向是什么


### 1.2 操作系统

- 怎么避免死锁？

### 1.3 数据库

- 关系型数据库中的主键是什么？
- 主键和唯一键有什么区别？
- UNION 和 UNION ALL 有什么区别？
- 数据库范式
- 连接查询
- 数据库事务
- 数据库索引

### 1.4 数据结构和算法

- 如何用数组实现队列？
- 实现生产者消费者问题
- 给出根节点和目标节点，找出二叉树中从根节点到目标节点的路径
- 二叉树中序遍历
- 判断平衡二叉树
- 如何从一百万个数里面找到最小的一百个数，考虑算法的时间复杂度和空间复杂度
- 一个二维数组，数组中的内容非0即1，0代表海洋，1代表陆地，求所给二维数组代表的区域中陆地面积的最大值
- 如何反转链表？
- 20亿个qq号码，如何判断其中是否存在某一个？
- 快排的思想，最好、最坏时间复杂度
- 数据库如何短时间高效批量插入数据
- 求给定数组中和最大的连续子串的最大和的值
- 如何快速获取链表的倒数第a个节点
- 描述下快速排序的思想，时间复杂度？什么场景对应着最坏情况？
- 给定无序数组和一个值，找到两个数和为值的元素，不能使用额外空间复杂度（不要使用HashMap）
- 递归非递归反转链表
- 打印回环数组
- 找到一个无序数组中第一次出现最多次数的元素
- 找到一个字符串中出现最多的字母

### 1.5 设计模式

- 观察者模式
- 适配器模式
- 代理模式
- 工厂方法模式
- 抽象工厂模式
- 单例模式
- 命令模式
- 你知道哪些 JDK 中用到的设计模式？
- 你知道哪些 Android 中用到的设计模式？


## 二、Java 知识


### 2.1 Java 基础

- == 和 equals 的区别
- 如果 try 或者 catch 中进行了 return，finally 是否还会执行？
- String、StringBuilder、StringBuffer 的异同点
- Object 的方法
- 内部类访问局部变量的时候，为什么变量必须加上 final 修饰？
- i++ 在多线程环境下是否存在问题，怎么解决？
- 你了解哪些 JDK1.8 的新特性？
- java 静态方法是否可以被重写？
- String 类为什么具有不可变性？其如何实现不可变性的？
- String 不可变有什么好处？
- String[] 是不是 Object 的子类？
- 在 A 线程中调用 B 线程的 sleep，休眠的是哪个线程？
- java 中类的某些成员变量没有被用到，是否可以随意删除？
- 字节流和字符流的区别
- java gc 机制介绍
- ReentrantLock 、synchronized 和 volatile 的区别 或者 java 中保持线程同步的三种方式比较
- synchronized 对普通方法、静态方法加锁有什么区别
- ReentrantLock 的内部实现
- TreeMap 具体实现
- ArrayList 和 LinkedList 对比
- 平衡二叉树、二叉查找树、红黑树
- Set 实现原理
- 注解的实现原理
- HashMap的原理
- Android 中为什么建议用 ArrayMap 和 SpareArray 替代 HashMap ？
- 动态代理的原理？
- java 的四种引用
- java中原子性、可见性、有序性问题的本质

### 2.2 Java 进阶

- 集合框架层次结构
- HashMap原理
- ArrayList、LinkedList、Vector的区别？各自的使用场景？
- ConcurrentMap 和 HashMap 区别
- Java中HashMap的key值要是为类对象则该类需要满足什么条件？


## 三、 Android

### 3.1 Android 基础

#### 四大组件

- 如何退出APP？
- Activity 生命周期
- Android 屏幕旋转时的生命周期
- A启动B和B返回A的生命周期执行过程（A 和 B 都是 Activity）
- Activity 执行 finish 后对应的生命周期
- Activity 启动的四种模式
- 如何加速 Activity 启动？
- Activity 和 Service 的区别是什么？
- Service 和 Activity 的通信方式
- Service 的生命周期
- Service onBindService 和 startService 启动的区别
- 如何保活 Service ?
- 为什么有时需要在Service中创建子线程而不是Activity?
- IntentService 有什么作用？
- ContentProvider 是如何实现数据共享的？
- ContentProvider、ContentResolver与ContentObserver之间的关系是什么？
- ContentProvider的操作是在哪个线程中运行？
- BroadcastReceiver 的分类
- BroadCastReceiver 如何处理耗时操作
- 广播发送和接收的原理
- 广播传输的数据是否有限制
- 本地广播实现原理？

#### Fragment

- Fragment 生命周期
- Fragment 有什么优点
- Fragment 和 View异同
- Fragment 的启动和回退栈
- 遇到过哪些关于 Fragment 的问题，如何处理的？
- 使用 Fragment 有什么好处？
- 有没有使用过嵌套 Fragment ？

#### View

- 如何自定义 View
- 为什么自定义 View 执行 invalidate 方法有时候不会回调onDraw()？
- View 的绘制流程
- View 的 measureSpec 由谁决定? 根 view 呢？
- View 的 invalidate 、postInvalidate 和 requestLayout 方法
- View 和 viewGroup 的区别
- View 和 viewGroup 绘制流程区别
- View 事件的分发机制
- onTouchEvent 、onTouch 、onClick 、onLongClick 的先后顺序
- view 的生命周期
- 如何处理滑动冲突？
- View 的多点触控
- RecyclerView 基本使用
- RecyclerView 的缓存机制
- View、SurfaceView 和 GLSurfaceView 的区别
- 常见 View 的布局
- 布局文件中 layout_gravity 和 gravity 以及 weight的作用
- TextView 怎么改变局部颜色
- Activity、View 及 Window 之间关系
- postDelayed 原理

#### 布局控件

- Android 中l ayout-sw600dp、layout-w600dp 和 layout-h600dp 的区别
- Android 样式和主题的区别

#### 消息通信

- AsyncTask 的实现原理
- 使用 AsyncTask 有需要注意的地方？如何进行并行操作？
- Android 为什么不允许在非 UI 线程更新 UI
- Android 中的 Handler 机制 或者叫 Android 消息机制
- Looper 消息机制，postDelay 的 Message 怎么处理，Looper 中的消息是同步还是异步？什么情况下会有异步消息
- Looper 的工作原理
- 如何在子线程使用 Handler
- ThreadLocal 的工作原理
- HandlerThread 的使用及实现
- Android 中 Handler 声明非静态对象会发出警告，为什么非得是静态的？
- 主线程 Looper 在没有消息处理的时候，为什么不会导致主线程卡死
- Android 中如何自己实现跨线程的通信
- 一个线程中可以有几个 handler ？几个 Looper ？几个messageQueue ？
- handler.postDelayed 中的 run 是工作在主线程还是子线程
- Android中除了线程池还有哪些异步线程（多线程）的实现方式？
- Android 跨进程（IPC）传递数据的几种方案
- Linux 的用户空间和内核空间
- 为什么要使用Binder？
- Binder 跨进程通信机制

#### 数据存储

- Android 中的数据存储方式都有哪些
- SharedPreference 是否是进程同步的？如何实现进程同步？
- SharedPreference 的方法 commit 和 apply 的区别
- Android 中文件存储路径与权限是怎么样的
- 在 sqlite 中如何进行大量的数据插入？
- 如何导入外部数据库？
- 如何保证多线程操作数据库的安全性？
- sqlite 实现原理

#### 其它

- Android 项目中的 res 目录和 asset 目录的区别
- Android 中 的 APP 是如何实现沙箱化的？沙箱化有什么好处？
- 热修复原理是什么
- 开启多进程要注意哪些？
- Android 中如何查看一个对象的回收情况？
- JNI 与 NDK 分别是什么
- JNIEnv 与 JavaVM
- JNI 中全局引用和局部引用的区别和使用
- JNI 线程间数据怎么互相访问
- JNI 开发中有碰到什么问题？怎么定位 native crash
- 怎么定位 NDK 中的问题和错误
- 静态注册和动态注册的区别
- ndk 中的 attachCurrentThread 有什么用？
- so 的动态加载和静态加载 或 so文件有几种加载方式
- ndk 加载 so 时如何考虑32位和64位的不同，如何考虑不同的 arm 平台
- 为什么要使用extern C
- Parcelable 和 Serializable 区别
- 在两个 Activity 之间传递对象还需要注意什么呢？
- Android 8.0，9.0有哪些新特性，有没有了解过
- Android源码中用到了哪些设计模式
- 应用怎么判断自己是处于前台还是后台？
- Bitmap的本质？
- Android的多渠道打包你了解吗？
- JVM、ART、Dalvik的区别和联系
- Android中的classLoader相比java中的classLoader有什么区别？
- jar 和 aar 的区别
- Android 如何生成设备唯一标识
- 如何在不压缩的情况下加载高清大图
- Android 中有哪些方法实现定时和延时任务？
- 如何给视频加密？
- 线程和进程的区别
- Android 中如何停止一个线程
- 如何优化 ListView 的加载
- ListView 与 RecyclerView 区别
- LRU 算法原理
- 推送机制中影响 TCP 连接寿命的因素
- 如何做进程保活?
- Bundle 和 HashMap 有什么区别？
- Android 中的动画有哪几种
- 插件化、组件化和热修复的区别
- 为什么Android中的单个dex方法数最多只能有65535？
- px、dp（dip）、sp的区别
- Kotlin 和 Java 比的异同点
- 有没有对比过flutter和其他跨平台方案有什么异同点
- 错误码和错误描述，可能多个离散错误码对应一个错误描述，如何根据不同的错误码返回不同的错误描述？
- Android 如何保证进程不被杀死
- 一个 Android 正常启动有多少个线程?
- 你觉得开发一个 SDK，需要注意哪些地方，有没有做过SDK性能测试

### 3.2 Android 开源库

- 开源类库 OkHttp 的实现原理
- OkHttp 中连接池的最大数量
- OkHttp 中连接池的实现原理
- 开源类库 Retrofit 的实现原理
- 开源类库 Fresco 的实现原理
- 开源类库 EventBus 的实现原理
- 开源类库 Glide 的实现原理
- 开源类库 OkHttp 的实现原理

### 3.3 Android 优化

- Android 启动优化
- Android 布局优化 
- Android 网络优化
- Android 体积优化
- Android 卡顿优化
- A ndroid 磁盘优化
- 如何制造 OOM 或 ANR ？
- Android 的屏幕刷新机制，怎么优化 UI 卡顿情况
- 什么是 ANR 以及如何避免？ 
- Android 中内存泄漏的常见原因
- Android 中如何避免内存泄漏？
- 开源类库 LeakCanry 的实现原理
- 如何减小内存的使用？或 如何优化内存？
- 如何优化 Bitmap？
- 如何优化卡顿？
- Android 中如何捕获异常
- Android 中如何捕获主进程异常让应用不奔溃
- 如何优化一个列表滑动的流畅性
- 让你加载一个200M左右的GIF，如何实现及优化，不可降低画质
- Android 的内存管理

### 3.4 Android 框架

- 如何理解 Android 中的 Context
- Application 和 Activity 的 Context 对象的区别
- Application start Activity 为什么必须 new 一个Task 
- apk 的安装流程
- Android 的系统架构是怎么样的
- Android 系统启动过程
- App 启动过程 或者 点击桌面的应用图标启动应用过程
- Activity 启动过程
- 匿名共享内存实现原理
- Binder 机制的实现思想
- AIDL的原理是什么？


### 3.5 Android 架构设计

- 设计一个网络请求框架(可以参考 Volley 框架)
- 设计一个网络图片加载框架
- 如何给 app 进行加固？
- ProGuard（混淆）的实现原理是什么？
- 如何实现断点续传？
- 如何设计一个下载管理框架？
- 如何设计一个 广告SDK？
- 如何设计一个路由框架？
- 能画一下项目的架构图么？
- 项目的架构是如何演进的？
- MVP 与 MVC 以及 MVVM 三中常见架构的区别


### 3.6 Android 音视频


## 四、其它

### 4.1 C++ 知识

- C++ 中参数传递有哪几种方式？java 呢？
- java 里面有没有类似 C++ 的析构函数的东西
- C++ 和 java 有什么区别？

### 4.2 开放题

