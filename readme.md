# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

为您提供 CS , DS , 商科 编程作业代写

<img src="design2023866.jpg"  width="200" />

# Question 1 [20 Marks]
Write a program in MIPS32 assembly language which takes three input arguments: register
A will receive a character, register B will receive another character, and register C will receive
the initial address of a string. Within the string, your program will replace any occurrence
of the character stored in register B by the character stored in register A. Finally, output the
replaced string in register C. For example:
- Input character in register A: c
- Input character in register B: f
- Input string in register C: affording to use a silver fork
- Output string in register C: according to use a silver cork
Detailed marking rubrics can be found in Appendix 2.

Question 2 [20 Marks]
Implement a MIPS version of the following C code, including the C function strncat() and
strstr(), which is specified in the IEEE 1003.1-2017 Standard.
Your Task
Given the following C code snippet:
1 #include <stdio.h>
2 #include <string.h>
3
4 int count substr n(const char*, const char*, int);
5
6 int main() {
7 const char s1[25] = STRING 1;
8 const char s2[25] = STRING 2;
9 int n = N;
10
11 int result = count substr n(s1, s2, n);
12 printf("%d", result);
13
14 return 0;
15 }
16
17 int count substr n(const char* p1, const char* p2, int n) {
18 char p2 new[25] = STRING 3;
19 int count = 0;
20 strncat(p2 new, p2, n);
21
22 char* temp = strstr(p1, p2 new);
23 while (temp != NULL) {
24 count++;
25 temp++;
26 temp = strstr(temp, p2 new);
27 }
28
29 return count;
30 }
4
Note: To execute the code snippet above, you may need to replace the RED colored content
by syntactically correct the C code. For example:
7 char s1[10] = "Forever Shared Future";
8 char s2[10] = "revisit";
9 int n = 2;
18 char p2 new[25] = "a";
Then the program should output
1
Your are required to implement the MIPS assembly code that returns EXACTLY the same
result as executing the code snippet above. You should not change any parts in the above
code snippet, except the red colored content. No mark is awarded to this question if this
requirement is not followed.
Input:
Once you execute your MIPS code, by invoking the appropriate syscall, at the QtSpim
console your program should intake a single string in the following format (Px indicates
Parameter x):
P1:STRING 1;P2:STRING 2;P3:N;P4:STRING 3;
where the RED colored content should be replaced in the same way as the above C snippet.
For example:
P1:"Forever Shared Future";P2:"revisit";P3:2;P4:"a";
Output:
After your code is executed based on the above input, at the QtSpim console, your program
should output the corresponding result. For the example above, the output should be:
1
Exceptions:
What happens if the above C code returns an run-time error, after you supplied the input
and run? Note: a run-time error is the type of abnormality that the compiler does not
recognize, and can finish compiling; but when executing the code, the error will occur, such
as dividing by zero, and index out-of-range.
5
If the C code reports a run-time error, your MIPS code should also report a run-time error,
since your MIPS code should implement the C code. But in this coursework, your MIPS
code does not have to output exactly the same error as the C code reports. At the simulator
console, your MIPS program should only output the following message.
An error has occurred.
Again, you do not have to specify the error, but make sure your MIPS program generates
exactly this error message, when the C code generates any run-time error message.
What happens if the above C code returns an compile-time error?
My test cases will not contain inputs that lead to a compile error (or warning). It is the
job of the compiler to examine the compile error or warning, and the aim of this coursework
is not writing a compiler for error checking. In other words, you can ignore the cases that
cause compile-time errors and warnings. They will not appear in the test cases.
Resources
1. Use the built-in gcc compiler available in our cslinux server as the standard C code
behavior reference. You can copy and paste the C code above into cslinux and run, to
obtain the referential result. In other words, your program should output exactly the
same ‘count’ value (except errors) as the C code outputs under gcc in cslinux.
2. To access cslinux and the gcc inside, refer back to your labs in the PGA module. A manual
to access cslinux via X2Go is provided in the Moodle’s coursework section. Figure 1 is a
snapshot that hopefully helps you recall the usage of gcc on cslinux.
3. For remote students, if cslinux is unavailable, please use the OnilneGDB C compiler as the
reference. For remote students, if you use OnlineGDB, please register with me by sending
an email to heng.yu@nottingham.edu.cn, and attach a formal statement provided by the
FoSE faculty as the verification of your remote status. Please do so before 7th April, 2023;
otherwise I will mark your submission based on the results using cslinux.
4. Click here to refer to the formal definition of strncat() function, and here for strstr().
6
Figure 1: Demonstration of compiling and running C code on cslinux.
Evaluation
1. Out of the 20 marks for this question, TEN (10) <input, output> test cases will be
employed to evaluate the functionality of your program. Example test case:
<P1:“Forever Shared Future”;P2:“revisit”;P3:2;P4:“a”, 1>.
Each correct answer is rewarded 2 marks. Each incorrect answer is rewarded 0 mark.
Your output answer should follow exactly the output requirement given in this question,
otherwise it would be deemed incorrect.
2. Again, unless otherwise specified, we will use the gcc compiler currently available in
cslinux and onlineGDB (only for remote students) as the C code behavior reference, to
evaluate your program output.

## 作业代写价格:

|类型|美元|人民币|
|------|------|------|
|Assignment|$60-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式

微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
