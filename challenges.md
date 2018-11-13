## Results for First Reverse 

Have the function FirstReverse(str) take the str parameter being passed and return the string in reversed order. For example: if the input string is "Hello World and Coders" then your program should return the string sredoC dna dlroW olleH. 

This challenge requires you to reverse an input string. A string in programming is sequence of characters and a character is simply a symbol that you can enter for the computer to read, such as a,b,z,$,4,? etc. An example of a string may be: "Hello" or "abc123$??." Strings always need to be written between double or single quotes (" or ').

There exist several built-in functions in almost all languages that reverse a string for you very easily, so we'll cover how to first reverse a string manually and then we'll show you how to do it using built-in functions.

A simple way to reverse a string would be to create a new string and fill it with the characters from the original string, but backwards. To do this, we need to loop through the original string starting from the end, and every iteration of the loop we move to the previous character in the string. Here is an example: 

``` Javascript

function FirstReverse(str) { 

  var newString = "";

  // add each character to newString
  for (var i = str.length - 1; i >= 0; i--) {   
    newString = newString + str.charAt(i);
  }

  return newString;
         
}
   
FirstReverse(readline());

```