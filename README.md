# Task02
프로그래밍응용 | 과제2 - 프로그래밍4

/********************
- 4장 프로그래밍 실습
- 3번 문제
********************/

#include <stdio.h>

int main(void)
{
	int x;
	int y;
	int z;
	x = 10;
	y = 20;
	z = x;

	printf("x=%d y=%d\n", x, y);
	printf("x=%d y=%d", y, z);
}

/********************
- 4장 프로그래밍 실습
- 8번 문제
********************/

#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int code;

	printf("아스키 코드값을 입력하시오:");

	scanf("%d", &code);

	printf("문자:%c입니다.", code);
	return 0;
}

/********************
- 4장 프로그래밍 실습
- 9번 문제
********************/

#define _SRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	char a;
	a = 97;

	printf("%c %c %c", a + 1, a + 2, a + 3);
	return 0;
}
