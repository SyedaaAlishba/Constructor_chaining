<h1>Constructor Chaining in Java</h1>
Overview<br>

Constructor chaining is a process of calling one constructor from another constructor within the same class or from the parent class. It is used to reuse constructor code and ensure proper initialization of objects.<br>

Types of Constructor Chaining<br>

Within the Same Class
<br>
Use the keyword this() to call another constructor of the same class.
<br>
Helps avoid code duplicatio<br><br>
From Parent Class (Inheritance)
<br>
Use the keyword super() to call a constructor from the parent class.
<br>
Must be the first statement in the child class constructor.
<br>
Benefits
<br>
Code Reusability: Avoids writing repetitive code in multiple constructors.
<br>
Better Initialization: Ensures proper initialization when multiple constructors exist.
<br>
Readable Code: Makes the code easier to understand and maintain.
<br>
Rules
<br>
this() can only call another constructor in the same class.
<br>
super() can only call a constructor from the parent class.
<br>
this() or super() must be the first statement in a constructor.
<br>
Constructor chaining can combine both this() and super() in different levels of the hierarchy.
