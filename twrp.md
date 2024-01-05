
**Procedural vs. Object-Oriented Development:**

**Procedural Development (Procedural Programming):** Ismein code ko functions ya procedures ke roop mein likha jata hai. Har function specific task ko handle karta hai, aur data alag-alag variables mein store hota hai. C programming ek accha udaharan hai procedural development ka. Yahan, functions data par kaam karte hain.

**Object-Oriented Development (Object-Oriented Programming):** Ismein code ko objects ke roop mein organize kiya jata hai. Objects ek particular class se banti hain aur unmein data aur methods (functions) ek saath store hote hain. Har object ek unique state aur behavior rakhta hai. C++ ek object-oriented programming language hai.

**Basic Concepts of Object-Oriented Programming (OOP):**

1. **Class:** Class ek blueprint hoti hai jo objects banane mein madad karti hai. Yeh define karta hai ki object mein kaisa data aur functionality hoga.

2. **Object:** Object ek class se bana hota hai aur real-world entity ko represent karta hai. Har object apna apna data aur methods rakhta hai.

3. **Encapsulation:** Encapsulation ka matlab hai ki data aur methods ko ek saath rakha jata hai aur usmein kisi bhi tarah ka access control lagaya jata hai.

4. **Inheritance:** Inheritance ke dwara ek class dusri class ke properties aur methods ko inherit kar sakti hai. Yeh code reusability badhata hai.

5. **Polymorphism:** Polymorphism ka matlab hai ki ek interface se multiple implementations ki taraf ja sakte hain. Isse code flexibility badhti hai.

**Applications and Benefits of OOP:**

- **Applications:** Object-oriented programming ka use aap software development mein kai tariko se kar sakte hain jaise ki desktop applications, web development, mobile apps, games, aur databases, etc.

- **Benefits:** OOP ke kuch fayde hain:
  - Code Reusability: Existing classes se naye classes bana sakte hain, isse code reusability hoti hai.
  - Modularity: Code ko chota modules mein divide karke development aur maintenance ko asaan banata hai.
  - Abstraction: Complex systems ko simple tarike se represent kiya ja sakta hai.
  - Encapsulation: Data security aur access control ensure hota hai.
  - Polymorphism: Flexibility aur code optimization hoti hai.

**Comparison between C and C++:**

| Parameter               | C                    | C++                   |
|-------------------------|----------------------|-----------------------|
| Programming Paradigm    | Procedural           | Object-Oriented       |
| Data Abstraction        | Limited              | Strong                |
| Code Reusability        | Limited              | High                  |
| Inheritance             | Not supported        | Supported             |
| Function Overloading    | Not supported        | Supported             |
| Operator Overloading    | Not supported        | Supported             |
| Standard Libraries      | Limited              | Extensive             |
| Memory Management       | Manual (malloc, free) | Automatic (new, delete) |

Upar di gayi table mein C aur C++ ke beech ke kuch mukhya antar dikhaye gaye hain. C++, object-oriented features ke saath aata hai, jo code reusability aur flexibility mein sudhar kar deta hai, jabki C procedural programming ka ek udaharan hai jismein objects aur classes ka istemal nahi hota.


**Stream-based I/O (Input/Output):**
C++ mein stream-based I/O ka use karke aap asaani se input aur output handle kar sakte hain. `cin` stream se aap user se input le sakte hain aur `cout` stream se aap output display kar sakte hain. Ismein `>>` operator ka use input ke liye hota hai aur `<<` operator ka use output ke liye hota hai.

**Literals - Constant Qualifiers:**
C++ mein literals, constants ko represent karne ke liye hote hain. For example, aap `int` data type mein `5` ko literal constant ke roop mein use kar sakte hain. Constant qualifiers jaise `const` ka use kiya jata hai taki aap specify kar sakein ki koi value change nahi ho sakti.

**Operators in C++:**
C++ mein kai tarah ke operators hote hain jo various operations ko perform karte hain. Arithmetic operators (like `+`, `-`, `*`, `/`), comparison operators (like `==`, `!=`, `<`, `>`), assignment operators (like `=`, `+=`, `-=`, `*=`), logical operators (like `&&`, `||`), aadi.

**Reference Variable:**
Reference variable ek variable ko dusre variable ka alias banata hai. Isse aap ek variable ko dusre variable ke naam se access kar sakte hain. Reference variable ko declare karte waqt `&` symbol ka use kiya jata hai.

**Functions - Default Arguments:**
C++ mein aap functions ke parameters ko default values assign kar sakte hain. Isse function call karte waqt agar koi value nahi di jati to default value use hoti hai. Ye feature function definition ke dauran provide kiya jata hai.

