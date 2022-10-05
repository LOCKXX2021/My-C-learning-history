# C data _type_size

## int 

### short(int) 

```
printf("%d/n",sizeof(short int a))
```

```
2
```

short 整形占字节为2，为16bit，范围为-32768-32767

初始化占位符为%d

### int

```c
printf("%d\n",sizeof(int a));
```

```
4
```

int 整形占字节为4，为32bit

初始化占位符为%d

### **long(int)**

```c
printf("%d\n",sizeof(long a));
```

```
4
```

**在qt环境中,long 占4byte，为32bit,即qt为32位环境**

初始化占位符为%ld

### long long 

```c
printf("%d\n",sizeof(long long a));
```

```
8
```

在Qt环境中，long long 占8byte，为64bit

## float

### float

```c
printf("%d\n",sizeof(float a));
```

```
4
```

float类型占内存高，无短类型，占byte为4，32bit

**默认保留小数点后六位**

初始化占位符为%f

### double(float)

```c
printf("%d\n",sizeof(double a));
```

double 类型为双浮点数，占8byte,64bit,与long long相同

**默认保留小数点后六位**

初始化占位符为%lf

## char

```c
printf("%d\n",sizeof(char a));
```

char类型为字符串类型，占1byte

初始化占位符为%c