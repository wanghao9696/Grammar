# ########## c++面向对象 ##########

## 内存分区模式：
> ·代码区：
>> 存放函数体的二进制代码，由操作系统进行管理的
> ·全局区：
>> 存放全局变量和静态变量以及常量
> ·栈区：
>> 由编译器自动分配释放，存放函数的参数值，局部变量等
> ·堆区：
>> 由程序员分配和释放，若程序员不释放，程序结束时由操作系统释放
>> 不同区域存放的数据，赋予不同的生命周期，使能够灵活编程）
> 程序运行前：