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
for(int i=1;i <= 4;i++) //corrected line
{
for(int j=1;j <= i; j++) //corrected line
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
a>10?printf("Yes"):printf("No"); //corrected line
}
```
# Question 5

## Correct code:
```
#include <iostream>
using namespace std;
int main() {
int o, i, s; //corrected line
for(o=5; o>=1; o--) 
{
for(s=1; s<=5-o; s++) //corrected line
cout<<" ";
for (i=1; i<=o; i++){ //corrected line
cout<<"*";} //corrected line
cout<<endl;
}}
```
# Question 6

## Correct code:
```
z=int(input("Enter a number:")) //corrected line
for x in range(0,9): // corrected line
    if (z==x): //corrected line
        print("They are equal") //corrected line
    else:
        print("They are not equal")
```
# Question 7

## Correct code:
```
#include <iostream>
using namespace std; //corrected line
class test{
    public:
int my_variable;
}; //corrected line
int main() {
test code_chef;
cin>>code_chef.my_variable;
if(code_chef.my_variable%2==0){
cout<<"Even";
}
else{
cout<<"odd"; //corrected line
}
return 0;
}
```
# Question 8

## Correct code:
```
#include<iostream>
using namespace std;
void printSums(int N)
{
int start=1, end=(N+1)/2;
while (start<end)
{
int sum=0;
for (int i=start;i<=end;i++)
{
sum+=i;
if (sum == N)
{
for (int j=start;j<=i;j++)
cout<<j<<" ";
cout<<"\n";
break;
}
if (sum>N)
break;
}
sum=0;
start++;
}
}
int main()
{
int n;
cin>>n;
printSums(n);
return 0;
}
```
# Question 9

## Correct code:
```
#include <iostream>
using namespace std;
int main() {
int length;
cout<<"enter the length of the array"<<endl;
cin>>length;
int array[length];
for(int i=0;i<length;i++){
cin>>array[i];
}
int min=array[0],max=array[0];
for(int i=1;i<length;i++){
if(array[i]>max)
max = array[i];
else if(array[i]<min)
min = array[i];
}
cout<< min<<" "<<max;
return 0;
}
```
# Question 10

## Correct code:
```
#include <stdio.h>
#include <string.h>
int main()
{
int t,i,diff_count;
scanf("%d",&t);
char s[100001];
while(t--){
diff_count=0;
scanf("%s",s);
for(int i=0;i<strlen(s)-1;i++){
if(s[i]==s[i+1])

diff_count++;
}
printf("%d\n",diff_count);
return 0;
}}
```
