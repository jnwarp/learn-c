learn c
-------

This is a simple repository for me to play around with learning C

Language
========

### Coding conventions

- Tabs not spaces
- Brackets on separate line

```c
#include <stdio.h>

int main()
{
	printf("Hello world\n");
	return 0;
}
```

### Variables

- int
- double
- float

```c
#include <stdio.h>

int main() {
	int a = 1;
	float b = 2.1;
	
	double sum;
	sum = a + b;

	printf("Sum of %d + %f is %f.", a, b, sum);
	return 0;
}
```

### Arrays
```c
int main() {
	int num_array[10];
	num_array[0] = 1;
	printf("1st element: %d", num_array[0]);
	return 0;
}
```
