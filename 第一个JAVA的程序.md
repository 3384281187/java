## 第一个JAVA的程序

作为每个程序员写的每种语言第一个程序那一定是Hello World了

现在来看一下Java的Hello World怎么写的：

假如我现在创建一共名为Hello World的Java文件

```java
public class HelloWorld{
    public static void main(String[] args){
        System.out.println("Hello world");
    }
}
```

#### 第一段代码

```java
public class HelloWorld//HelloWorld就是你的文件名，你对这个Java文件起的什么名字这里就是你文件的名字
```

其中**`Helloworld`**就是你所创建Java的文件名

而**`public class`**就是第一段的关键字一般来说是不会改变的

#### 第二段代码

```java
public static void main(String[] args)//这一段的代码是固定的
```

这一段代码一般是固定的，是不做改变的

只不过要注意格式：

```java
public class HelloWorld{
    public static void main(String[] args){
    }
}
```

#### 第三段代码

```java
System.out.println("Hello world");
```

**`System.out.println()`**

这就是输出的格式，输出内容放在括号内就行