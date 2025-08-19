# uml_diagram
### Description:
Demo for all relationship types used in UML 

### Reference links:
https://blog.algomaster.io/p/uml-class-diagram-explained-with-examples </br>
https://www.geeksforgeeks.org/system-design/unified-modeling-language-uml-class-diagrams </br>
https://www.visual-paradigm.com/guide/uml-unified-modeling-language/uml-class-diagram-tutorial </br>

### Relationships in UML class diagram:
<img width="440" height="280" alt="image" src="https://github.com/user-attachments/assets/0689b3ab-c153-4cb2-a1fd-0bd93a6d14e0" />
<img width="356" height="330" alt="image" src="https://github.com/user-attachments/assets/06e4d05a-c674-414d-838a-36fbe3c66032" />
<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/255ec970-5fd8-4b67-aa9d-467a6d57df70" />


## 1. Association:
Association represents a **"uses-a"** relationship between two classes where one class uses or interacts with the other.</br></br>
**Example:** A `Student` class is associated with a `Course` class, as a student can enroll in multiple courses.
<img width="250" height="250" alt="1" src="https://github.com/user-attachments/assets/98a40e0d-4c24-49ba-90d0-af04b6a41c36" />

## 2. Aggregation:
Represents a **"has-a"** relationship where one class (the whole) contains another class (the part), but the contained class can exist independently.</br></br>
**Example:** A `Car` class has an `Engine` class but the `Engine` class can exist without the `Car` class.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/cd200231-a514-4375-b94d-a8366f9fad8e" />

## 3. Composition:
Represents a strong **"has-a"** relationship where the part cannot exist without the whole. If the whole is destroyed, the parts are also destroyed.</br></br>
**Example:** A `House` class is composed of `Room` class but the `Room` class can not exist without the `House` class.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/df722cdc-02da-40c2-acac-863277d5f514" />

## 4. Inheritance:
Inheritance (or Generalization) represents an **"is-a"** relationship where one class (subclass) inherits the attributes and methods of another class (superclass).</br></br>
**Example:** A `Dog` class and a `Cat` class inherit from an `Animal` class, as both dogs and cats are animals.
<img width="496" height="340" alt="image" src="https://github.com/user-attachments/assets/570dba07-a963-4d08-abe8-a433f34b83c4" />

## 5. Realization (Implementation):
Realization or implementation represents a relationship between a class and an interface, where the class implements the methods declared in the interface.</br></br>
**Example:** A `Rectangle` class and a `Circle` class implement the `Shape` interface, which declares a `getArea()` method.
<img width="476" height="338" alt="image" src="https://github.com/user-attachments/assets/9c442f47-ec9a-4450-b046-0db215293d73" />

## 6. Dependency:
Represents a **"uses"** relationship where a change in one class (the supplier) may affect the other class (the client).</br></br>
**Example:** A Customer class uses an Order class to place order.
<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/dc119a49-70b9-40f3-a173-761d0ccc3a4c" />

## Combined example:
Here's a comprehensive example that includes various types of relationships:
<img width="600" height="400" alt="2" src="https://github.com/user-attachments/assets/4c4dab01-018a-4ba4-ae83-a67900186737" />

<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/031d2434-2dd4-4994-9fcb-0de1b2a00a35" />


