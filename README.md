Download Link: https://assignmentchef.com/product/solved-cs40032-assignment-4-lambda-in-c
<br>
<strong>Instructions</strong>: Please solve the questions using pen and paper and scan the images. Every image should contain your roll number and name.

<ol>

 <li>Answer the following questions based on the given instructions. <strong>[15]</strong></li>

</ol>

(a) Write output of the following code snippet.                                               <strong>2</strong>

#include &lt;iostream&gt; using namespace std; int main(){ auto con= 8; auto l = [&amp;](int x) { return x*con; } ;

–con;

cout &lt;&lt; l(5) &lt;&lt; endl ; auto m = [=] ( int x ) { return x+con; } ;

++con; cout &lt;&lt; l(5)&lt;&lt;endl&lt;&lt;m(5) &lt;&lt;endl ; return 0;

}

<ul>

 <li>Write output of the following code snippet. <strong>2</strong></li>

</ul>

#include &lt;iostream&gt; using namespace std; int main(){ int c=5; auto f1 = [=] ( ) mutable {++c ; cout &lt;&lt; c ; } ; auto f2 = [&amp;] ( ) mutable {c+=3 ; cout &lt;&lt; c ; } ; f1() ; f2() ; cout &lt;&lt; c ; f2();

cout &lt;&lt; c ; return 0 ;

}

<ul>

 <li>Write a code snippet containing a lambda expression in C++ that will do the following: <strong>3</strong></li>

</ul>

Read a temperature value in Fahrenheit scale from the keyboard in a variable F.

Convert the temperature value to its corresponding value in Centigrade scale and store it in a variable C.

Print the value of C in the display.

Note that the temperature values are real numbers. Also, they can be positive, negative, or 0.

<ul>

 <li>Write a code snippet containing a lambda expression in C++ that will do the following: <strong>3</strong></li>

</ul>

Read the length L and width W of a rectangle.

Compute the area A and perimeter P of the rectangle.

Print the values of A and P with a suitable message.

You can assume that L and W are integers.

1

<ul>

 <li>Write a code snippet containing a lambda expression in C++ to compute and print the taxi fare based on the following chart. Total number of Kilometers traveled will be input by the user as an integer.</li>

</ul>

<strong>5</strong>

First 12 KM: Rs. 100/Next 4 KM: Rs. 8 / KM

Next 4 KM: Rs 6 / KM

Above 20 KM: Rs 5 / KM

The program will –

Read in the distance traveled (integer but don’t enter 0).

Print out the corresponding fare.

Example:- If user input is 27, then the total fare will be- (100+(4*8)+(4*6)+ (7*5)) = 191.

<ol start="2">

 <li>Write a C++ code to print all permutations of a given string using</li>

</ol>

<ul>

 <li></li>

 <li>Lambda Expression.</li>

</ul>

<strong>[5 * 2 = 10]</strong>

You can print the permutations in any order and no character will be repeated in input string.

Example: – For string ABC permutations will be:

ABC

ACB

BAC

BCA

CAB

CBA

2