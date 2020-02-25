https://www.acmicpc.net/problem/10886

```c++
#include <stdio.h>
int main(void)
{
	int n = 0;
	int i = 0;
	scanf("%d", &n);
	int cute = 0;
	int notc = 0;
	while (n != 0)
	{
		scanf("%d", &i);
		if (i == 1)cute++;
		else notc++;
		n--;
	}
	if (cute > notc)printf("Junhee is cute!");
	else printf("Junhee is not cute!");
}
```

