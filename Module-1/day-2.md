## Aim:

To write a C++ program that calculates the volume of a cylinder using a class, where the data members are 
declared private and the methods are defined inside the class.

# Algorithm:

1.Start the program.<br>
2.Define a class named Cylinder.<br>
3.Declare the radius and height as private data members.<br>
4.Define public methods.<br>
5.Create an object of the Cylinder class.<br>
6.End the program.

# Program:
```
#include <bits/stdc++.h>
using namespace std;
class cylinder{
public:
    void setnumber(double num1,double num2){
        a=num1;
        b=num2;
    }
    double result(){
        return 3.14*a*a*b;
    }
    
private:
    double a,b;
};
int main(){
    double num1,num2;
    cin>>num1>>num2;
    cylinder s;
    s.setnumber(num1,num2);
    cout<<"The Volume of the Cyclinder is:"<<s.result();
}
```

# Output:

![Screenshot 2025-04-29 093201](https://github.com/user-attachments/assets/3e3428ca-d340-48f8-adfc-3d206856bd43)

# Result:

Thus, the c++ program to display the volume of a cylinder is implemented successfully.
