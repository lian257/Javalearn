# Javalearn
java language

# 面向对象

**类：共同特征的描述 
对象：真实存在的具体实例**

语句： 
    **类名  对象名 = new 类名();**
```java
Phone p1 = new Phone(); 
```
## 封装 
> __正确设计一个对象__
>
>> **private权限修饰符，修饰的成员只能在本类中调用**
> * 针对私有化成员变量，都要提供get和set方法
> * Intellij Idea 快捷键**ALT + Insert**
>> 
```java
    private String brand;
    //私有 成员变量
    double price;

    public String getBrand() {
        return brand;
    }
吧
    public void setBrand(String brand) {
        String brand;
        // TODO:局部变量
        this.brand = brand;
        // this 代表方法调用值的地址值
        区分局部和成员变量
    }
```
# 构造方法  无返回值
> * 如果没有定义构造方法，系统会自动给出一个默认无参构造方法
> * __无论是否使用，都要手动书写构造方法__
> * __创建对象的时候，由虚拟机自动调用，给成员变量进行初始化__
> * **一旦定义有参构造器，无参构造器消失，此时需要写无参数构造器**

### 创造对象的时候，虚拟机是自动调用构造方法，作用是给成员变量赋初值

# javaBean
> * 所有成员变量使用Prvite修饰
> * 初学不使用快捷键
> * 空参 带全部参数的构造
> * get set 方法

基本数据类型：数据存储在自己空间
特点：赋值给其他变量为真实值
引用数据类型：数据存储在其他空间
自己空间存储的是地址值

# 重载
> 方法名一样
>> * 参数个数不一样 类型不一样
>> * 例外： 返回值不一样 不够成重载 

