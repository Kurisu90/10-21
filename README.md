# 10-21
//第一题

#include<stdio.h>

#include<math.h>

int main() {

double a, b, c;

printf("请输入三角形三边长：");

scanf("%lf%lf%lf", &a, &b, &c);

if (a + b > c && a + c > b && b + c > a) {

printf("三角形存在。");

double C, S;

printf("三角形的周长为:%lf\n", a + b + c);

double p = (a + b + c) / 2;

S = sqrt(p * (p - a) * (p - b) * (p - c));

printf("三角形的面积为:%lf", S);

}

else {

printf("三角形不存在。");

}



}

运行结果：1.

请输入三角形三边长：3 4 5

三角形存在。

三角形的周长为:12.000000

三角形的面积为:6.000000

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 15224)已退出，代码为 0。

按任意键关闭此窗口. . .

2.

请输入三角形三边长：1 1 3

三角形不存在。

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 49392)已退出，代码为 0。

按任意键关闭此窗口. . .





//第二题

#include<stdio.h>

#include<math.h>

int main() {

double a, b, c;

printf("请依次输入一元二次方程的a,b,c：");

scanf("%lf%lf%lf", &a, &b, &c);

double deta = b * b - 4 * a * c;

double answer1, answer2;

if (deta<0) {

printf("该方程无解！");

}

else if (deta == 0) {

printf("该方程有两个相同解。\n");

answer1 = (-b) / 2*a;

printf("两个解均为%lf", answer1);

}

else {

printf("该方程有两个不同解。\n");

answer1 = (-b + sqrt(deta)) / (2 * a);

answer2 = (-b - sqrt(deta)) / (2 * a);

printf("两个解分别是%lf\t   %lf", answer1, answer2);

}

}

运行结果：

1.请依次输入一元二次方程的a,b,c：1 -2 1

该方程有两个相同解。

两个解均为1.000000

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 18868)已退出，代码为 0。

按任意键关闭此窗口. . .



2.

请依次输入一元二次方程的a,b,c：1 1 1

该方程无解！

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 12332)已退出，代码为 0。

按任意键关闭此窗口. . .



3.

请依次输入一元二次方程的a,b,c：1 -3 2

该方程有两个不同解。

两个解分别是2.000000       1.000000

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 13044)已退出，代码为 0。

按任意键关闭此窗口. . .



//第三题

#include<stdio.h>

int main() {

char a;

printf("请输入一个大写字母：");

scanf("%c", &a);

printf("%c", a + 32);

}



运行结果：

请输入一个大写字母：A

a

C:\Users\86188\source\repos\Project47\x64\Debug\Project47.exe (进程 52128)已退出，代码为 0。

按任意键关闭此窗口. . .





