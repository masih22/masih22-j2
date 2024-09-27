# Question 1.
| Objects | Basic types |
| ------- | ----------- |
| String s | int a |
| | int[] c |
| | double b |
| | int a |

# Question 2.
a: A static method is a method that belongs to the class itself rather than instances of the class. A static method allows you to create a method, without previously defining any other objects
b: The main method must  be static because there is always a main method, and w/o the static, the compiler wouldn't run

# Question 3.
Program 1: Wrong <br>
Program 2: Correct

# Question 4.
The program does not change the season because the change_season method never changes the address of the season variable declared in main.
The method instead creates a new address with a new variable.

# Question 5.
X: 0 Y: 0 <br>
In the public point constructor it assigns the variable to itself which would result in 1 = 1 for x and 2 = 2 fro y, instead of the intended case of 0 = 1 for x and 0 = 2 for y.
To fix this we would need to add a this. in the left handed side, so we have the code this.x = x and this.y = y.

# Question 6.
The private decloration of a variable achieves the encaspulation or information hiding principle of Object Oriented Programming (OOP). It is useful because it restricts user access to any variable
declared using private so that the program may not be altered and lose its intended function.

# Question 7. 
Java would choose the first contructor through method overloading. 

# Question 8.
Since x and y is private, we don't have direct access to the point x and y, which would eliminate option 1 and 2. Option 3 creates a new "this variable" which would have a compile error. Option 4 would work as it 
calls a get method to access the private x and y. Option 5 doesn't declare a new x and y, so it tries to access the parent's x and y which are private.

# Question 9.
There would be a compile error because you need to have the super line first when declaring the constructor.

# Question 10.
The program will compile, however it will not give us the answer we are looking for

# Question 11.
In Option 1, since sum x_y is private it woudlnt work. Option 2 would work. In Option 3 sum x_y is private. 

