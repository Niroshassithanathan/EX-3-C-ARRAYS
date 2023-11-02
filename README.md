# EX-3-C-ARRAYS
## AIM :
Create a C program to read n elements as input and print the first three elements of an array.
## ALGORITHAM :
1.Start

2.Declare variables for 'n' (number of elements) and an array (arr) to store the elements.

3.Prompt the user to enter 'n' (the number of elements) and read it into the 'n' variable.

4.Initialize a loop counter 'i' to 0.

5.Print the first three elements of the 'arr' array.

6.End.
## PROGRAM :
```
#include<stdio.h>
int main(){
int i,n,a[5];
scanf("%d",&n);
for(i=0;i<n;i++) {
scanf("%d",&a[i]);
}
for(i=0;i<n;i++)
{ printf("%d
",a[i]);
}
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-3-C-ARRAYS/assets/121418437/022ae126-d765-4d8f-b0f2-1f6f3fce3ff9)

## RESULT :
Thus , The C program has been executed successfully.
