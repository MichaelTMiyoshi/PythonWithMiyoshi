# Competency Tests

I have students take what I call competency tests.  They write code by hand.  I do not keep the tests a secret.  Instead, they are her available from day one (or even before).

One of the reasons I decided to have students write code by hand is because of the AP Computer Science test.  Since those students needed to write code without the use of a compiler, I figured my intro students ought to do that too.  I figured they needed to be their own compilers.  An industry professional told me later that coding by hand was also beneficial because prospective employees needed to write code during interviews.  They coded by hand on whiteboards.  So I have continued to require my students to write code by hand.  And even though Programming for the rest of us is a class for those not really desiring (at this point) to become coding professionals, it is beneficial for these students to be their own compilers too.

I am including all the competency tests in one place.  The directions I give to my students are below followed by the competency tests themselves.  By the way, I tell my students that they only have 15-20 minutes to finish (see the instructions), but I rarely enforce that.

## Introduction to Competency Tests and Instructions

Competency tests are writing code by hand.  Yes, you need to use pencil (or pen) and paper.  No compiler except your own brain.  They ought to take each person about 15-20 minutes to finish.  They are used to test your ability to think through code without the help of a compiler.  And they test specific concepts.  You only need to write the code snippets necessary to complete the tasks.  You do not need to put in int main() unless specifically told to do so in the instructions.

<hr>

### CT – Variables, Constants, and Division

Demonstrate your competence in using the math operators by creating a short code segment for **each** of the following scenarios, and give example numbers and answers:
1. You have three numbers called n1, n2, and n3 and you want to determine the remainders of the division of each of the numbers by 7.  Give three example numbers (at least one number must be less than 7) and the answers of all 3 remainders (modulus operation).  (Put the answers in comments after the divisions.) (Some example numbers: n1 = 3, n2 = 11, n3 = 19)
1. You have three numberss called n1, n2, and n3 and you want to determine the value of each divided by the other.  Give three example numbers and the answers of all 6 divisions.  (Put the answers in comments after the divisions.) (Some example numbers: n1 = 3, n2 = 11, n3 = 19)
1. You have two numbers called n1 and n2 and you want to determine what each divided by the other will be.  You want to make sure that when you divide by n2, you get a float answer (a number with a decimal) and when you divide by n1, you get an int answer (a number without a decimal).  Give two example numbers and answers to both divisions.  (Put the answers in comments after the divisions.)  Make sure that the float has a decimal value not equal to zero (i.e. 3.2 not 3.0). (Some example numbers: n1 = 3.7, n2 = 8)
1. You have two numbers called n1 and n2 and you want to determine what each divided by the other will be (but the opposite of the previous question).  You want to make sure that when you divide by n1, you get a float answer (a number with a decimal) and when you divide by n2, you get an int answer (a number without a decimal).  Use the same two example numbers as above and give answers to both divisions.  (Put the answers in comments after the divisions.)  Make sure that the float has a decimal value not equal to zero (i.e. 3.2 not 3.0). (Some example numbers: n1 = 3.7, n2 = 8)
<hr>

### CT – Branching

<ol>
<li>Demonstrate your competence in using the if-structure by creating an if-structure for <b>both</b> of the following scenarios:
<ol type="A">
<li>You have three numbers called n1, n2, and n3 and want to find out which has the middle value.  Expected outputs: “n1 is the middle value”, “n2 is the middle value”, “n3 is the middle value”, “there is no middle value” or you can output the number instead of saying which variable is the middle</li>
<li>You have three numbers called n1, n2, and n3 and you want to see whether all, some, or none of the values is positive.  Expected outputs: “All the values are positive”, “Some of the values are positive”, “None of the values are positive”</li>
</ol>
</ol>

<hr>

### CT – Looping

When you do the looping competency test, make sure to do one for and one while loop.  You must do all A or all B problems.  Do not mix and match.  In other words, do 1A, 2A or 1B, 2B.  Those are your two choices of problems.

1.  Demonstrate your competence in using the for loop by creating a for loop for one of the following scenarios:

A.	Output the numbers from 15 through 125 (inclusive) skipping 25, 30, and 35.  Use only one loop.  Put tabs between the numbers and only put 5 numbers on each line.

Expected output (first four lines):
```
15	16	17	18	19
20	21	22	23	24
26	27	28	29	31
32	33	34	36	37
```

B.	Count (and output) by a given increment (iIncrement) from a given start point (iStart) to a given end point (iEnd).

2.  Demonstrate your competence in using the while loop by creating a while loop for one of the following scenarios:

A.	Create an error-checking loop that makes sure the user gives a positive input into a number called iNum.

B.	Output the numbers from 1 through 100 (inclusive) skipping 30, 40, and 50.  Use only one loop.  Put tabs between the numbers and only put 6 numbers on each line.

Expected output (first line, then three other lines):
```
1	2	3	4	5	6
…
19	20	21	22	23	24
25	26	27	38	29	31
32	33	34	35	36	37
```

<hr>

### CT – Lists & Dictionaries

Demonstrate your competence in using Lists (and loops) for each of the following scenarios:

