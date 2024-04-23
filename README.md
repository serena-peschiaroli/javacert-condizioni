- 1. 

Given the code fragment:


String flavors[] = {“Vanilla“, “Chocolate“};

int choice = 2;

switch(choice) {

  case 1:

    System.out.println(“Selected “ + flavors[1] + “ flavor.“);

    break;

  case 2:

    System.out.println(“Selected “ + flavors[2] + “ flavor.“);

    break;

  default:

    System.out.println(“Thank you!“);

}


What is the result?

The are 1 correct answers

Selected null flavor.
Selected Chocolate flavor.
- [x] An ArrayIndexOutofBoundsException is thrown at run time
Selected Chocolate flavor.
Thank you!

(Flavor array has indexes  0 and 1 so calling 2 throws an exception.)

__________________________________________

- 2. 

Given the code fragment:


int value = 10;

int a = ++value;
//preincrement, value=11 && a==11

int b = value; //11
int c = value++;//post increment, here 11, then value is 12

if (a <= b && a <= c) {//true

 if (b <=c) { //true

  a = ++b; //12

 } else {

  a = ++c;

 }

}

System.out.println(a);


What is the result?

The are 1 correct answers

10
11
- [x] 12
13

_____________________________________________

- 3. 

Given the following code:

 

public class Application {

public static void main(String[] args) {

int b = 3;

if (!(b > 3)) { //true

System.out.println(“square“);

}

{

System.out.println(“circle“);//stand alone code so its printed

}

System.out.println(“…“);

}

}

 

And the invocation:

java Application

What is the result?

The are 1 correct answers
An exception is thrownCompilation fails
- [x] square, circle, …
circle, …
square, …


______________________________________________________-

- 4. 

Project the anticipated result of the following code.
The are 1 correct answers

package com.example;
public class Main{
public static void main(String[] args) {
int a = 1;
if(a++ == 1){//post increment, here  a=1, then a =2
a -= 1;

System.out.print(a);
}
}
}

Zero
- [x] 1
2
-1
-2
11


__________________________________________________

- 5. 

Given the code fragment:


// line n1

switch (var) {

  case “1“: //case with string "1"

    System.out.println(“one“);

    break;

}


Which code fragment, when inserted at line n1, enables the code to print one?

The are 1 correct answers

char var = ‘1‘;
String var = “1“;
int var = 1;
- [x] String var = 1;

_______________________________________________________

- 6. 

Given:

public class ArithmeticResultsOutput {

 public static void main(String[] args) {

  int i, j = 0; //i not initialized

  if (i++ == ++j) {

   System.out.println(“True: i=“ + i + “,j=“ + j);

  } else {

   System.out.println(“False: i=“ + i + “,j=“ + j);

  }

 }

}

What will be printed to standard out?

The are 1 correct answers

-[x] Compilation fails
False: i=0,j=1
True: i=1,j=1
True: i=0,j=1
An exception is thrown
False: i=1,j=1

________________________________________

- 7. 

Given:

 

public static void main(String[] args) {

boolean value1 = 10 + 5 >= 2 + 13;

int value2 = 0;

if (value1 == true) { //true

value2 = 5 * 3 + 10 / 2;

} else {

value2 = 5 / 3 + 10 * 2;

}

System.out.println(value2);

}

 

What is the result?

The are 1 correct answers

- [x] 20
32
A compilation error occurs
21