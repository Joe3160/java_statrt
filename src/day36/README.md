###  抽象类
 
1. **定义**

        抽象是为子类提供一个规范
        
    
        修饰符 abstract 类名｛
            
            
        
        ｝        
     
    * 抽象方法没有方法体: `public abstract void test();`
    * 普通方法有方法体：`public abstract void test(){ 方法体 }`
    * 抽象类至少含有一个抽象方法
    * 含有抽象方法的类一定是抽象类

2.  **抽象类的例用**

>  `@Override` 检测是否重写成功

- 一个类继承了抽象类，就必须重写该抽象类的所有抽象方法
- 如果一个类没有重写抽象类的抽象方法，这个类也要定义为抽象类

