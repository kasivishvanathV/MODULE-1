# MODULE-1
1A OVERVIEW & STRUCTURE
PROGRAM STATEMENT:
Write a C++ program to display "Welcome to Technical Training" in first line and "at Saveetha Engineering College" in next line in the output device?

ALGORITHM:
Start the program.
Include necessary header files for input/output operations.
Define the main function.
Print "Welcome to Technical Training" with a newline.
Print "at Saveetha Engineering College".
End the program.
PROGRAM:
#include <iostream>
using namespace std;
int main()
{
    cout<<"Welcome to Technical Training\nat Saveetha Engineering College";
    return 0;
}
OUTPUT:
![1](https://github.com/user-attachments/assets/53624077-c454-4c71-90f5-3f15cd3caf22)


RESULT:
Thus, the C++ program to display "Welcome to Technical Training" in first line and "at Saveetha Engineering College" in next line into the output device is implemented successfully.

1B CLASS SCOPE AND ACCESSING CLASS MEMBERS & REFERENCE VARIABLES
PROGRAM STATEMENT:
Write a C++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class)

ALGORITHM:
Start the program and define a class Cylinder with private radius and height.
Create a method to take input for radius and height from the user.
Define a method inside the class to calculate volume using the formula πr²h.
In main(), create an object of the class and call the input and volume methods.
Display the volume and end the program.
PROGRAM:
#include <iostream>
using namespace std;
class cyclinder
{
    public:
    float a,b;
    void dis()
    {
        cin>>a>>b;
        cout<<"The Volume of the Cyclinder is:"<<(3.14)*(a*a)*(b);
    }
};
int main()
{
    cyclinder c;
    c.dis();
}
OUTPUT:
![2](https://github.com/user-attachments/assets/638b7c53-321f-49bb-9a36-1adefe04d9cb)


RESULT:
Thus,the C++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class) has been successfully created.

1C C++ CONSTRUCTORS AND DESTRUCTORS
PROGRAM STATEMENT
Write a C++ program to display "C++ constructors" using default constructors.

ALGORITHM:
Start the program.
Define a class Cont with a default constructor that prints "C++ constructors".
In the main function, create an object c of class Cont, which calls the default constructor and displays the message.
End the program.
PROGRAM:
#include<iostream>
using namespace std;
class con
{
    public:
    con()
    {
        cout<<"C++ constructors";
    }
};
int main()
{
    con g;
    return 0;
}
OUTPUT:
![3](https://github.com/user-attachments/assets/1c89a2f4-7e82-4060-a17b-d66c584d4d65)


RESULT:
Thus, the C++ program to display "C++ constructors" using a default constructor is created successfully.

1D C++ MEMBER FUNCTION
PROGRAM STATEMENT:
Write a C++ program to calculate the sum of AP series using friend function.

ALGORITHM:
Start and define a class AP with private members a, d, n.
Create a method to input a, d, and n.
Use a friend function to calculate the AP sum using the formula.
In main(), create an object and call the input and friend function.
Display the sum and end the program.
PROGRAM:
#include<iostream>
using namespace std;
class zenko{
    public:
    int x,y,z;
    void data(){
        cin>>x>>y>>z;
    }
    friend int z(zenko m);
};
int z(zenko m){
    int u=(m.x+(m.y-1)*m.z);
    return u;
}
int main(){
    zenko s;
    s.data();
    cout<<"the sum is "<<z(s);
}
OUTPUT:
![4](https://github.com/user-attachments/assets/558bf45d-8f16-4d8a-9bc4-30eeb357cf1a)

RESULT:
Thus,the C++ program to calculate the sum of AP series using friend function has been created successfully.
