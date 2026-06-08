# EX 10 Write a c program to find the sum of even digits using do-while loop
## AIM:
To write a C program to find the sum of even digits using do-while loop .
## Algorithm
1. Start. 
2. Declare variables a, sum = 0, and i = 1. 
3. Read the value of a. 
4. Repeat while i <= a: 
5. If i is even (i % 2 == 0): 
6. Add i to sum. 
7. Increment i by 1.
8. Display the value of sum. 9.Stop.
## Program:
```
#include<stdio.h>
int main()
{
    int a,sum=0;
    scanf("%d",&a);
    int i=1;
    while(i<=a)
    {
        if(i%2==0)
        {sum=sum+i;i++;}
        else
        i++;
    }
    printf("%d",sum);
}
```

## Output:

<img width="714" height="398" alt="image" src="https://github.com/user-attachments/assets/66af98ee-9bb2-48ea-8e75-97d06675f5ea" />




## Result:
Thus the program was executed and the output was verified successfully.
