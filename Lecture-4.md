
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
            cout << j;
            j = j + 1;
        }
        cout << endl;
        i = i + 1;
    }

                                   count   pattrn
                                   
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter the value of n: ";
    cin >> n;  // Take user input

    int i=1;
    int count=1;
    while(i<=n)
    {
        int j=1;
        while(j<=n)
        {
            cout<< count<<" " ;
            count=count+1;
            j=j+1;
        }
        i=i+1;
        cout<<endl;
    }
} 
                         star pattern triangle...

#include <iostream>
using namespace std;
int main() {
    int n;
    cin>>n;
    int row=1;
    while(row<=n)
    {
     int col =1;
     while(col<=row)
     {
        cout<<"*";
        col=col +1;
    }
      cout<<endl;
   row=row+1;
   cout<<endl;
}

    return 0;
}
                              count trainge


        // Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int main() {
    int n;
    cin>>n;
    int row=1;
    int count=1;
    while(row<=n)                               // count is not working here.. when cout is row
    {
     int col =1;                                      if we erase count then also it will work.
     while(col<=row)
     {                                                  but it will work if cout is COUNT.
        cout<<row;
        count=count+1;
        col=col+1;
    }
      cout<<endl;
   row=row+1;
   cout<<endl;
}

    return 0;
}





