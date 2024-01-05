
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

Yeh concepts aapko C++ mein classes aur objects ke sath kaam karne mein madadgar honge.