1.	Declare a List that will hold 100 numbers.  Initialize that List (using a loop) with the numbers 1 through 100.  (_**Note** to my students: If you choose to initialize the List without using a loop, the best score you can receive is 2.5/4._)
1.	Declare a two-dimensional List of numbers.  Use a nested loop to initialize the List to have the following values:  (_**Note** to my students: If you choose to initialize the two-dimensional List without using nested loops, the best score you can receive is 2.5/4._)
```
1	2	3	4	5
2	4	6	8	10
3	6	9	12	15
4	8	12	16	20
5	10	15	20	25
```
1.	Create a dictionary with at least 5 states (keys) and their capitals (values).  Use a loop to output the data with the state followed by the capital separated by a colon.  Each entry in the dictionary must be output.  The output should look like the following:
```
Washington: Olympia
Oregon: Salem
Idaho: Boise
Montana: Helena
California: Sacramento
```

<hr>

### CT – Strings

Demonstrate your competence in using strings for each of the following scenarios:
1.	Create a String called sFName and initialize it to your first name.  Output the 3rd character in the String.  Then change the String to hold the name, Rumplestiltskin.

Expected outcome:
```
First name: Annabelle		Output: n
First name: Jo			Output: error (or error message that you choose to show)
```

2.	Create a String called sMName and initialize it to your middle name.  Output the first 5 characters using a loop and subscripts.  Make sure the loop does not try to access characters beyond the last char in your middle name.  (You will need a branching statement to determine whether or not your name is less than 5 chars to make your answer more general, and to get all four points.  Loss of 1 point if a name shorter than 5 characters makes your loop give an out of bounds error.)  If you have no middle name, initialize the variable to “NoMiddleName” (with or without spaces).

Expected outcome:
```
Middle name: NoMiddleName		Output: NoMid
Middle name: Cruz			Output: Cruz
Middle name: Richard			Output: Richa
```

3.	Create a String called sLName and initialize it to your last name.  Output the name in reverse order.  (Without using a method from the String class or any other function that you do not write.)

<hr>

### CT – File I/O
11306	Use streams to manage input and output including files

(Note: This competency tests may need to be updated.  Still mulling it over.)

Demonstrate your competence in using data files by writing code for the following scenario:
1.	You have data that you want to store and then retrieve.  You must decide what type of delimiting you would like to use (use comma- or tab-delimiting) to store the following data (The first row is not part of the data, just labels):
```
Name		Age	Height (in)	Weight (lb)	Phone #
Loretta		18	66		130		425.844.1231
Mike		16	68		145		425.844.1232
Charles		17	72		160		425.844.1233
Gracie		15	74		205		425.844.1234
Anna		19	73		170		425.844.1235
George		15	62		115		425.844.1236
```
[_**Note**: If you copy the above data, it has extra tabs so that it looks correct in this file._]

a.	Write code to open a new file for writing.  The file name will be names.txt.  Use a loop to get data from the user (who would then input the above data).  End the loop by asking whether the user is done entering data.  Do not just use Strings for each piece of data.  Use the appropriate data types (name, phone: string; age, height, weight: int).  Tell what type of delimiting you are using (can be a comment in the written code) and output the data to the file accordingly.

b.	Write out what **all** the above data would look like in your file.  Show tabs as \t or commas as commas (,).  Do not put in extra spaces.

c.	Write code that will get the data from the data file (you may hardcode the filename in your code) and output it to the screen.  Get the username and phone number as strings and the other data as unsigned integers.  Use a loop that does not assume there are only 6 pieces of data.

<hr>

### CT – Functions

Demonstrate your competence in using functions by creating a function (or function signature) for **each** of the following scenarios:

1.	Create a function signature for a function that will not return a value and takes 3 number arguments.

2.	Create a function that takes in two numbers and returns the LOWER value.

Expected outcomes: 

Inputs | Output
-----: | -----:
3, 5   | 3
-7, 2  | -7
9, 9   | 9

3.	Create a function that takes one String argument and returns a String which has the original String except that the first letter is capitalized and all the letters after spaces are also capitilized.  Use the following function signature: 

```
def Capitalize(original)
```

Expected outcomes: 

Original string | Capitalized string
----- | -----
the rain in spain | The Rain In Spain
what is your quest? | What Is Your Quest?
my name is INIGO! | My Name Is INIGO!

<hr>

### CT – enums

Demonstrate your competence in using enum and struct by using and/or creating one for **each** of the following scenarios:

1.	Create enumerated sizes using the following definitions:
```
a.	each = 1
b.	dozen = 12
c.	gross = 144
```
Then use those enumerated sizes with two different variables called boxes and envelopes.

<hr>

### CT – Classes

Demonstrate your competence in using classes for **both** of the following scenarios:
1.	Create a square class.  It must include the proper instance variables and methods to set and get those values.  It must also include a default constructor and methods that return the perimeter and area of the square.
2.	Create a person class.  It must include instance variables for name and age.  It must also include a default constructor and methods to set and get the values of those instance variables.

<hr>

That is it for my intro competency tests.  Like I said, my students have access to these from the first time they set foot in class, so may prepare from day one.

To those taking the competency tests, have fun being your own compiler and your own printer.
