# java基础



## git提交语句



cd 到文件夹下

git add *

git commit -m "随便写"

git remote add origin https://github.com/Plutonian-Z/Typora.git

git push -u origin master



## git加载语句



指定目录下 git clone https://github.com/Plutonian-Z/Typora.git

cd 到Typora中

git add *

git commit -m "提交信息"

git push -u origin master

== git pull --rebase origin master ==



## 核心技术卷1

### 第三章 基本程序设计结构



整型 

1. int 4字节
2. short 2字节
3. long 8字节
4. byte 1字节

浮点类型

1. float 4字节
2. double 8字节

char类型 用于表示单个字符 字符常量 采用Unicode编码

boolean类型 true false 整型与布尔型之间不能进行相互转换

变量 声明后必须用赋值语句进行初始化

常量 final关键字 只能被赋值一次 用static final类常量的定义位于main方法外部，同一个类的其他方法也能使用该常量。如果被声明为public，其他类方法也能使用该常量。

&& || ！ 与 或 非

位运算符 & | ^ ~ 与 或 异或 非   >> << 将二进制位进行右移和左移操作，分别用0和符号位填充高位

字符串String “” 

1. substring 提取子串
2. +进行拼接
3. s.equals(t)判断字符串是否相等
4. StringBuilder构造空的字符串构建器

输入输出 System.out.print("")   in.nextline()

格式化输出 与C一致  %8.2f  %d 

文件输入与输出 Scanner in = new Scanner(Path.gets("file"))

控制流程  switch  if  while  for  do while 

中断控制流语句 break continue

大数值 BigInteger BigDecimal

数组 int[] a = new int[100];

for(int element: a)          for each循环 

​	System.out.println(element);

数组拷贝 Arrays.copyof(Array, Array.length)

多维数组，不规则数组 

### 第四章 对象和类



类 封装 对象 的行为、状态、标识



























## 牛客网题目











## 练手项目 



### 小小记账本



### GUI图书馆管理系统





