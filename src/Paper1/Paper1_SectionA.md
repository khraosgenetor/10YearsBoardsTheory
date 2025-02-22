# Section A

## **Question 1**

Choose the correct answer and write the correct option.

---

### **(i) What will this code produce as output?**  

```java
public class q {
    public static void main(String[] args) {
        int[] a = {2, 4, 6, 8, 10};
        a[0] = 23;
        a[3] = a[1];
        int c = a[0] + a[1];
        System.out.println("Sum = " + c);
    }
}
```
(a) 26  
(b) 23  
(c) 25  
(d) 27

**Answer:** **(d) 27**

### **Working:**
- `a[0]` is assigned `23`, and `a[3]` is assigned `a[1]` (which is `4`).
- The sum is calculated as:  
  `a[0] + a[1] = 23 + 4 = 27`.

---

### **(ii) The process of binding the data and method together as one unit is called**
(a) Dynamic binding  
(b) Inheritance  
(c) Polymorphism  
(d) **Encapsulation**

**Answer:** **(d) Encapsulation**

---

### **(iii) A collection of classes is known as a**
(a) **Package**  
(b) Function  
(c) Method  
(d) Wrapper class

**Answer:** **(a) Package**

---

### **(iv) What is the return type of the following function?**
`isLetterOrDigit(char)`  
(a) String  
(b) Char  
(c) Integer  
(d) **Boolean**

**Answer:** **(d) Boolean**

---

### **(v) What will the following code output?**

```java
public class q {
    public static void main(String[] args) {
        String str = "Computer Applications" + 1 + 0;
        System.out.println("Understanding " + str);
    }
}
```
(a) **Understanding Computer Applications 10**  
(b) Understanding Computer Application 20  
(c) Understanding Computer Application 10  
(d) Error

**Answer:** **(a) Understanding Computer Applications 10**

---

### **(vi) What is the output of the following code?**

```java
public class q {
    public static void main(String[] args) {
        String s1 = "welcome";
        String s2 = "island";
        System.out.println(s1.substring(0).concat(s2.substring(2)));
        System.out.println(s2.toUpperCase());
    }
}
```
(a) Welcome-land ISLAND  
(b) Welcome Land Island  
(c) WELCOME LAND  
(d) **Welcome land ISLAND**

**Answer:** **(d) Welcome land ISLAND**

---

### **(vii) This term refers to the name assigned to a package, class, interface, method, or variable.**
(a) Keyword  
(b) Token  
(c) Literal  
(d) **Identifier**

**Answer:** **(d) Identifier**

---

### **(viii) These constructors require parameters to be provided when creating objects.**
(a) Copy  
(b) Default  
(c) **Parameterized**  
(d) None of the above

**Answer:** **(c) Parameterized**

---

### **(ix) int code[ ] = {25, 37, 38, 42}; The given statement**
(a) **assigns 37 to `code[1]`**  
(b) assigns 25 to `code[1]`  
(c) assigns 38 to `code[3]`  
(d) assigns 42 to `code[0]`

**Answer:** **(a) assigns 37 to `code[1]`**

---

### **(x) The automatic conversion of a primitive data type into an object of its corresponding wrapper class is called:**
(a) **Auto-boxing**  
(b) Explicit conversion  
(c) Shifting  
(d) None of the above

**Answer:** **(a) Auto-boxing**

---

### **(xi) The `parseInt()` function is a member of**
(a) **Integer wrapper class**  
(b) Character wrapper class  
(c) Boolean wrapper class  
(d) None of these

**Answer:** **(a) Integer wrapper class**

---

### **(xii) _____ members are accessible inside their own class, classes within the package, and subclasses.**
(a) Private  
(b) **Protected**  
(c) Public  
(d) None of these

**Answer:** **(b) Protected**

---

### **(xiii) Iteration is also known as**
(a) Looping  
(b) Repetition  
(c) **Both (a) and (b)**  
(d) None of these

**Answer:** **(c) Both (a) and (b)**

---

