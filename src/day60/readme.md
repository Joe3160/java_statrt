#### 第60节 死锁问题

##### 死锁问题

线程a需要申请资源1才能执行，资源1被线程b占有;
线程b需要申请资源2才能执行，而资源2被线程a占有。

线程a占有资源2，需要请求资源1;
线程b占有资源1，需要请求资源2。