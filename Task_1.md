# Question 1

## Correct code:
```
include <stdio.h>
int main()
{
     int number,LD;
     printf(" Enter a number");
     scanf("%d",&number);
     LD = number % 10; //corrected statement
     printf(" \n The Last Digit of a Given Number %d = %d", number,LD);
     return 0;
 }
 ```
 
 # Question 2
 
 ## Correct code:
 ```
int sumcal(int len, int* arr, int value)
{
    int sum = 0;
    for(int i =0 ; i< len-1; i++ )
    {
        if(arr[i]%value == 0)
        sum += arr[i]; //corrected line
    }
    return sum;
}
```


# Question 3

## Correct code:
```
#include <stdio.h>
int main()
{
for(int i=1;i <= 4;i++) //
{
for(int j=1;j <= i; j++)
{
if(i != j)
{
printf("*");
}
else
{
printf(" ");
}
}
printf("\n");
}
return 0;
}
```

# Question 4

## Correct code:
```
#include <stdio.h>
void main() {
char a='A';
a>10?printf("Yes"):printf("No");
}
```