**Parameter Passing by Value, Reference, and Pointer:**
Function mein parameters ko kisi bhi tarike se pass kiya ja sakta hai. Parameter passing by value, reference, aur pointer ke tino tarike hote hain. Value se pass karne par original data modify nahi hota, reference se pass karne par original data modify ho sakta hai, aur pointer se pass karne par address ke through original data modify ho sakta hai.

**Inline Functions:**
Inline functions compile-time optimization ke liye hoti hain. Yeh functions compiler ko suggestion deti hain ki unko function call ke bajaye wahi code insert karna chahiye jahan function call hota hai. Isse function call ki overhead kam hoti hai.

**Type Conversion:**
Type conversion, ya casting, ka use data type ko ek se dusre mein convert karne ke liye hota hai. C++ mein implicit (automatic) type conversion hoti hai, jaise ki `int` se `float` mein. Explicit (manual) type conversion bhi kiya ja sakta hai, jahan aap specifically data type ko cast karte hain.

**Basic C++ Programs:**
Basic C++ programs mein aap "Hello World" jaise simple programs likh sakte hain. Ismein aap user se input le sakte hain, use process karke output generate kar sakte hain, ya fir arithmetic calculations kar sakte hain.

**New and Delete Operators - Dynamic Memory Allocation for Arrays:**
`new` operator ka use dynamic memory allocation ke liye hota hai. Isse aap heap memory mein nayi memory allocate kar sakte hain. `delete` operator ka use dynamically allocated memory ko deallocate karne ke liye hota hai. Arrays ke liye `new[]` aur `delete[]` operators ka use kiya jata hai.

**Classes and Objects:**

**C++ Class Declaration:**
C++ mein class ek blueprint hoti hai jo objects ke liye define hoti hai. Class declaration ke dauran aap class ke members, functions, aur access specifiers define karte hain. Niche ek example diya gaya hai:

```cpp
class Student {
private:
    int rollNumber;
    char grade;

public:
    void setRollNumber(int r) {
        rollNumber = r;
    }

    void setGrade(char g) {
        grade = g;
    }

    void display() {
        cout << "Roll Number: " << rollNumber << endl;
        cout << "Grade: " << grade << endl;
    }
};
```

**Access Specifiers:**
Access specifiers, jaise ki `private`, `public`, aur `protected`, batate hain ki class ke members aur functions ka access kis level par allowed hai. Private members sirf class ke andar hi access kar sakte hain, public members class ke bahar se bhi access kar sakte hain.

**Member Functions:**
Member functions class ke functions hote hain jo class ke members ko manipulate karte hain. Upar diye gaye example mein `setRollNumber()`, `setGrade()`, aur `display()` member functions hain.

**Arrays Within a Class:**
Aap ek class ke andar arrays bhi define kar sakte hain. Jaise ki:

```cpp
class MyClass {
private:
    int myArray[5];

public:
    // Constructor to initialize the array
    MyClass() {
        for (int i = 0; i < 5; i++) {
            myArray[i] = 0;
        }
    }
};
```

**Array of Objects:**
Aap multiple objects create karke unko ek array mein bhi store kar sakte hain. Jaise ki:

```cpp
Student students[5];
```

**Memory Allocation of Objects:**
Objects stack ya heap memory mein allocate ho sakte hain. Stack mein objects automatically destroy ho jate hain jab unka scope khatam ho jata hai, jabki heap mein manually `new` aur `delete` operators ka use karke objects allocate aur deallocate kiye jate hain.

**Passing Objects as Arguments:**
Aap objects ko functions mein arguments ke roop mein pass kar sakte hain. Example:

```cpp
void printStudentDetails(Student s) {
    s.display();
}
```

**Returning Objects from Functions:**
Aap functions se objects return kar sakte hain. Example:

```cpp
Student createStudent() {
    Student s;
    s.setRollNumber(101);
    s.setGrade('A');
    return s;
}
```

**Function Overloading:**
Function overloading ka matlab hai ki ek function ke multiple versions ho sakte hain, jinke parameters alag ho. Example:

```cpp
int add(int a, int b) {
    return a + b;
}

double add(double a, double b) {
    return a + b;
}
```

**Static Data and Member Functions:**
Static data members ek class ke sabhi objects ke liye common hote hain. Static member functions bhi class ke sabhi objects ke liye common hote hain aur class ke instance data members tak access nahi kar sakte.

**Friend Function and Friend Class:**
Friend function ek class ke private members ko access karne ke liye use hota hai, lekin woh class member nahi hota. Friend class ek class ko dost class declare karne ke liye use hota hai.

