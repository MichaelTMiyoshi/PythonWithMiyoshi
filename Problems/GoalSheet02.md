# Goal Sheet 02

**Problem GS02-01 (if)**

Write a program that gives a student a science quiz.  Get the name of the student (string) and address the student when asking each question.  Your quiz will have 3 multiple-choice questions.  Each question will have a minimum of four answers.  You must use if to determine whether your student gave the correct answer.  You must also automatically score the quiz.  Each correct answer gives the student four points and each incorrect answer subtracts one point.  (Yes, scores can be negative.)  Answers that are not one of the answers listed will neither add to nor subtract from the score.  Make sure to output the user’s name and score at the end of the quiz.

**Problem GS02-02 (nested if)**

Create a maze.  The maze looks like the following, but you need not have a graphical user interface (GUI).  Instead, you will give the user choices at each juncture.  There is a catch to this maze.  When you go through a door, that particular door (not every door in the room) shuts behind you and you cannot enter (or exit) it again.  This leads to many dead ends.

We have not yet covered loops, so you must use nested branching.  Be aware that there are three or more levels of nesting.  Also, make sure that the user is able to take every path to the very end (even if it is a dead end).

![picture](https://github.com/MichaelTMiyoshi/PythonWithMiyoshi/blob/main/images/CPPMaze.png)

**Problem GS02-03 (for)**

Write a program that uses only one int variable to output to the screen the numbers one through ten.  Make sure to put each number on its own line.  Do not just output the numbers (using no variables).  Output the one variable.  Then, use a for loop to output the numbers 100-200.  Make sure that only 10 numbers are on a line.  (Which means that you will need to separate them by tabs or some appropriate number of spaces.)  Then, use another for loop to simulate 100 six-sided die throws.  (Use random numbers.)  Again, make sure that only 10 die throws are on each line.

**Problem GS02-04 (while)**

Create a new maze.  The maze will have the same exact pattern as that from GS2-2, but the doors do not close behind the user.  Instead of using all the code from the old program and trying to modify it, it is easier to start the code from scratch with an overarching loop and branching for each room.

![picture](https://github.com/MichaelTMiyoshi/PythonWithMiyoshi/blob/main/images/CPPMaze.png)

**Problem GS02-05 (functions)**

Write a program that reduces fractions using a function.  The function will return an int and have two int arguments.  The returned int will be the greatest common factor (GCF).  The function prototype and the GCF function from the example in the chapter may be used as a starting point.

**Problem GS2-6 (reverse a string)**

Write a program that reverses the characters in a string.  While there is probably a function that does this, using it does not count as writing a function.  Your function should pass one string to it.  (See function signature below.)  The function gets passed the original string and returns the reversed string.  Output the original and reversed strings in the calling function.  Loop the program until the user does not want to reverse any more strings.

```
  def Reverser(original):
 ```
