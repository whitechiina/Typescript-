## 1.1什么是typescript

1、TS是由微软开发的开源编程语言

2、typescript是javascript的超集、

3、TS是开发大型应用的基石

4、TS提供了更丰富的语法提示

5、TS在编写阶段就能检查错误

## 2.1ts是静态类型，js是动态类型

在TS中，类型是确定的，给类型赋完值之后不能去轻易的更改，类似js中的常量

## 3.1 TS中的数据类型:

JS：
原始数据类型： boolean string number null undefined symbol
引用数据类型： object

TS：
基础类型： boolean string number null undefined symbol
any never 

对象：  interface关键字
数组：  number[]  string[]  boolean[]  数组泛型写法： Array<number>

函数的注解： 

function test( a：nunmber, b：string) {
    return a + b;
}

新的语法特性：
    as  断言
    class （ES5中就有，多了一个原始的OOP面向对象的三大特性：封装，继承，多态）



## 3.1 TS中的原始数据的注解:
布尔值的注解
let a: boolean = false

数字的注解
let b: number = 123

字符串的注解
let c: string = '123'
c = "smith"

模板字符串
let senternce: string = `helloe, my name is ${c}`;