**This Pointer:**
`this` pointer ek special pointer hota hai jo ek object ke liye khud ko point karta hai. Isse aap class ke members ko reference kar sakte hain. Example:

```cpp
class Student {
private:
    int rollNumber;

public:
    void setRollNumber(int r) {
        this->rollNumber = r;
    }
};
```

**Constructors & Destructors:**

**Introduction to Constructor and Destructor:**
- **Constructor:** Constructor ek special member function hota hai jo object banate waqt automatically call hota hai. Constructor ka kaam hota hai object ke members ko initialize karna.
- **Destructor:** Destructor bhi ek special member function hota hai, lekin yeh object destroy (memory deallocate) hone par automatically call hota hai. Destructor ka kaam hota hai resources, jaise ki memory, release karna.

**Parameterized Constructor:**
Parameterized constructor ek constructor hota hai jisko parameters ke sath define kiya jata hai. Isse aap object banate waqt values ko pass kar sakte hain. Example:

```cpp
class Rectangle {
private:
    int length;
    int width;

public:
    Rectangle(int l, int w) {
        length = l;
        width = w;
    }
};
```

**Constructor with Default Arguments:**
Constructor ko default arguments ke sath define kiya ja sakta hai. Isse constructor ko bina arguments ke bhi call kiya ja sakta hai. Example:

```cpp
class Circle {
private:
    double radius;

public:
    Circle(double r = 1.0) {
        radius = r;
    }
};
```

**Multiple Constructors in a Class:**
Aap ek class mein multiple constructors define kar sakte hain, lekin unke parameters alag hone chahiye (function overloading ka concept). Example:

```cpp
class Employee {
private:
    int empId;

public:
    Employee() {
        empId = 0;
    }

    Employee(int id) {
        empId = id;
    }
};
```

**Copy Constructor:**
Copy constructor ek special constructor hota hai jo ek object se dusra object banane ke liye use hota hai. Yeh ek existing object ke data ko copy karke naya object banata hai. Example:

```cpp
class Book {
private:
    string title;

public:
    Book(const Book& otherBook) {
        title = otherBook.title;
    }
};
```

Constructors aur destructors C++ mein class ke objects ke creation aur destruction ke process ko control karne mein madad karte hain.

**Inheritance:**

Inheritance ek important concept hai C++ programming mein, jisme ek class dusri class ke properties aur methods ko inherit karti hai. Yeh ek parent-child relationship ko represent karta hai. Inheritance se code reusability aur hierarchies create karne mein madad milti hai. Niche main kuch important concepts aur types of inheritance explain karunga:

**Types of Inheritance:**
1. **Single Inheritance:** Ek child class ek hi parent class se inherit hoti hai.
2. **Multiple Inheritance:** Ek child class do ya do se adhik parent classes se inherit hoti hai.
3. **Multilevel Inheritance:** Ek class dusri class se inherit hoti hai, phir dusri class se tisri class inherit hoti hai, aur aise hi chalti rahti hai.
4. **Hierarchical Inheritance:** Ek class multiple child classes ko inherit karti hai.
5. **Hybrid Inheritance:** Yeh ek combination hota hai multiple, multilevel, ya hierarchical inheritance ke.

**Derivation - Public, Private & Protected:**
- **Public Inheritance:** Public inheritance mein, public members parent class se child class mein public members ke roop mein inherit hote hain, private members child class mein access nahi ho sakte.
- **Private Inheritance:** Private inheritance mein, parent class ke public aur protected members child class mein private members ke roop mein inherit hote hain, aur unko child class ke bahar access nahi kiya ja sakta.
- **Protected Inheritance:** Protected inheritance mein, parent class ke public aur protected members child class mein protected members ke roop mein inherit hote hain, aur unko child class ke bahar access nahi kiya ja sakta.

**Ambiguity Resolution (Function Overriding):**
Agar ek child class mein do parent classes se aane wale members ke naam ya data type mein conflict hota hai, toh ambiguity resolution ki zaroorat hoti hai. Isme `virtual` keyword aur function overriding ka use kiya jata hai.

**Aggregation:**
Aggregation ek relationship hota hai jahan ek class dusri class ke objects ko "has-a" relationship ke roop mein use karti hai. Isme ek class dusri class ke objects ko reference karta hai. Example, ek University class ek Department class ke objects ko reference kar sakta hai.

**Composition vs Classification:**
Composition ek relationship hota hai jahan ek class dusri class ke objects ko "owns" relationship ke roop mein use karti hai. Isme ek class dusri class ke objects ko khud ke part ke roop mein rakhti hai. Classification mein ek class dusri class ko inherit karti hai.

