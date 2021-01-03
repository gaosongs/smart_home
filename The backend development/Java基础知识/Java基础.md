# Java基础

- Java特点
- Java语法
- Java开发环境

## 1. Java的主要特点

Java是一种简单的、面向对象的、分布式的、编译与解释性、健壮性、安全性、可移植性、高性能、多线程和动态的编译语言。

## 2. Java语法
### 2.1 数据类型

> Java的基本的数据类型简单概括为4类八种。

1. 整数类型
   - byte:8位，有符号的整数，-128~127，默认为0
   - short:16位，有符号的整数，-32768~32767,默认为0
   - int:32位，有符号整数，-2 的31次幂~2的31次幂-1，默认为0（常用）
   - long:64位，有符号的整数，-2 的63次幂~2的63次幂-1，默认为0L
2. 浮点类型
   - float:单精度类型，32位，默认值0.0F
   - double:双精度浮点类型，64位，默认值0.0D
3. 字符类型
   - char:char类型是一个单一的16位Unicode字符
4. 布尔类型
   - boolean:表示一位信息，只取两个值，true和false

### 2.2 标识符

> Java的类名、变量名及方法名都称之为标识符。

- 标识符限定：
  1. 标识符必须由字母、美元符、下划线开头
  2. 首字母之后可以由字母、数字、美元符号、下划线任意组合
  3. 标识符不可是Java的关键字或者保留字
  4. 标识符是区分大小写的
- 建议（约定俗称）：
  1. 命名类名时每个单词首字母大写，如HelloWorld;
  2. 变量名和方法名时通常第一个单词的首字母小写，采用驼峰命名法（小驼峰命名法），如helloWorld
  3. 常量命名通常是所有字母都大写，如MAX,有多个单词的时候用下划线分隔开，如MAX_SIZE

### 2.3 修饰符

> Java的修饰符主要用来修饰类、方法、属性，有两类修饰符。

1. 访问控制修饰符

   > 包括public、private、protected、default(没有修饰符)

   | 访问级别 | 访问控制修饰符 | 同类  | 同包  | 子类  | 不同包 |
   | -------- | -------------- | ----- | ----- | ----- | ------ |
   | 公开     | public         | **√** | **√** | **√** | **√**  |
   | 受保护   | protected      | **√** | **√** | **√** |        |
   | 默认     | default        | **√** | **√** |       |        |
   | 私有     | private        | **√** |       |       |        |

2. 非访问控制修饰符

   > 包括final、abstract、static、volatile、synchronized、native、transient

### 2.4 变量

> 1. 类变量：独立于方法之外的变量，用static修饰。
> 2. 实例变量：独立于方法之外的变量，不用static修饰。
> 3. 局部变量：方法中的变量。

### 2.5 运算符

1. 算数运算符

   | 运算符 | 运算       | 范例       | 结果 |
   | ------ | ---------- | ---------- | ---- |
   | +      | 正号       | +3         |      |
   | -      | 负号       | b=4;-b     |      |
   | +      | 加号       | 5+5        |      |
   | -      | 减号       | 6-4        |      |
   | *      | 乘号       | 3*4        |      |
   | /      | 除号       | 5/5        |      |
   | %      | 取模       | 7%5        |      |
   | ++     | 自增（前） | a=2;b=++a  |      |
   | ++     | 自增（后） | a=2;b=a++  |      |
   | --     | 自减（前） | a=2;b=--a  |      |
   | --     | 自减（后） | a=2;b=a--  |      |
   | +      | 字符串相加 | “He”+"llo" |      |

2. 赋值运算符

   | 运算符 | 运算                   | 范例         | 结果 |
   | ------ | ---------------------- | ------------ | ---- |
   | =      | 等于：直接赋值         | c=1+2        |      |
   | +=     | 加等于：先运算在赋值   | a=1;b=2;b+=a |      |
   | -=     | 减等于：先运算在赋值   | a=1;b=2;b-=a |      |
   | /=     | 除等于：先运算在赋值   | a=1;b=2;b/=a |      |
   | %=     | 取模等于：先运算在赋值 | a=2;b=3;b%=a |      |

3. 比较运算符

   | 运算符     | 运算                       | 范例                      | 结果（boolean） |
   | ---------- | -------------------------- | ------------------------- | --------------- |
   | ==         | 相等                       | 4==3                      |                 |
   | !=         | 不等于                     | 4!=3                      |                 |
   | <          | 小于                       | 4<3                       |                 |
   | >          | 大于                       | 4>3                       |                 |
   | <=         | 小于等于                   | 4<=3                      |                 |
   | >=         | 大于等于                   | 4>=3                      |                 |
   | instanceof | 检查是否是某一个类的、对象 | "hello" instanceof String |                 |

4. 位运算符

   | 运算符 | 运算       | 说明                                                         |
   | ------ | ---------- | ------------------------------------------------------------ |
   | <<     | 左移       | 被移除的高位丢弃，空缺位补0                                  |
   | >>     | 右移       | 被移除的二进制最高位是0，右移后，空缺位补0；被移除的最高位是1，空缺位补1 |
   | >>>    | 无符号右移 | 被移除的最高位无论是0还是1，空缺位都补0                      |
   | &      | 与运算     | 只有1&1=1，其余结果皆为0                                     |
   | \|     | 或运算     | 只有0&0=0，其余皆为1                                         |
   | ⋀      | 异或运算   | 相同结果为0；不同结果为1                                     |
   | ~      | 反码       | 正数（原码、反码、补码）相同，负数取反的补码+1               |
   
