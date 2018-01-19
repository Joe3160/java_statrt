#### 第59节 Java同步问题解决方案

##### Java同步问题解决方案

1.  同步方法：
    
    当线程进入同步方法的时候，就会获得同步方法所属对象的锁，
    一旦获所属对象的锁，其它线程不能再执行被锁对象的任何同步方法。
    只有在同步方法执行完毕之后释放了锁，其它线程才能执行。

    
        synchronized 方法声明{
        
        }
2. 同步块：

        synchronized(资源对象){
         //需要同步的方法
        }