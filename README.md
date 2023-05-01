Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-9-introduction-function-overloading-references-dynamic-memory-allocation
<br>
<h1><strong>Problem 9.1 </strong>Check g++ compiler &amp; Write simple program</h1>

Make sure that you have g++ installed and you can use an IDE or an editor to write and compile C++ code.

Write a program that reads your country of origin from the standard input (i.e., keyboard) and prints it on the standard output (i.e., screen) using cin and cout. <em>You can assume that the input will be valid and will not contain spaces.</em>

<h1><strong>Problem 9.2 </strong>Using different variables</h1>

Write a program which reads one integer value n, one double value x and a string s from the keyboard. Then s and x should be printed on the screen (separated by ’:’ with a newline after the double value). This printing should be repeated n times.

<em>You can assume that the input will be valid and the string will not contain spaces.</em>

<h1><strong>Problem 9.3 </strong>Absolute value function</h1>

Consider the abs function, which determines the absolute values of a real number. The function returns the following values:

-x for x <em>&lt; </em>0<em>, </em>x for x≥ 0<em>.</em>

Write a function which determines and returns the absolute values of a float parameter. Then write a main() function which calls the function from above and prints on the screen the returned value. You may not use any library functions related to the absolute value.

<em>You can assume that the input will be valid.</em>

<table width="457">

 <tbody>

  <tr>

   <td width="457"><strong>Problem 9.4 </strong><em>Function overloading</em></td>

  </tr>

  <tr>

   <td width="457"> </td>

  </tr>

 </tbody>

</table>

<h2>Language: C++</h2>

Write a program that provides two overloaded functions named … mycount(…). This function either computes the difference between the second and first parameter (in this order) if integers are passed or counts the number of occurrences of a character if a character and a string are passed.

For example, mycount(7, 3) should return −4 and mycount(’i’, “this is a string”) should return 3. In case of no occurrence 0 should be returned.

Write a simple main() function that demonstrates the above described behavior for both functions.

<em>You can assume that the input will be valid.</em>

<table width="457">

 <tbody>

  <tr>

   <td width="457"><strong>Problem 9.5 </strong><em>A guessing game</em></td>

  </tr>

  <tr>

   <td width="457"> </td>

  </tr>

 </tbody>

</table>

<h2>Language: C++</h2>

Write a simple program for implementing the guessing game as outlined in the slides (Tutorial 9, slides 5−6).

<em>You can assume that the input will be valid.</em>

<table width="328">

 <tbody>

  <tr>

   <td width="328"><strong>Problem 9.6 </strong><em>Function overloading</em></td>

  </tr>

 </tbody>

</table>

<h2>Language: C++</h2>

Write three overloaded functions … myfirst(…) which should do the following:

<ul>

 <li>if called with an array of integers, it determines and returns the first positive and even value from the array. If no such element exists then −1 should be returned;</li>

 <li>if called with an array of doubles, it determines and returns the first negative element which does not have a fractional part. If no such element exists then −1<em>.</em>1 should be returned;</li>

 <li>if called with an array of chars, it determines and returns the first element which is a consonant. If no consonants are present in the array then the character ’0’ should be returned.</li>

</ul>

Write a program which calls the above functions and illustrates their effect. You may choose to enter test data from the keyboard or to initialize variables within your code. <em>You can assume that the input will be valid.</em>

<h1><strong>Problem 9.7 </strong>Swapping with call-by-reference</h1>

Write a program swapref.cpp, which provides three overloaded functions void swapping(…). These functions should swap two integers, two floats, and two pointers to char. The swapping should be done by a “real” call-by-reference (i.e., not by using <sup>∗</sup>). Complete the following code fragment:

#include &lt;iostream&gt;

using namespace std;

void swapping(…) { …. } // swap ints void swapping(…) { …. } // swap floats void swapping(…) { …. } // swap char pointers

int main(void) {

int a = 7, b = 15; float x = 3.5, y = 9.2; const char <sup>∗</sup>str1 = “One”; const char <sup>∗</sup>str2 = “Two”;

cout &lt;&lt; “a=” &lt;&lt; a &lt;&lt; “, b=” &lt;&lt; b &lt;&lt; endl; cout &lt;&lt; “x=” &lt;&lt; x &lt;&lt; “, y=” &lt;&lt; y &lt;&lt; endl; cout &lt;&lt; “str1=” &lt;&lt; str1 &lt;&lt; “, str2=” &lt;&lt; str2 &lt;&lt; endl;

swapping(a, b); swapping(x, y); swapping(str1, str2);

cout &lt;&lt; “a=” &lt;&lt; a &lt;&lt; “, b=” &lt;&lt; b &lt;&lt; endl; cout &lt;&lt; “x=” &lt;&lt; x &lt;&lt; “, y=” &lt;&lt; y &lt;&lt; endl; cout &lt;&lt; “str1=” &lt;&lt; str1 &lt;&lt; “, str2=” &lt;&lt; str2 &lt;&lt; endl; return 0; }

<h1><strong>Problem 9.8 </strong>Dynamic allocation and references                                                         (</h1>

Write a program which reads from the keyboard an integer n followed by n integer values which are to be stored in a dynamically allocated array a. Your program should define a function void subtract_max(…) for determining the maximum value in the array and subtracting this maximum from all elements of the array. You should also define a function called void deallocate(…) for releasing the memory which was allocated for the array. The main() function should allocate memory for the array, call the function, illustrate its effect by printing the values of the array and finally deallocate the memory occupied by the array by calling the second function from above. <em>You can assume that the input will be valid.</em>

<table width="457">

 <tbody>

  <tr>

   <td width="457"><strong>Problem 9.9 </strong><em>Word guessing</em></td>

  </tr>

  <tr>

   <td width="457"> </td>

  </tr>

 </tbody>

</table>

<h2>Language: C++</h2>

Write a program that stores an array of words (containing ”computer”, ”television”, ”keyboard”, ”laptop”, ”mouse”) and 12 other words of your choice in an array of strings. Inside of a game loop your program should randomly choose one word out of the 17 possible words. The program should print the word on the screen after replacing all vowels by underscores, then the player should try to guess the word. After the player has guessed the right word, the number of tries should be printed on the screen and the player should be asked whether he/she wishes to play again. If the player enters ”quit” as a word guess, then the game should immediately stop.

<em>You can assume that the input will be valid and that ”quit” will not be in the set of words to be guessed.</em>