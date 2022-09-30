## 乘法运算：
<<<<<<< HEAD
##### 1.二进制基础乘法器：
![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/乘法器(1)_页面_1.jpg)![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/乘法器(1)_页面_2.jpg)
##### 2.改进版的二进制乘法器：
![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/乘法器(1)_页面_3.jpg)![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/2134DF73B71B9334D2C1E924AF94AF19.png)
=======
##### 1.二进制的乘法运算：
- 二进制的乘法运算和十进制的乘法运算相同，都能够采用列竖式的方式进行。
- 二进制的乘法运算更为简单，原因是只有1 x 1，1 x 0，0 x 0这三种情况。
- 下面将使用列竖式乘法的方式计算二进制：1000 x 1001
```
	 1000
	x
	 1001
	——————
	 1000
	0000
   0000
  1000
  ————————
  1001000	 
```
- 观察上面这个二进制的乘法运算：
	- 我们定义被乘数是1000，乘数是1001。
	- 我们可以从上面这个二进制乘法运算中发现一些算法从而将乘法运算转换成加法运算。
	- 乘数每次向右移动一位，并且我们只需要乘数的最右一位。被乘数每次向左移动一位。
		- 1.首先，乘数的最右一位是1，把被乘数放到一个寄存器a中。
		- 2.其次，右移乘数，左移被乘数。
		- 3.此时乘数最右一位为0，因此继续右移乘数，左移被乘数。
		- 4.此时乘数的最右一位依旧为0，因此继续右移乘数，左移被乘数。
		- 5.此时乘数的最后一位是1，把此时的被乘数加到寄存器a中。
		- 6.此时寄存器a中的结果就是二进制乘法运算的结果。
##### 2.根据上面的二进制乘法算法设置我们的乘法器：
![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/Page1(1)_页面_1.jpg)

![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/Page1(1)_页面_2.jpg)

![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/Page1(1)_页面_3.jpg)

![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/Page1(1)_页面_4.jpg)

![](https://nickaljy-pictures.oss-cn-hangzhou.aliyuncs.com/Page1(1)_页面_5.jpg)
>>>>>>> d248944 (The third commit and Chapter 03)
