[TOC]

![image-20230226101345215](assets/image-20230226101345215.png)

toString（）和Objects的无关

包头不包尾

```java
Arrays.copyOf(arr, 3)//超过数组个数，自动补充默认值
```

![image-20230226111153382](assets/image-20230226111153382.png)

![image-20230226111319328](assets/image-20230226111319328.png)

![image-20230226112426987](assets/image-20230226112426987.png)

# 算法

## 1、二分查找

前提条件：数据有序，每次排除一半

步骤：

- 左右指针相加/2，记录中间数据

- 判断中间数据和查找数据范围

- 根据数值范围修改指针

- 左右指针位置交换，不存在left《= rigtht

  

## 2、面试题int超范围相加

![image-20230226121853977](assets/image-20230226121853977.png)

## 3、冒泡排序

### 两两比较（三种数值换位置，）

![image-20230310181022722](assets/image-20230310181022722.png)

![image-20230310181127865](assets/image-20230310181127865.png)

![image-20230310181259629](assets/image-20230310181259629.png)

![image-20230310174931378](assets/image-20230310174931378.png)

![image-20230310180409102](assets/image-20230310180409102.png)

if中的j位置

## 4、选择排序

# 正则表达式

![image-20230226144726961](assets/image-20230226144726961.png)

![image-20230226150554538](assets/image-20230226150554538.png)

![image-20230226151927987](assets/image-20230226151927987.png)

# 异常Throwable

## Error

![image-20230226165010728](assets/image-20230226165010728.png)

## Exception

![image-20230226165223710](assets/image-20230226165223710.png)

![image-20230226165717367](assets/image-20230226165717367.png)

#### 异常流程

![image-20230226170616775](assets/image-20230226170616775.png)

![image-20230226171322667](assets/image-20230226171322667.png)

==继承方法重写，父类没有异常，子类只能try catch，接口也是一个样子==

![image-20230226173932693](assets/image-20230226173932693.png)

#### 自定义异常

分为两类

![image-20230226175532844](assets/image-20230226175532844.png) 

## try-catch-finally