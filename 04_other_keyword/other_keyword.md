# 其他关键字

## sizeof

### 测量变量、数组的大小

```c

int a = 10;

int num;

num = sizeof(a);
```



## typedef

### 重命名相关的关键字

定义已有关键字

```c
//typedef oldtype newtype;   

typedef short int    INT16;
```

### volatile

### 修饰易改变的变量

每次调用都调用内存中最新的值而非寄存器中的数据