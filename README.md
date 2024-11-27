##实验一 数据类型、运算符与表达式 
##一、实验目的
1、了解算法的概念、特性、算法在程序设计中的地位。 
2、熟悉算法的表示方法。 
3、掌握用流程图表示一个算法。 
4、能独立设计一个问题的算法,并根据该算法编出问题的程序。 
5、掌握C语言数据类型，熟悉如何定义一个整型、字符型和实型变量，以及对它们赋值的方法，了解以上类型数据输出时所用的格式转换符。 
6、学会使用C的有关算术运算符，以及包含这些运算符的表达式，特别是自加、自减运算符的使用。 
7、进一步熟悉C程序的编辑、编译、连接和运行的过程。 
##二、实验准备 
1、复习算法的概念和特性。 
2、复习算法的几种表示方式。
3、复习C语言的数据类型。 
4、复习各种运算符和表达式。 
##三、实验内容 
1、运行程序并回答问题: 
#include<stdio.h> 
int main() 
{ 
printf("%c", '/007'); 
return 0; 
} 
问题:如果执行printf("%c＂,'0x7')会得到什么结果?为什么? ![image](https://github.com/user-attachments/assets/19d85c35-323a-4e49-a86e-2815704f75c2)

7，因为x是十六进制，7比16小所以不进位 
#include<stdio.h> 
void main() 
{ 
char c1, c2;
 c1 = getchar(); 
c2 = getchar();
 putchar(c1);
 putchar(c2); 
return 0; 
} 
问题：把c1，c2定义成整型变量是否可以？为什么？采用同样的输入值观察结果。 可以 char:![image](https://github.com/user-attachments/assets/d0326667-63fa-4a1d-bb22-6549e1ebc998)
 int: ![image](https://github.com/user-attachments/assets/0635c0f8-bdea-4fc8-90d2-79eb85017e48)

2、输人程序并运行:
 #include<stdio.h> 
void main()
 { 
char c1, c2; 
c1 = 97; 
c2 = 98; 
printf("%c %c\n", c1, c2);
 return 0; 
} 
在此基础上: ·加printf("%d,%d",c1,c2)；运行。 ·![image](https://github.com/user-attachments/assets/13d804cb-d6b0-423e-9f01-43b6acd71e61)

将第二行改为:int c1,c2；运行。 ![image](https://github.com/user-attachments/assets/dbc18002-42ab-40fe-bc64-113bc348ecf4)

·将第三行改为:c1=300;c2=400;运行。![image](https://github.com/user-attachments/assets/b755bc99-c494-4cc1-a933-fd78c113e924)

3、输入程序并运行： 
#include<stdio.h> 
void main() 
｛ 
char c1='a',c2='b',c3='c',c4='\101' ,c5='\116';
 printf("a%cb%c\tc%c\tabc\n" ,c1,c2,c3);
printf("\t\b%c%c",c4,c5); 
return 0; 
}
![image](https://github.com/user-attachments/assets/acc9edf7-f4bb-4569-a0c9-9cb3b5f7472d)

