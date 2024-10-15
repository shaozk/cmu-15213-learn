# Data Lab

数据实验



## 练习

**Problem 1.**  How many binary digits (a.k.a. bits) are needed to represent the following decimal numbers:

2, 5, 7, 10

```shell
# answer
2, 3, 3, 4
```



**Problem 2.** List the decimal numbers (between zero and eleven) where the size of the binary representation increases vs. the previous one, and show their binary representatioin.

```shell
# answer
decimal			0	1	2	3	4	5	6	7	8		9		10		11
decimal size	1	1	1	1	1	1	1	1	1		1		2		2
binary			0	1	10	11	100	101	110	111	1000	1001	1010	1011
binary size		1	1	2	2	3	3	3	3	4		4		4		4
```

```shell
# fix
2 4 8

# reason
没有理解题意，题目问的是用十进制列出那些二进制大小改变的值（从0到11区间）。
```



**Problem 3.** What is the **smallest** number that will require a certain number of bits? Give your answer in decimal.

5 bits, 6 bits, 7 bits

```shell
# answer
16, 32, 64
```



**Problem 4.** Complete the  following table to show the binary representation of the numbers 11 to 15, using your knowledge of binary patterns you explored in the previous questions.

11, 12, 13, 14, 15

```shell
# answer
1011, 1100, 1101, 1110, 1111
```



**Problem 5.** What is the decimal representation of the binary number 11001? Show your work by first showing the binary digits times the place value, and then adding them together:

```shell
# answer
2^4 + 2^3 + 2^0 = 25
```



**Problem 6.** What possible values can a single hexadecimal digit have? For example, a single bit can have the value 0 or 1, while a single decimal digit can have values between 0 and 9.

```shell
# answer
0 ... 9 a b c d e f
```

```shell
# fix
from 0 to 15

# reason
没有用正确的形式回答问题，需要用数值表示（十进制）。
```



**Problem 7.** Give the hexadecimal and decimal representations of the first number to require 3 hex digits.

```shell
# answer
Hexadecimal:	0x100
Decimal:		256
```



**Problem 8.** What is the hexadecimal representation of the decimal number 21?

```shell
# answer
0x15
```



**Problem 9.** What is the binary reresentation of the following hex number? Translate it in groups of four bits (which equal one hex digit):

```shell
# answer
0xCAFE = 1100 1010 1111 1110
0x8BAADF00D = 1000 1011 1010 1010 1101 1111 0000 0000 1101
```



**Problem 10.** What is the result of these binary operation?

``` shell
# answer
0b1010 & 0b1100 = 0b1000
0b1010 | 0b1100 = 0b1110
0b1010 xor 0b1100 = 0b0110
x = 0b10
x = (x << 2) | x = 0b1010
x = (x << 4) | x = 0b10101010
```

