# 语言概述

下面是 ECMAScript 的概述信息，没有描述所有部分的语言规范。这个概述不是标准本身的一部分。

ECMAScript 是基于对象的，基本的语言和宿主设施以对象的形式提供，ECMAScript 程序是一组相互通讯的对象。一个 ECMAScript**对象**是一组**属性**(properties)，每个属性有零个或多个**特性**(attributes)组成，特性决定属性如何被使用。例如，当属性的可写特性被设置为**false**时，任何尝试改变属性值的 ECMAScript 代码都会失败。属性也是保存其它对象的容器，**原始类型**或**函数**，一个原始类型是以下几种内置类型之一：**Undefined**,**Null**,**Boolean**,**Number**和**String**；一个对象是剩下的内置类型**Object**的成员；函数是一个可调用的对象。一个通过对象属性相关的函数是一个**方法**。

ECMAScript 定义了一组内置的对象，完成 ECMAScript 实体的定义。这些内置对象包含**global**对象，**Object**对象，**Function**对象，**Array**对象，**String**对象，**Boolean**对象，**Number**对象，**Math**对象，**Date**对象，**RegExp**对象，**JSON**对象，和错误对象**Error**，**EvalError**，**RangeError**,**ReferenceError**,**SyntaxError**,**TypeError**和**URIError**。

ECMAScript 同时也定义了一组内置**运算符**，ECMAScript运算符包含，一元运算符，算法运算符，加法运算符，位移运算符，关系运算符，相等运算符，二进制位运算符，二进制逻辑运算符，赋值运算符和逗号运算符。

ECMAScript 的语法故意像Java的语法。ECMAScript 的语法设计成容易使用的脚本语言。例如，一个变量不需要定义其类型，同样属性的类型也不需要，并且函数也不需要在调用的位置前定义他们。
