## 一、选择题

1.下面不属于ECMAScript规范的范围的是：（ ）

A、数据类型

B、语法

C、DOM事件

D、内置对象和函数的标准库

 

2.下面不属于关键字let的特点的是：（ ）

A、只在 let 命令所在的代码块内有效

B、会产生变量提升现象

C、同一个作用域，不能重复声明同一个变量

D、不能在函数内部重新声明参数

 

3.关于关键字const，下列说法错误的是：（）

A、用于声明常量，声明后不可修改

B、不会发生变量提升现象

C、不能重复声明同一个变量

D、可以先声明，不赋值。

 

4.在数组的解构赋值中，var [ a,b,c ] = [ 1,2 ]结果中，a、b、c的值分别是：（）

A、1  2  null

B、1  2  undefined

C、1  2  2

D、抛出异常



5.在对象的解构赋值中，var {a,b,c} = { “c”:10, ”b”:9, ”a”:8 } 结果中，a、b、c的值分别是：（）

A、10  9  8

B、8  9  10

C、undefined  9  undefined

D、null  9  null



6.关于模板字符串，下列说法不正确的是：（）

A、使用反引号标识

B、插入变量的时候使用${ }

C、所有的空格和缩进都会被保留在输出中

D、${ }中的表达式不能是函数的调用



7.关于字符串扩展的新函数，下面描述错误的是：（）

A、includes函数用于判断字符串中是否含有指定的子字符串

B、repeat函数将目标字符串重复N次，目标字符串被修改

C、startsWidth函数判断指定的子字符串是否出现在目标字符串头部位置

D、endWidth函数判断指定的子字符串是否出现在目标字符串尾部位置



8.关于数值的扩展，window.isNaN(“abc”) 和Number.isNaN(“abc”)的结果分别是：（）

A、true   false

B、false   true

C、true   true

D、false   false



9.关于数值扩展的Number.isInteger函数，下面说法错误的是：（）

A、用来判断是否是整数，返回布尔值。

B、Number.isInteger(3);结果为：true

C、Number.isInteger(3.0);结果为：false

D、Number.isInteger(3.01);结果为：false



10.数组扩展的fill( )函数，[1,2,3].fill(4)的结果是：（）

A、[4]

B、[1,2,3,4]

C、[4,1,2,3]

D、[4,4,4]



11.数组的扩展中，不属于用于数组遍历的函数的是：（）

A、keys( )

B、entries( )

C、values( )

D、find( )



12.关于对象的扩展，错误的是：（）

A、ES6中对象的表示法更加简洁

B、对象的属性名可以是表达式

C、对象的方法名不可以是表达式

D、当属性名为表达式的时候，需要使用[ ]标识



13.关于对象的Object.is函数，错误的是：（）

A、用于判断两个值是否严格相等

B、用于判断两个值是否抽象相等

C、Object.is(3,'3') 结果是：false

D、Object.is(3,3.0) 结果是：true



14.函数的扩展中，关于rest参数的描述，正确的是：（）

A、获取函数剩下部分的参数

B、rest参数不可以是函数的最后一个参数

C、获取函数的第一个参数

D、一个名叫rest的参数

 

15.关于箭头函数的描述，错误的是：（）

A、使用箭头符号=>定义

B、参数超过1个的话，需要用小括号（）括起来

C、函数体语句超过1条的时候，需要用大括号{ }括起来，用return语句返回

D、函数体内的 this 对象，绑定使用时所在的对象



16.关于Symbol，错误的说法是：（）

A、是ES6新增的一种数据类型

B、Symbol() === Symbol() 结果为false

C、Symbol('same') === Symbol('same') 结果为true

D、当symbol值作为对象的属性名的时候，不能用点运算符获取对应的值。



17.下面运算结果，结果为true的是：（）

A、Symbol.for('name') == Symbol.for('name')  

B、Symbol('name') == Symbol.for('name')

C、Symbol('name') == Symbol('name')

D、Symbol.for('name') == Symbol('name')



18.关于Proxy代理，下面说法错误的是：（）

A、可以理解成在目标对象之前，架设一层“拦截”

B、Proxy的get 方法用于拦截某个属性的读取操作。

C、Proxy的set方法用于拦截对对象的写操作。

D、一旦对象设置Proxy代理后不可取消，所以要谨慎操作



19.关于for...of的简述，说法错误的是：（）

A、它可以遍历所有具有iterator 接口的数据结构

B、不可以用break来终止循环

C、使用continue可以跳过当前循环

D、可以遍历DOM list对象



20.关于set结构，下面说法错误的是：（）

A、创建一个实例需要用new关键字

B、结构成员都是唯一的，不允许重复

C、使用add方法添加已经存在的成员会报错

D、初始化的时候接受数组作为参数



21.关于Set结构的实例方法，下面说法错误的是：（）

A、set方法用于添加成员

B、clear方法用于清除所有成员。

C、entries方法返回成员的位置索引和值的遍历器

D、values方法返回成员值的便利器



22.关于WeakSet结构，说法错误的是：（）

A、与Set结构一样，成员值都是唯一

B、成员值必须是对象

C、WeakSet 中的对象都是弱引用

D、可以forEach( )方法实现遍历



23.关于Map结构的介绍，下面说法错误的是：（）

A、是键值对的集合

B、创建实例需要使用new关键字

C、Map结构的键名必须是引用类型

D、Map结构是可遍历的



24.下列Map结构的键名数据类型，描述错误的是：（）

A、键名可以是数组类型的值

B、键名可以是Symbol类型的值

C、键名值可以是null

D、键名值不可以为undefined



25.关于WeakMap结构，下列说法错误的是：（）

A、创建实例需要使用new关键字

