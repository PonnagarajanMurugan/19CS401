# AIM:
To Write A CPP Program to create class RectangleBox and calculate the volume of the rectangleBoxe use of static member variable in the class RectangleBox.


# ALGORTHIM:

1.Start the program.
2.Define a class named Box with private data members for length, breadth, and height, and a static data member to count objects.
3.Define a constructor to initialize the dimensions and increment the object counter.
4.Define a public method to calculate and return the volume of the box.
5.In the main() function, read dimensions, create two Box objects, and display their volumes.
6.Display the total number of objects created and end the program.

# PROGRAM:

```
#include <iostream>
using namespace std;
class Box
{
    public:
    static int objcount;
    Box(double l,double b,double h) 
    {
        length=l;
        breadth=b;
        height=h;
        cout<<"Constructor called."<<endl;
        objcount++;
    }
    double Volume() 
    {
        return length*breadth*height;
    }
    private:
    double length;     
    double breadth;    
    double height;     
};
int Box::objcount=0;
int main(void) 
{
    int l,b,h,l1,b1,h1;
    cin>>l>>b>>h>>l1>>b1>>h1;
    Box box1(l,b,h);
    cout<<"Volume :"<<box1.Volume()<<endl;
    Box box2(l1,b1,h1);
    cout<<"Volume :"<<box2.Volume()<<endl;
    cout<<"Total objects: "<<Box::objcount;
    return 0;
}

````

# OUTPUT:'

![Screenshot 2025-05-29 181203](https://github.com/user-attachments/assets/51b30cb5-e16e-43a2-a990-8e885ddd65b5)

# RESULT:

The C++ program for Write A CPP Program to create class RectangleBox and calculate the volume of the rectangleBoxe use of static member variable in the class RectangleBox.
