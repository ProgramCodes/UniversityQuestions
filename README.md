# Introductory Programming Courses

Examples and questions are all addressed in university classes.
Use them to practice and enhance your ability.

I hope they will be useful for university professors and student.

Write a program that :
------------------

## 1th Section

### 1.1 
Displays the hello text.
*Answer(s) :*
```
#include<stdio.h>
int main()
{
	printf("Hello!");
	return 0;
}
```


```
#include<stdio.h>
int main()
{
	printf("Hello!\n");
	return 0;
}
```


## 1.2
Displays the 6-star icon.
*Answer(s) :*
```
#include<stdio.h>
int main()
{
	int n;
	n = 0 ;
	while(n<6)
	{
		printf("*");
		n = n + 1;
	}
	return 0;
}
```


```
#include<stdio.h>
int main()
{
	printf("***");
	printf("***");
	return 0;
}
```



```
#include<stdio.h>
int main()
{
	printf("******\n");
	return 0;
}
```


## 2th Section

### 2.1
Get two integers of the user.
Numbers are the length of a parallelogram length.
Display the shape using the '*' symbol.

### 2.2
Get two number from user.
And draw a trapezius.
Both numbers must be greater than 0.
If the condition is not satisfied, retrieve the number from the user.
Draw a shape using the * symbol.

### 2.3

Get an odd number greater than 4 from the user.
For example, if the user enters number 5.
Show a 5 * 5 square using the * symbols.
There is also a triangle on top of the square.

