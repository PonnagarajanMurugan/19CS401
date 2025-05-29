# AIM:
To Write A CPP Program to allocate memory dynamically for a double array. (Note: p_array = new type [size]; ).


# ALGORTHIM:

1.Start the program.
2.Define a class named student.
3.Declare integer variables and a float pointer to dynamically allocate an array.
4.In the constructor, display a message, read the size of the array, and take input for each element.
5.In the destructor, display the array elements and a message indicating the array is deleted.
6.Create an object of the student class in the main function and end the program.

# PROGRAM:

```
#include <iostream>
using namespace std; 
class student
{
    public:
    int i, n;
    
    float *a=new float[5];
    student()
    {
        cout<<"Array Created"<<endl;
        cin>>n;
        for(i=0;i<n;i++)
        {
            cin>>a[i];
        }
    }
    ~student()
    {
        cout<<"Array Values :"<<endl;
        for(i=0;i<n;i++)
        {
            cout<<a[i]<<" ";
        }
        cout<<endl<<"Array Deleted";
    }
};

int main()
{
    student s;
}
````

# OUTPUT:'

![image](https://github.com/user-attachments/assets/cceabfe1-7723-4f85-8ffd-ea6980d94124)

# RESULT:

The C++ program for Write A CPP Program to allocate memory dynamically for a double array is successfully executed.