B、键名可以是任何类型的值

C、WeakMap结构不支持clear方法

D、WeakMap结构不可遍历



26.ES6的新特性Promise对象的设计初衷是：（）

A、 更好地实现遍历具有iterator接口的数据结构

B、 为对象的操作增加了一层“拦截”

C、 独一无二的值，用于对象属性，避免属性名冲突

D、 让开发者更合理、更规范地用于处理异步操作



27.关于Promise对象的状态，下列说法错误的是：（）

A、 三种状态分别是：pending初始状态、fulfilled成功、rejected失败

B、 pending初始状态可以状变成fulfilled成功

C、 rejected失败不可以状变成pending初始状态

D、 rejected失败可以状变成fulfilled成功



28.下面关于类class的描述，错误的是：（）

A、 JavaScript的类class本质上是基于原型prototype的实现方式做了进一步的封装

B、 constructor构造方法是必须的

C、 如果类的constructor构造方法有多个，后者会覆盖前者

D、 类的静态方法可以通过类名调用，不需要实例化



29.JavaScript中类的继承使用的关键字是：（）

A、 extends

B、 inherit

C、 extend

D、 base



30.在类的继承中，关于super的说法错误的是：（）

A、 在子类的构造函数，必须先调用super( )

B、 super相当于子类的引用

C、 先调用super( )，才可以使用this

D、 super( )相当于父类构造函数的调用



31.下列数据结构中，不能被for...of遍历的是：（）

A、 Array数组

B、 Object对象

C、 String字符串

D、 Set结构



32.关于Iterator遍历器的说法，错误的是：（）

A、next( )方法是Iterator遍历器的核心

B、当next( )返回对象的done属性为fasle，遍历结束

C、具有Iterator接口的对象视为可遍历对象

D、可以自定义一个可遍历对象和其遍历行为



33.关于新特性Generator函数的描述，错误的是：（）

A、Generator函数，又称生成器函数

B、声明Generator函数的关键字是：function*

C、Generator函数执行后得到的一个生成器

D、使用return语句使Generator函数暂停执行，直到next方法的调用



34.Generator函数的yield关键字的作用是：（）

A、停止执行

B、退出函数

C、暂停执行，等待next( )方法调用

D、停止执行，可自行恢复执行



35.在Generator函数中，yield*语句的作用是：（）

A、调用另外的Generator函数

B、暂停执行，待next( )方法调用后恢复

C、停止执行，退出函数

D、调用任意的其他函数



36.关于ES6的module模块，下列说法错误的是：（）

A、可以有效解决大型系统文件复杂的依赖问题

B、使用export语句可以选择性地向外部暴露自己的属性或者方法

C、使用import语句导入其他模块的属性或者方法

D、目前大部分主流浏览器都支持module模块



37.module模块中，对下列语句的描述，错误的是：（）

A、export 导出

B、import 导入

C、export default 默认导出

D、import * as  重命名



38.module模块中的注意事项，下列说法错误的：（）

A、除了对象类型以外，导出的属性对外都是只读的

B、导入不存在的变量，值为undefined

C、导入不存在的变量，程序会抛出异常

D、可以为导入的属性和方法取任意名字



39.想要获取Map实例对象的成员数，利用的属性是：（）

A、size

B、length

C、sum

D、members



40.关于定义常量的关键字const，定义一个Object对象{“name”:”Jack”}，再对属性name 的值进行修改，如：obj.name = “John”。下列说法正确的：（）

A、修改常量，程序跑出异常

B、程序不抛出异常，修改无效

C、修改成功，name的值为John

D、程序不抛出异常，name的值为undefined

## 二、简答题

#### 1、说出至少5个ES6的新特性，并简述它们的作用

#### 2、使用结构赋值，实现两个变量的值的交换

#### 3、计算出数组 [1,2,3,4] 每一个元素的平方并组成新的数组

#### 4、使用模板字符串改写下面的代码

var iam  = "我是";var name = "tom";var str  = "大家好，"+iam+name+"，多指教。";

#### 5、用对象的简洁表示法改写下面的代码

`let name = "tom";

​	 let obj = {        

​	"name":name,       

​	 "say":function(){        

​		alert('hello world');    

​	} 

};`

#### 6、用箭头函数的形式改写下面的代码。

arr.forEach(function (v,i) {    console.log(i);    console.log(v);});

#### 7、阅读下面的代码，并用for…of改成它

let arr = [11,22,33,44,55];

 let sum = 0; 

for(let i=0;i<arr.length;i++){    sum += arr[i]; }

#### 8、关于Set结构，阅读下面的代码，回答问题。

let s = new Set();
s.add([1]);
s.add([1]);
console.log(s.size);

**问：打印出来的size的值是多少？**

#### 9、关于Map结构，阅读下面的代码，回答问题。

let map = new Map();
map.set([1],"ES6系列");
let con = map.get([1]);
console.log(con);

**问：打印出来的变量con的值是多少，为什么？**

#### 10、定义一个类Animal，通过传参初始化它的类型，如：“猫科类”。它有一个实例方法：run，run函数体内容可自行定义。

#### 11、基于上题的Animal类，定义一个子类Cat并继承Animal类。

#### 12、举例说明什么浅拷贝。并说出深拷贝的实现方法。

### 13、加赛题：10分
谷歌中国的面试题：有 1000 个瓶子，其中 999 瓶是水，1 瓶是毒药，外观无法区别。现有 10 只小白鼠和无限多的干净试管，你怎么找出那瓶毒药？
1、ES6实现：生成长度为1000的数组，其中一位与其他999个不同，位置随机。
2、找出与众不同的数组项的位置。写出代码或思路。如果用循环解决，最大循环次数不能超过10
