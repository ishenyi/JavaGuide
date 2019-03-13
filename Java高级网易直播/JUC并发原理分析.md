## 推断FultureTask原理

callable.call() 与 Runable.run()联系

对象的wait(). Notify()方法可以实现 线程唤醒，等待

记得分析object源码

1. 范型定义
2. 构造方法callable
3. 实现runnable
4. get方法返回callable执行结果
5. get方法有阻塞效果，未执行结束的化

多线程之间状态的流转



实际源码实现线程的等待和唤醒，用的是pack和unpack方式

还用到了线程终止，cas机制



dubbo motan grpc spring