# DSA IN JAVA

## syntax 
  
'''
  package package_name
  
  public class class_name{

    public static void main(Strings[] args)# use psvma{

        ## to print something --- sout

        system.out.println("  ");

        ## ln for next line or u  can insert \n atlast 

    }
  }
'''

### printing space between x and y when not using println

* (x + " ")


## printing numbers 

* printing numbers as same as u print any alphabet but u can write without using double quotes . 

* u are writing b\w the quotes anything it is written as it is . but without using any operations it will give the output.


## variables

using data type --  
* int x = 8;  [declaration and initialization]

* int y;     [declaration]

* y =9;  [initialization]

### always declaration is done only one time and initialization can be done many times and last initialization is the updation .


## modifying values of the variables 

* always gives the right hand side vaue to the right hand side one 

### assigning values also done in one line 

'''int x = 4 , y = 9;'''

## datatypes

* in java , float x = 5f;  otherwise use double x = 7;

int operation int === int 

int operation duble === double 

* and also double is stored in  the double


## comments use 
* // or
*  /* multi line comment */

## in java there is no use of exponentiation sign ** for raise up the power

## variable naming rules 

1. variables can be start from alphabet or _ or $
2. special characters except _ or $ are not allowed 
3. blanks , commas are not allowed
4. keywords are not allowed

## input 

'''
import java.util.Scanner
* outiside the class but inside the package 

Scanner sc = new Scanner(System.in);
int x = sc.nextInt();

* jo datatype aap variale ko denge bhyi apka use hoga as after next 
'''

* if you want then you can close after taking the input 
-- sc.close()


## modulus operator 

* it is working on the integer or any other datatype also and return the remainder

* properties
    1.  a%b = a , (a<b)
    2.  a%(-b) = a%b
    3.  -a%b = -(a%b)

## division of the datatypes 

* int / int = int
* double/ int = double 
* double / double = double
* int / double = double

## char datatype 

* single quote me only characters we can write 

* ascii values 
    1. a....z === 97.....122
    2. A...Z  === 65.....90
    3. 0....9 === 48.....57


## typecasting 
-- conversion of one datatype into other datatype

* explicit typecasting -- char x = 'd';
                          int y = (int)x;

* implicit typecasting -- char x = 'd';
                          int y = x;

* integer to the character ---- use explicit typecasting

* one more way of typecasting is add 0

    #### if we add or doing any operation on the char and integer it will always gives the integer value , firstly convert the char into the integer .

    #### to get the ascii value just add +0 in it 

## increment and decrement operators 
x++ , ++x , x-- , --x

## relational operators
-- comparision operator. returns boolean value(true or false)

## boolean datatype 
-- can also store the true , false value in it 
-- it is inconvertible datatype
