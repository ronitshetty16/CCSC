# Question 2

## Code:

```
#include <iostream>
using namespace std;
int main()
{
    int size,k,element,flag=0;
    cin>>size;
    int array[size];
    for(int i=0;i<size;i++){
        cin>>array[i];
    }
    for(int i=0;i<size-1;i++){
        for(int j=0;j<size-i-1;j++){
            if(array[j]>array[j+1]){
                int temp=array[j];
                array[j]=array[j+1];
                array[j+1]=temp;
            }
        }
    }
    cin>>k;
    element=array[k-1];
    cout<<element<<endl;
    for(int i=2;i<=element/2;i++){
        if(element%i==0){
            cout<<"Not Prime";
            flag=1;
            break;
        }
    }
    if(flag==0){
        cout<<"Prime";
    }
    return 0;
}
```

# Question 3

## Code:

```
#include<iostream>
using namespace std;
int main()
{
    
    char lowerCase = 'a';
    char upperCase = 'A';
    int printLowerCase = 0;
    
    //2
    while(lowerCase <= 'z' & upperCase <= 'Z'){
        
        if(printLowerCase){
            cout<<lowerCase<<endl;
        }else{
            cout<<upperCase<<endl;
        }
        
        printLowerCase = !printLowerCase;
        lowerCase+=2;
        upperCase+=2;
    }
        
    return 0;
}
```

# Question 4

## Code:

```
#include <iostream>
using namespace std;
int main()
{
    int n,k=0,temp,flag=1,square,a,b;
    cin>>n;
    temp=n;
    while(temp>0){
        temp/=10;
        flag*=10;
        k++;
    }
    square=n*n;
    a= square%flag;
    b= square/flag;
    if(a+b==n){
        cout<<"Chef Number";
    }else{
        cout<<"Not Chef Number";
    }
    return 0;
}
```
