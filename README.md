# Python入门
**要点回顾：**

### **Date: 1/6/2022**

 **要点回顾：**

- 变量
    - 变量/变量值/内存位置：
        - 计算机的核心功能是计算，CPU是负责计算的，计算需要数据源，数据源要存在内存里，然后后面的程序才能调用
    - 变量定义规则：
        - 变量的组成必须由字母，数字或者下划线的任意组合
        - 变量名称的第一个字符不能是数字
        - 尽量不用关键字命名变量
    - 变量的删除和修改
        - name=”alex”, name2=name, name2只是refer “alex”, 若name=”zoey”, name2=”alex”不变
- 基本数据类型
    - Python的数据类型：整数/浮点/字符串/布尔/列表/元祖/字典/集合
    - 数字类型
        - int(整型）
        - float(浮点）
    - 字符串：在py中，所有加了引号的都可以被认为是字符串
        - 单引号双引号没有区别
        - 多引号 引用多行字符串
        - 字符串的拼接：
            - 字符串的拼接只能是双方都是字符串，不能和其他类型进行拼接
            - 数字可以进行加减乘除运算，字符串只能进行+和*
    - 布尔类型
    - 列表
        - 列表中的字符叫做元素，列表是通过下标来标记元素的位置的，下标从0开始
        - 常见的用法
            - 插入变量： insert(第几个前,插入什么””)
            - 增加变量：append(””)
            - 删除：del
            - 列表中独有的删除方式：remove () 从左边开始删，如果有重复值，只能删除一个
            - 判断：in
- 常用的运算符
    - 常用运算符
        - %：取模运算-返回余数，可以判断奇偶
        - **：幂：返回x的y次幂
        - //取整除：返回商的整数部分
    - 比较运算符
        - <>不等于在py3中已经取消了
    - 赋值运算符
        - = 赋值运算
        - += 加法赋值运算 c+=a: c=c+a
        - -= 减法赋值运算 c-=a: c=c-a
        - *= 乘法赋值运算 c*=a: c=c*a*
        - /= 除法赋值运算 c/=a: c=c/a
        - %= 取模赋值运算 c%a: c=c%a
        - **= 幂赋值运算 c** =a: c=c**a
        - //= 取整除赋值运算符 c//=a: c=c//a
    - 逻辑运算符
        - and/or/not
        - or/and 可以拼在一起
        - or的优先级高于and
- Pycharm编辑器
    - command+d 可以复制粘贴
    - command+？可以多行注释
- 读取用户输入
    - input()只能读取字符串
    - f””””“”：可以读取外部引用的变量
- 流程控制
    - 单分支：缩进的归属关系
    - 双分支： if/else

### Date：Jan 8

**要点回顾**

- for 循环：
    - for in in range()
- break/ continue
    - break
        - 结束当前循环 eg. 如果有两层循环嵌套仅结束当前的
        - break 用于完全结束一个循环，跳出循环体执行循环后面的语句
    - continue
        - 和break类似，区别在于终止本次循环，接着还执行后面的循环，break 则完全终止
        - 可以理解为continue是跳过当次循环中剩下的语句，执行下一次循环
    - while循环
        - 如果不加限制是死循环
        - 用法和for 一样，可以添加break和continue
 - random 模块 生成随机数
    - import random
    - random.choice(‘abcde’) 参数也可以是一个列表，随机选出一个值
    - random.sample(S, 3) 从数据源S中随机取出3个值
    - random.randint(1,100) 打印一个随机数
- string 模块
    - import string
    - string.ascii_letters 打印字母
    - string.ascii_uppercase #大写字母
    - string.ascii_lowercase #小写字母
    - string.punctuation #打印特殊字符
### Date Jan 9

**要点回顾：**

- 字符串的特性
    - 有序，下标从0开始
    - 可进行切片操作
        - S[3,6] →顾头不顾尾
    - 不可变，不可以进行修改
- 常用操作
    - [str.center](http://str.center)(50,”-”) →output:—— ———
    - str.count(”l”,0,4)
    - str.endwith(”00”) →判断结尾
    - str.startwith(”00”)→判断开头
    - str.find() →字符查找
    - str.isdigit() →判断是否是整数
    - “-”.join(str) →以怎样的形式拼接字符串
    - 步长：str[0::2]
        - 中间用冒号隔开
        - 步长=2时，跳过2-1个数
- 列表的反转与排序
    - str.reverse()
    - str.sort()
    - str.log()
 