### **(xiv) _____ are reference types, which hold the reference ID of a memory location.**
(a) **Composite types**  
(b) Primitive types  
(c) Attribute types  
(d) None of the above

**Answer:** **(a) Composite types**

---

### **(xv) Classes that inherit from `RuntimeException` are referred to as:**
(a) Checked exceptions  
(b) **Unchecked exceptions**  
(c) Impure exceptions  
(d) Static exceptions

**Answer:** **(b) Unchecked exceptions**

---

### **(xvi) Which of the following are invoked directly when an object is created?**
(a) Methods  
(b) Arrays  
(c) **Constructors**  
(d) Strings

**Answer:** **(c) Constructors**

---

### **(xvii) Assertion (A): Array is a data type that can store multiple homogeneous variables.**
Reason (R): Elements of an array are stored in an indexed manner starting with index 0.

(a) **Both A and R are true, and R is a correct explanation of A.**  
(b) Both A and R are true, but R is not a correct explanation of A.  
(c) A is true, and R is false.  
(d) A is false, and R is true.

**Answer:** **(a) Both A and R are true, and R is a correct explanation of A.**

---

### **(xviii) Read the following text and choose the correct answer.**
Abstraction is a key concept in Object-Oriented Programming (OOP) that focuses on representing essential features while omitting unnecessary background details.

(a) **Abstraction is more about "What" a class can do.**  
(b) Abstraction is more about "How" to achieve that functionality.  
(c) It binds data and methods in a single unit.  
(d) It implements using the `private` access modifier.

**Answer:** **(a) Abstraction is more about "What" a class can do.**

---

### **(xix) Assertion (A): The factory of objects means a factory that produces objects.**
Reason (R): A class is known as an object factory because a single class generates a lot of objects.

(a) **Both A and R are true, and R is a correct explanation of A.**  
(b) Both A and R are true, but R is not a correct explanation of A.  
(c) A is true, and R is false.  
(d) A is false, and R is true.

**Answer:** **(a) Both A and R are true, and R is a correct explanation of A.**

---

### **(xx) Which of the following statements is incorrect?**
(a) **Arrays can be initialized when they are declared.**  
(b) Arrays can be initialized using ‘comma’ separated expressions surrounded by curly braces.  
(c) It is necessary to use the `new` operator to initialize an array.  
(d) None of the above

**Answer:** **(a) Arrays can be initialized when they are declared.**

---

## **Question 2**

---

### **(i) If int a[ ] = {7, 3, 4, 8, 9, 2}; what are the values of x and y?**

#### <b>(a) x = a[1] * a[0] + a[3]</b>

    x = 3 * 7 + 8
    x = 21 + 8
    x = 29

#### <b>(b) y=a.length</b>

    y = 6

---

### **(ii) Determine the values of n and m after executing the following code:**

```java
public class q {
    public static void main(String[] args) {
        int m;
        int n;
        m=5;
        n=(5*++m)%3;
        System.out.println("n="+n+"m="+m);
    }
}
```
#### **Solution:**

    m = 5, n = (5 * ++5) % 3
    m = 5, n = (5 * 6) % 3
    m = 5, n = 30 % 3
    m = 5, n = 0

#### **Output:**

    n=0m=5

---

### **(iii) Identify the keyword that:**
#### **(a) Indicates an error has occurred during an input/output operation**:
##### Answer: *IOException*

---

#### **(b) Differentiates between an instance variable and a class variable**:
##### Answer: *this*

---

### **(iv) What will be the outcome of the following statements?**
```java
public class q {
    public static void main(String[] args) {
        int a=3;
        System.out.println(" "+(1+a));
        System.out.println(" "+1+a);
    }
}
```

#### **Output:**

     4
     13

---

#### **Process 1: (Addition, then concatenation)**

    " "+(1+3) (Addition, then concatenation)
        " "+4
         4

---

#### **Process 2: (Direct concatenation)**

    " "+1+3 (Direct concatenation)
        " 1"+3
         13

### (v) Name the primitive data type in Java that is a 64 bits integer and is used when you need a range of values under than those provided by int.