5. 三元运算符

   > (条件表达式)？表达式1：表达式2
   >
   > 条件表达式运算结果为true,运算的结果为表达式1；
   >
   > 条件表达式运算结果为false,运算的结果为表达式2

### 2.6 关键字

<table border="1" width="800px">
    <tr>
        <td>分类</td>
        <td>关键字</td>
        <td>说明</td>
    </tr>
    <tr>
        <td rowspan="3">访问控制</td>
        <td>public</td>
        <td>公有的</td>
    </tr>
    <tr>
        <td>private</td>
        <td>私有的</td>
    </tr>
    <tr>
        <td>protected</td>
        <td>受保护的</td>
    </tr>
    <tr>
        <td rowspan="14">类、修饰符</td>
        <td>abstract</td>
        <td>抽象的</td>
    </tr>
    <tr>
        <td>class</td>
        <td>类</td>
    </tr>
    <tr>
        <td>extends</td>
        <td>继承</td>
    </tr>
    <tr>
        <td>implements</td>
        <td>实现(接口)</td>
    </tr>
    <tr>
        <td>interface</td>
        <td>接口</td>
    </tr>
    <tr>
        <td>enum</td>
        <td>枚举</td>
    </tr>
    <tr>
        <td>final</td>
        <td>最终的，不可改变的</td>
    </tr>
    <tr>
        <td>native</td>
        <td>本地，原生方法</td>
    </tr>
    <tr>
        <td>new</td>
        <td>创建</td>
    </tr>
    <tr>
        <td>static</td>
        <td>静态</td>
    </tr>
    <tr>
        <td>strictfp</td>
        <td>严格，精准</td>
    </tr>
    <tr>
        <td>transient</td>
        <td>短暂的</td>
    </tr>
    <tr>
        <td>volatile</td>
        <td>易变的</td>
    </tr>
    <tr>
        <td>synchronized</td>
        <td>同步线程</td>
    </tr>
    <tr>
        <td rowspan="6">程序控制</td>
        <td>for</td>
        <td>循环</td>
    </tr>
    <tr>
        <td>break</td>
        <td>跳出循环</td>
    </tr>
    <tr>
        <td>continue</td>
        <td>继续下一次循环</td>
    </tr>
    <tr>
        <td>do</td>
        <td>运行</td>
    </tr>
    <tr>
        <td>while</td>
        <td>循环</td>
    </tr>
    <tr>
        <td>switch</td>
        <td>选择</td>
    </tr>
    <tr>
        <td rowspan="5">程序控制</td>
        <td>case</td>
        <td>定一个值供switch选择</td>
    </tr>
    <tr>
        <td>default</td>
        <td>默认</td>
    </tr>
    <tr>
        <td>if</td>
        <td>如果</td>
    </tr>
    <tr>
        <td>else</td>
        <td>否则</td>
    </tr>
    <tr>
        <td>return</td>
        <td>返回</td>
    </tr>
    <tr>
        <td rowspan="6">异常处理</td>
        <td>try</td>
        <td>捕获异常</td>
    </tr>
    <tr>
        <td>catch</td>
        <td>捕捉异常</td>
    </tr>
    <tr>
        <td>finally</td>
        <td>必须执行</td>
    </tr>
    <tr>
        <td>throw</td>
        <td>抛出一个异常</td>
    </tr>
    <tr>
        <td>throws</td>
        <td>声明一个异常可能被抛出</td>
    </tr>
    <tr>
        <td>assert</td>
        <td>断言</td>
    </tr>
    <tr>
        <td rowspan="2">包</td>
        <td>import</td>
        <td>导入</td>
    </tr>
    <tr>
        <td>package</td>
        <td>包</td>
    </tr>
    <tr>
        <td rowspan="8">数据类型</td>
        <td>byte</td>
        <td>字节型</td>
    </tr>
    <tr>
        <td>short</td>
        <td>短整型</td>
    </tr>
    <tr>
        <td>int</td>
        <td>整型</td>
    </tr>
    <tr>
        <td>long</td>
        <td>长整型</td>
    </tr>
    <tr>
        <td>float</td>
        <td>单精度浮点类型</td>
    </tr>
    <tr>
        <td>double</td>
        <td>双精度浮点类型</td>
    </tr>
    <tr>
        <td>char</td>
        <td>字符型</td>
    </tr>
    <tr>
        <td>boolean</td>
        <td>布尔型</td>
    </tr>
    <tr>
        <td rowspan="3">变量引用</td>
        <td>super</td>
        <td>父类（超类）</td>
    </tr>
    <tr>
        <td>this</td>
        <td>本类</td>
    </tr>
    <tr>
        <td>void</td>
        <td>无返回值</td>
    </tr>
    <tr>
        <td rowspan="3">保留关键字</td>
        <td>null</td>
        <td>空</td>
    </tr>
    <tr>
        <td>const</td>
        <td>是关键字,但是不能使用</td>
    </tr>
    <tr>
        <td>goto</td>
        <td>是关键字,但是不能使用</td>
    </tr>
</table>


### 2.7 注释

> 1. 单行注释：//
>2. 多行注释：/* 。。。。*/
> 3. 文档注释：/* *  。。。。* / (markdown显示有点问题)

## 3.Java开发环境

### 3.1 JDK

### 3.2 JRE

### 3.3 JVM

jdk>>jre>>jvm

### 3.4 配置环境变量

1. 新建JAVA_HOME变量,变量值为jdk的安装目录。

2. 在path变量末尾添加  （;%JAVA_HOME\bin%;）

3. 检查是否配置成功

   ```java
   java -version
   ```

   