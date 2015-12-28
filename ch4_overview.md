# 概述

这一节包含一份不规范的ECMAScript语言。

ECMAScript是一种面向对象的语言，它在一个主机环境中处理计算及操作可计算的对象。这里定义的ECMAScript不是想要成为可计算的自立；实际上，在这份规范里没有提供外部数据的输入和计算结果的输出。作为代替，它期望这个可计算的ECMAScript程序环境会提供，不仅是这份规范里描述的对象和其它设施，还包含环境相关的主机对象，这些主机对象的描述和行为超出了这份规范的范围，除了指出它们提供的一些ECMAScript程序可访问的属性和可调用的函数。

脚本语言是一种在现有系统上操作，定制和自动化的编程语言。在这种系统中，有用的功能已经以用户接口的方式可用，脚本语言是一种把这些功能暴露给程序控制的机制。用这种方式，已经存在的系统被认为是提供一个对象和设施的主机环境，来完善脚本语言的能力。脚本语言想要同时被有经验和无经验的程序员使用。

ECMAScript 起初被设计为一种网页脚本语言，提供使浏览器中的网页更加生动的机制和基于web的客户端-服务端架构的服务通信。ECMAScript可以给各种主机环境提供核心的脚本功能，因此这份规范的核心脚本语言不针对一种特殊的主机环境。

一些 ECMAScript 的设施和其它一些编程语言很相似；特别是如下描述的Java<sup>TM</sup>， Self和Scheme：

Gosling, James, Bill Joy and Guy Steele. Java<sup>TM</sup>语言规范，Addison Wesley Publishing Co., 1996.

Ungar, David, and Smith, Randall B. Self: The Power of Simplicity. OOPSLA '87 Conference Proceedings, pp. 227-241, Orlando, FL, October 1987.

IEEE Standard for the Scheme Programming Language. IEEE Std 1178-1990.
