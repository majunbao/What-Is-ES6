## 你是根据什么规范版本写的这些？
* ECMAScript 6.0 版本
* 在这里可以访问它：[http://www.ecma-international.org/ecma-262/6.0/](http://www.ecma-international.org/ecma-262/6.0/)

## 什么是 Types ？
* 在ECMAScript规范中操作values（值）的每个算法都有相关联的type。这些可能的value types都定义在了这个规范中。
* Types又可分为：`ECMAScript language types`和`specification types`。

## 什么是 ECMAScript language types？
* 一个 ECMAScript language type 相当于 values，ECMAScript 程序员通过 ECMAScript language 可以直接操作它。
* ECMAScript language typs 又可分为：`Undefined`，`Null`，`Boolean`，`String`，`Number`，`Object`。

### 什么是 Undefined Type？
* Undefined type 只有一个 value，叫做 undefined（注意开头字母是小写）。
* 任何没有分配value 的 variable(变量) 都有一个 value 是 undefined 。

### 什么是 Null Type？
* Null type 只有一个 value，叫做 null（注意是小写）。

### 什么是 Boolean Type？
* Boolean type 是一个logical entity（逻辑实体），它有两个值，`true` 和 `false`。

### 什么是 String Type？
* String Typs 是零个或者多个 16-bit unsigned integer values (“elements”) 的 finite ordered sequences（有限命令序列）的 set（集合）。
* 简单说 String Typs 是set（集合）。

#### 什么是set？

#### 什么是 bit？
* bit是信息技术和网络通信的基本单元。一个 bit 只有两个 values，这些 values 通常表示为 0 或 1。bit 这个单词是 binary digit（二进制）的 portmanteau（混合词）。


##### 什么是 portmanteau（混合词）？
* portmanteau 译为混合词，所谓混合词是由两个词提取他们的一部分组合成一个新的单词。例如 中国几个省份的名字就是混合词。安徽是安庆和徽州的简拼，甘肃是甘州和肃州的简拼，江苏是江宁（南京的古代名字）和苏州的简拼。
* portmanteau 也可翻译为旅行箱。旅行箱可以打开成两个相等的部分，很形象。
* 参考资料：[Portmanteau](https://en.wikipedia.org/wiki/Portmanteau)

#### 什么是 16-bit？
* 计算机一般在一个固定的大小内操作bit，这通常称`word`。例如 byte。
* byte 是 Werner Buchholz在1956年创造的。他设计的计算机，最小可操作单位是byte，每个byte就是8个bit的有序序列，即2得8次方，256种可能。
* 通常计算机最小可操作单位是8-80bit，当然也有特殊的。21世纪以来，常用的计算机是16/64-bit。
* 16-bit 就是每个 `word` 是 16个bit，每个 `word` 都可代表65536种可能（2的16次方）。
* 参考资料：[bit](https://en.wikipedia.org/wiki/Bit)，[16-bit](https://en.wikipedia.org/wiki/16-bit)，[Werner Buchholz](https://en.wikipedia.org/wiki/Werner_Buchholz)

### 什么是 Number Type？
* Number Type 有不多不少 18437736874454810627（2^64−2^53+3） 个values。

### 什么是 Object Type？

## 什么是 specification type？

一个bit的功能很少，一般只能实现开和关这么简单的功能，所以