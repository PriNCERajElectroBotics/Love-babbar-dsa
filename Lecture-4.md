
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

