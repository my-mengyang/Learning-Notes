# es6

var的设计可以看成是JS语言的错误 所以在es6中新增了一个let 可以看作是更完美的var
## 块级作用域
JS中使用var来声明一个变量的时候 变量的作用于主要是和函数的定义有关
针对于其他块定义来说是没有作用于的 比如for if 

### let 变量 
let 有块级作用域
- 作用域是什么
变量在什么范围内可以使用
闭包可以解决作用于问题 因为函数是一个作用域


### const 常量
使用const修饰的标识符未常量，不可再次被赋值

当我们修饰的标识符不会被再次赋值时，就可以使用const来保证数据的安全性

在es6开发中 优先使用const 只有需要改变某一个标识符的时候才使用let

注意 ：
	const的值不能修改
	const修饰的标识符必须赋值
	常量的含义是指向的对象不能修改，但是可以改变对象内部的属性
	
### 对象字面量的增强写法
run:function(){

}
增强写法
+ 属性的增强写法
name:name 可以写成name
+ 对象的增强写法

run(){

}