# AIM:
To Write a CPP program to overload a function to print Integer data in one and Floating-Point data in another


# ALGORTHIM:
```
1.Start the program.
2.Define a class named function with two overloaded print() methods—one for integers and one for floating-point numbers.
3.In each method, display the value along with a label indicating its type.
4.In the main() function, declare variables for an integer and a float.
5.Read input values for both variables and call the appropriate print() methods using an object of the class.
6.End the program.
```
# PROGRAM:

```

 #include<iostream>
using namespace std;
class function
{
    public:
    void print(int x)
    {
        cout<<"Integer="<<x<<endl;
    }
    void print(float y)
    {
        cout<<"Floating Point="<<y;
    }
};
int main()
{
    function f;
    int x;
    float y;
    cin>>x>>y;
    f.print(x);
    f.print(y);
}

````

# OUTPUT:'

![image](https://github.com/user-attachments/assets/0db6886d-0c59-4e6a-ad91-115313172c0e)

# RESULT:

The C++ program for Write a CPP program to overload a function to print Integer data in one and Floating-Point data in another is successfully executed.

