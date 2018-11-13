/**This project was built Caroline Jubran**/
--> The project is based on two main classes, Monom and Polynom, a helper class Monom_Comperator and a test class 
                                      /*********CLASS MONOM***********/

------------->This class represent a function of type a*x^b.<--------------
a - coefficient, of type double.
b - power, of type int.

There are 3 constructors:

1.empty constructor - construct a zero Monom (a = b = 0).

2. initialize by string - construct a Monom from a string.

3. copy constructor - construct a copy of a given Monom.

4.constructor- construct a new Monom and gives a value to it 

                                       /**Class functionalities are**/

1. add - add a Monom to a Monom.

2. substract - substract a Monom from a monom.

3. multiply - multiply a Monom by a Monom.

4. f(x) - calculates the value of f for a given x.

5. isEqual - test if a Monom is  equal to a different Monom.

6. derivative-calculates the derivative of the monom

7. getters and setters.

                                  /**********CLASS POLYNOM*************/
--------------->This class represenst a function of type a1*x^b1 + .. + a_n*x^b_n.<--------------

Every Polynom is a list of m0,m1,..,m_n Monom's.

There are 3 constructors:

1. empty constructor - construct a zero Polynom.

2.initialize by string - construct a Polynom from a given string.

3. copy constructor - construct a copy of a given Polynom.
                                 
                                                /**Class functionalities are**/

1. add(Monom) - add a Monom to a Polynom.
add(Polynom) - add a Polynom to a Polynom.

2. substract(Monom) - substract a Monom from a Polynom.
substract(Polynom) - substract a Polynom from a Polynom.

3. multiply(Monom) - multiply a Polynom by a Monom.
multiply(Polynom) - multiply a Polynom by a Polynom.
multiply(Polynom,Polynom) - multiply two Polynom.

4. f(x) - calculates a value of the Polynom for a given x.

5.derivative(x) - value of the derivative of x.

6.area - calculate the area of the Polynom between two points.

7. root - search if the Polynom has a root between two points.

8. iterator - iterate over the collection.

                             /*******class Monom_Comperator*************/
This class implements Comperator interface of type Monom.
functionalities:
compare - compare between two Monom's.
                              /*************Class test**************/
This class is used to test every functionality of the project