Prince
#include <iostream>
using namespace std;
int main()                                             Cin don't reads enter,tab, space
{ int a,b;
cin>>a>>b;
cout<<"value of a and b is"<<" " <<a<<" "<<b<<endl;
   
    return 0;
}

#include <iostream>
using namespace std;
int main()
{
    int a=9;                       == means check  ,,,,    = intialisation
   
    int b=a+1;
    if((a==3)==b)
    {
        cout<<a;
    } else
    {cout<<a+1;
      }
    
}

// H W
 char ch;
 lower case if it is between a-z
 uppercase if it is between A-Z
 numeric if it is between 0-9


while loop😊


#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    int i=1;
    int sum=0;
    while(i<=n)
    {
    sum=sum+i;
    i=i+1;
    
} cout<< "value of sum is"<<sum<<endl;
}


                       # sum of even number...
#include <iostream>
using namespace std;
 int main()
{
    int n;
    int i;
    int sum=0;
    cout<<"enter value of n:";
    cin>>n;
    for(i=1;i<=n;i++)
{
   
    sum=sum+i*2;
       
}
cout<<"sum of first"<<sum;
    return 0;
}
                                                       pattern


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter the value of n: ";
    cin >> n;  // Take user input

    int i = 1;
    while (i <= n) {
        int j = 1;
        while (j <= n) {
            cout << "*";
            j = j + 1;
        }
        cout << endl;
        i = i + 1;
    }

    return 0;  // Return 0 to indicate successful execution
}

                                     pattern 1111 2222 3333 44444
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter the value of n: ";
    cin >> n;  // Take user input

    int i = 1;
    while (i <= n) {
        int j = 1;
        while (j <= n) {
            cout << i;
            j = j + 1;
        }
        cout << endl;
        i = i + 1;
    }

    return 0;  // Return 0 to indicate successful execution
}

                          pattern 1 22 333 4444 .........
#include <iostream>
using namespace std;
int main()
{
    int n;
    
    cin >> n;
    int i=1;
    while(i<=n)
   {
       int j=i;
    while(j<=n)
    {cout<<i;
       j=j+1;
   }
    cout<<endl;
    i=i+1;
}
}


                          AAA
                         BBB
                         CCC

         #include<iostream>
using namespace std;
int main()
{
int n;
cin>>n;
int row=1;       
while(row<=n)
 { int col=1;                                            can not directly cout formula, it will give ascii value in num.
   while(col<=n)
   
   { 
       char ch='A'+row-1;
       cout<<ch;
     col=col+1;
   }cout<<endl;
   row=row+1;                         iuhdfijsguifidaoui
   
 }
 }                
                               today i was not able to

