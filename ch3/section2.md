# 循环优化

1. 在执行for循环之前确定最大循环数，不要把 count/strlen/sizeof 等每次都要重复做的但结果都一样的事情放到 for 循环的条件语句中，另外最好运用foreach代替for循环。
2. 禁止在循环内查询数据库，应将查询放在循环外。
3. 循环内部不宜使用`@`操作符
4. 循环内部不宜声明变量，尤其是大变量：对象，解决办法是循环之前预定义需要声明的变量。