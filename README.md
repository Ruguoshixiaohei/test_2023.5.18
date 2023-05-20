#include<stdio.h>
#include<string.h>

int main()
{
  printf("判断一个数是否为奇数\n")
	int a = 0;
    scanf_s("%d", &a);
	int b = a % 2;
	if (1 == b)
		printf("奇数");
	else
		printf("偶数");
	return 0;
