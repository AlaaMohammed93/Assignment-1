# Assignment-1
Name: Alaa Mohammed Ahmed
B.N: 33718
____________________________________________________________________________________________________________________________
1.	A class is: abstraction used to specify the form of an object and it combines data representation and methods for 
manipulating that data into one neat package. The data and functions within a class are called members of the class.
____________________________________________________________________________________________________________________________
2.	Abstraction is: hiding the implementation details by providing a layer over the basic functionality.
Information Hiding is: hiding the data which is being affected by that implementation. Use of private and public comes
under this. For example, hiding the variables of the classes.
Encapsulation is: just grouping all similar data and functions into a group e.g Class in programming; Packet in networking. 
Through the use of Classes, we implement all three concepts - Abstraction, Information Hiding and Encapsulation
____________________________________________________________________________________________________________________________
3.	A class defines the properties and behavior for the objects represented by the abstraction.
A class thus denotes a category of objects and act as a blueprint for creating such objects.
An object exhibits the property and behaviors defined by its class. Generally, an object is an instance of a class.
____________________________________________________________________________________________________________________________
4.	Member functions are the functions, which have their declaration inside the class definition and works on the data
members of the class. The definition of member functions can be inside or outside the definition of class.
Data members are not part of objects of a given class type.
____________________________________________________________________________________________________________________________
5.	#include <string>
using namespace std;
class Bank
{
private:
char name;
string acc_no;
double balance;
public:
Bank(char NM = 0, string AN = 0, double BL = 0.0);
char getname();
string getacc_no();
double getbalance();
void deposite();
void withdraw();
};
#endif;
_____________________________________________________________________________________________________________________________
6.	Constructor is called when: execution reaches point where object is declared.
Destructor is called if we want to replace an object with another object of the same type but don't want to 
free memory just to allocate it again. You can destroy the old object in place and construct a new one in place.
_____________________________________________________________________________________________________________________________
7.	Bank(char, string,double);
_____________________________________________________________________________________________________________________________
8.	Default constructor is: a constructor that can be called without having to provide any arguments. 
If a class has no explicitly defined constructors, the compiler will implicitly declare and define a default
constructor for it. This implicitly defined default constructor is equivalent to an explicitly defined one with an 
empty body assuring that no errors will occur.
_____________________________________________________________________________________________________________________________
9.	Replace std::string company; with char* company;
int get_shares()
{return shares;}
double get_share_val()
{return share_value;}
double get_total_val()
{return shares * share_val;}
char company()
{return company;}
______________________________________________________________________________________________________________________________
10.	This is: a pointer to the current object, while *this is: "clone" of the current object, allocated on the stack. Unless the return type of the method to return a reference is specified.
