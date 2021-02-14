# Chapter-4
Exercises from the book

# Exercise 1 - SSN

<code>#include <stdio.h></code>
 
<code>int main (){</code>

 <code>printf("My name is Jenny Guadalupe Bacab Saavedra, my SSN is 16139897306 and I was born on 09/03/1998");</code>

 <code>return 0;</code>
 
<code>}</code>


# Exercise 2 - The big E

#include <stdio.h>

 int main (){

 printf("***** \n*\n*\n*****\n*\n*\n*****");

 return 0;

}

# Exercise 3 - Rectangle

#include <stdio.h>

int main(){

 //please note all units are in inches

 int width = 3;
 
 int height = 5;

 int area = width*height;
 
 int perimeter = 2* width + 2* height;

 printf("The area is %i inches and the perimeter is %i inches", area, perimeter);

 return 0;

//changes to work for a rectangle with a width of 6.8 inches and a lenght of 2.3 inches would be to change the variable type to float and the numbers

}

# Exercise 4 - HELLO
https://repl.it/@JennyBacab/Chapter4Exercises#main.c

# Exercise 5 - Mistakes

#include <stdio.h>

int main(){

//first mistake, float as d
float floatingpoint;
floatingpoint = 3.05;
printf("The float is %d\n", floatingpoint);

//second mistake, integer as float
int integer;
integer = 3;
printf("The integer is %f\n",integer);

//third mistake, char as d
char plswork ='e';
printf("The char is %d", plswork);

return 0;

}


