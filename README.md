# CS121_project2 ~> Bubble sort using pointers and functions
## Overview and Expectations
We are making a bubblesort program using functions and pointers. The idea was NOT to come out with the most efective sorting algorithm but implement to concepts of C and open our brains into newer nodes of thinking. With the given semi-start code the following was accomplished- reverse engineering the logic, i.e., using the broader idea sample to breakdown to self the details of each function, learning reusability and background breakdown in this procedural language(breaking the code into series of functions/methods and (here)arrays, etc) AND building with these blocks the clearer bigger picture. 

Therefore, the expectations(*with regards to the precise project*) were:
[x] Help you get into the CS mindset: experimenting and playing with code
[x] Give you some experience with the C language
[x] Practice using a compiler
[x] learn about a basic sorting algorithm (we will come back to algorithms later)
[x] Help you practice pointers; the most important idea in C
[x] Explore the relationship between arrays and pointers

And hopefully they were achieved(?)!

*<ins>Personal expectations achieved</ins>*
[x] Attempting to code while having fun, but also opening more ways to think and visual the execution
[x] Making something cool in a new language, where everything has to be self-built
[x] Complete in time
[x] Not being scared to make mistake
[x] Being more open to ask help
[x] MAke even more mistakes and remember the errors
[x] To REMEMBER!! to git add, commit, push; lost my code 5 times due to related errors.
[x] importance of function prototypes, syntax and value of trials and errors.

<ins>Higher goals</ins>: Making this with user input, practice to memorise some vim key commands to reduce wastage of effort, mind and systems.

## List of Functions and about them
- int main()
  primitive function to overview the enitre program and control flow of control and call other functions.
  Its return type is 0, to tell that it ran finr
- void printValues(int *parray)
  This doesnt return anything but gives the output, whenever called with the passed reference(either addresses for x, y or arrays which are pointers themselves)
-void swap(int *a, int *b)
  This doesnt return anything but using pointer variables, interchanges the values in the memory adn thereby isnt returning anything
- void sort(int *arrayval)
  This doesnt return anything but sorts the entire array which is passed in ascending order, comparing and using sort(); and displays the iterations after swapping.

~> for the variables used, the main motive and idea behind to realise pass by value which expects a return type and pass by referece, which would not need a return type as it changes the memory itself. Also, the * pointer of variable and & as address of variable was learnt; which arrays dont need because they themselves are the pointers. 

## Algorithm
Beginning with #include to include the standard library for input and output with .h header extension

Having our fixed variable, the sixe of our own array
declaring the function prototypes to compile them without error while execution
print function with pointer array 
and using for loop to iterate each individual int

swap function taking 2 pointers, called using reference, using a 3rd variable to swap values

sort function with 2 nested loops, and swaping and printing iterations

MAX-1 because for n length of array, only n-1 iterations to need and the remaining 1 automatically is in right place
MAX-i-1 for the remaining places to move in inner loop

main function to declare, initialise, display raw data
test swapping using x,y and displaying

and swapping using swap() and displaying output
return 0 for confirm execution







*loads of Gratitude to Nolan for helping me figure out my mistakes and so kindly, helping even on weekend,the last moment with sooo much details, some direct, some good food for thought :tada:.*

*Document created with <3 and stress and a little sleeplessness by Ananya Sharma.*

