# Goal Sheet 03

**Problem GS03-01 (Lists)**

Write a program that is passed a number and returns string containing a fortune.  You will decide which fortune (of twenty possible) based on the (random) number that is passed to the function.  The fortunes are contained in a list of strings (local list in the function).  The function must pass the fortune back to the calling function.  Output the fortune in the calling function.  You must loop the program (where the function is called) so that the user can keep getting fortunes until opting to quit.

**Problem GS03-02 (Dictionaries)**

Create two lists with at least 20 items in each of them.  (The lists must be the same size.)  Make sure the first list does not have any duplicates.  Then, create a map from the two lists.  Use the first list (without any duplicates) as the keys, and the second list (which may have duplicates) as the values.  An example of the two lists.  First list: numbers from 1 through 20.  Second list: the squares of those numbers.

**Problem GS03-03 (Strings and Regular expressions)**

Create a program that gets dates from the user.  The program should make sure that the date format is of the form mm/dd/yyyy, that is month first with two digits (a leading zero for January through September), followed by a two-digit day, followed by the year with four digits.  The month, day, and year should each be separated by a slash or some other character designated by you.  Use a regular expression to verify the date before putting it into a list of dates.  Make the program loop to get dates and some numeric data that will be the keys and values of a dictionary.  Loop until the user is finished inputting data.

**Problem GS03-04 (Files)**
Create a comma-delimited file with an int, a float, a character array (no spaces), and a character (in that order) on each of 10 rows.  Write a program to get in the data and then output it into a tab-delimited file.  (Do so without using the CSV module.  You will do that later.)  You may use the data below as the data for your file:

```
1,2.3,abcdef,q
2,3.4,ghijklmn,r
3,4.5,opqrstu,s
4,5.6,vw,t
5,6.7,xyzpdq,u
6,7.8,abc123,v
7,8.9,qqqrrrsss,w
8,9.01,tea,x
9,0.12,taxation,y
10,11.12,present,z
```
**Problem GS03-05 (REGEX, dictionary, files)**

Expand Problem GS03-03 to first get data into the dictionary by reading from a given file (and put it in a dictionary).  Then, get data into the same dictionary.  Making sure to check that the keys (dates) are not being duplicated.  When the user is done collecing the data, write the data out to a comma separated file with date, separated by a comma and the different date-data pairs on separate lines (an example is shown below).

```
01/01/2000,1.2
01/02/2010,2.3
10/25/2011,3.4
03/15/2009,4.5
```

**Problem GS03-06 (major program - earthquakes)**

You gathered some information in the first part of the major program.  Now do something with that information.  Create a global list.  It will contain the earthquakes the user has felt.  Date and size.  Use a function to gather the information and put it into the list.  Loop around that function (keep calling the function) as long as the user has more information to input.