**Virtual Base Class:**
Virtual base class ka use multiple inheritance ke case mein hota hai. Jab ek class do se adhik classes se inherit hoti hai aur un dono classes mein ek common base class hai, toh yeh ambiguity ko resolve karne mein madadgar hoti hai.

**Constructor and Destructor in Derived Classes:**
- Derived class ke constructor mein base class ke constructor ko call karna important hota hai. Isse base class ke members initialize hote hain.
- Destructor bhi derived class ke destructor mein base class ke destructor ko call karna chahiye taki resources properly deallocate ho sake.

Yahan ek diagram diya gaya hai jo inheritance ke kuch types ko represent karta hai:

```
       Person
         /  \
        /    \
   Student   Teacher
      |
   Engineer
```

Is diagram mein `Person` ek base class hai, `Student` aur `Teacher` derived classes hain jo `Person` class se inherit hoti hain, aur `Engineer` ek aur derived class hai jo `Student` class se inherit hoti hai.

**Polymorphism:**

**Types of Polymorphism:**
1. **Compile-time Polymorphism (Static Binding):** Ismein function overloading aur operator overloading ka use hota hai. Function calls compile-time par resolve hote hain.
2. **Run-time Polymorphism (Dynamic Binding):** Ismein function overriding ka use hota hai. Function calls run-time par resolve hote hain. Yeh virtual functions ke through achieve hota hai.

**Early vs. Late Binding:**
- **Early Binding:** Compile-time par function calls resolve hote hain. Ismein static binding hoti hai.
- **Late Binding:** Run-time par function calls resolve hote hain. Ismein dynamic binding hoti hai.

**Virtual Functions:**
- Virtual functions tab use hoti hain jab aap base class ke pointer/reference se derived class ke functions ko call karna chahte hain.
- Yeh base class mein declare hoti hain `virtual` keyword ke sath aur derived class mein override hoti hain.
- Yeh run-time polymorphism ko possible banati hain.

**Example with Diagram:**
Consider a scenario where we have a base class `Shape` and two derived classes `Circle` and `Rectangle`. `Shape` has a virtual function `area()`. Here's a simple diagram:

```
        Shape
        /    \
    Circle  Rectangle
```

```cpp
class Shape {
public:
    virtual double area() { return 0; }
};

class Circle : public Shape {
private:
    double radius;

public:
    Circle(double r) : radius(r) {}
    double area() override {
        return 3.14159 * radius * radius;
    }
};

class Rectangle : public Shape {
private:
    double length;
    double width;

public:
    Rectangle(double l, double w) : length(l), width(w) {}
    double area() override {
        return length * width;
    }
};
```

**Pointer to Derived Class Objects:**
```cpp
Shape* shape1 = new Circle(5.0);
Shape* shape2 = new Rectangle(4.0, 6.0);

double area1 = shape1->area(); // Calls Circle's area()
double area2 = shape2->area(); // Calls Rectangle's area()
```

**Pure Virtual Functions & Abstract Classes:**
- Pure virtual functions are declared in base classes but have no implementation.
- A class containing pure virtual functions is called an abstract class.
- Abstract classes cannot be instantiated; they are meant to be inherited from and their pure virtual functions must be implemented in derived classes.

**Operator Overloading:**

**Overloading Unary Operators:**
```cpp
class Complex {
private:
    double real;
    double imag;

public:
    Complex(double r, double i) : real(r), imag(i) {}
    Complex operator-() {
        return Complex(-real, -imag);
    }
};
```

**Nameless Objects:**
```cpp
Complex c1(3.0, 4.0);
Complex c2 = -c1; // Using unary operator overloading
```

**Overloading Binary Operators:**
```cpp
class Complex {
private:
    double real;
    double imag;

public:
    Complex(double r, double i) : real(r), imag(i) {}
    Complex operator+(const Complex& other) {
        return Complex(real + other.real, imag + other.imag);
    }
};
```

**Overloading with Friend Functions:**
```cpp
class Complex {
private:
    double real;
    double imag;

public:
    Complex(double r, double i) : real(r), imag(i) {}
    friend Complex operator+(const Complex& a, const Complex& b) {
        return Complex(a.real + b.real, a.imag + b.imag);
    }
};
```

**Conversion Between Basic Types and User-Defined Types:**
You can overload casting operators to allow conversion between user-defined types and basic types.

```cpp
class Distance {
private:
    int feet;
    float inches;

public:
    Distance() : feet(0), inches(0.0) {}
    Distance(int f, float in) : feet(f), inches(in) {}
    operator float() const {
        return feet + (inches / 12.0);
    }
};
```

These are some examples and explanations of polymorphism, operator overloading, and related concepts in C++.
