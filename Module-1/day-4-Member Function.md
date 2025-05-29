## Aim:

To Write a C++ program to display the even numbers up to n using class and member function. Get 'n' value from user.

# Algorithm:

1.Start the program.
2.Define a class named EvenNumbers.
3.Declare an integer variable n as a private data member.
4.Define public methods to get input from the user and to display even numbers up to n.
5.Create an object of the EvenNumbers class and call the methods.
6.End the program.

# Program:
```
#include <iostream>

class EvenNumbers {
 private:
  int n;

 public:
  EvenNumbers() {
    n = 0;
  }

  void getN() {
   
    std::cin >> n;
  }

  void displayEvenNumbers() {
    
    for (int i = 2; i <= n; i += 2) {
      std::cout << i <<"\n";
    }
    std::cout << std::endl;
  }
};

int main() {
  EvenNumbers even;
  even.getN();
  even.displayEvenNumbers();
  return 0;
}

```

# Output:

![Screenshot 2025-05-29 175024](https://github.com/user-attachments/assets/bf4ca010-2f59-42e7-8343-5679b27a2e98)


# Result:

Thus, the  C++ program to display the even numbers up to n using class and member function is successfully executed.
