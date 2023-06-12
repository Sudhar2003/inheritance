# inheritance
# Java-Experiment.08
# Inheritance
# Aim:
   To write a Java program using inheritance one class can acquire the properties of others.
# Algorithm:
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Animal" and create required statements.

Step 3 : Create a another class called "Bird" and create required statements.

Step 3 : Create another class,called the Solution Class.

Step 4 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 5 : Display the statements from the first and secomd Class using Solution Class in the terminal.

# Program:
~~~
class Animal{
void walk(){
System.out.println("I am walking");
  }
}

class Bird extends Animal{
void fly(){
System.out.println("I am flying");
  }
}

public class Solution{
public static void main(String args[]){
Bird bird = new Bird();
bird.walk();
bird.fly();
  }
}
~~~
# Output:
![image](https://github.com/Sudhar2003/inheritance/assets/128343775/e5fc085e-ccb0-4eff-a01e-b7e7d726ef65)



# Result
    We have successfully created a Java program using inheritance one class can acquire the properties of others.
