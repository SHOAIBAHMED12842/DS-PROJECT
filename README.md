# DS-PROJECT
Implementation of Cocktail Shaker Sort is made by a group of students in the year 2018 of UIT 2017 batch III semester in the subject name as DATA STRUCTURE (DS).

## Members Includes:
                 
                 MUHAMMAD UNAIS               (17B-017-SE)
                 SHOAIB AHMED                 (17B-033-SE)
                 HASSAN AHMED SIDDIQUE        (17B-049-SE)
# COCKTAIL SHAKER SORT
## INTRODUCTION
Cocktail Shaker Sort is basically a modified version of Bubble Sort called as Bidirectional Bubble Sort because it sort element left to right as bubble sort and also in reverse direction.It is also called Suffle Sort,Ripple Sort or Shuttle Sort.It works 2 times as faster to the bubble sort.It is treated as comparision sort.

### Time Complexity:

                        WORST     :    O(N^2)
                        AVEREGE   :    O(N^2)
                        BEST      :    O(N)
## PSEUDOCODE
    procedure cocktailShakerSort( A : list of sortable items ) defined as:
    do
    swapped := false
    for each i in 0 to length( A ) - 2 do:
      if A[ i ] > A[ i + 1 ]
        swap( A[ i ], A[ i + 1 ] ) 
        swapped := true
      end if
    end for
    if not swapped then 
      break do-while loop
    end if
    swapped := false
    for each i in length( A ) - 2 to 0 do:
      if A[ i ] > A[ i + 1 ] then
        swap( A[ i ], A[ i + 1 ] )
        swapped := true
      end if
    end for
    while swapped 
    end procedure
## ADVANTAGES
It solves the problem of turtles in bubble sort in this turtles is also treated as rabbits by its working with both direction.It does not improve asymtotic performance of bubble sort.

### Turtles:

    It is the smallest element in the list which is shifted left side in its correct position through many iteration in bubble sort which convert into rabbits in cocktail sort which means it is fastly move to the right.
### Rabbits:
        
    It is the largest element in the list which is shifted very fast in right direction in both cocktail as well as bubble sort.
         
## Platform Support
It can be compiled in any version of Microsoft Visual Studio although our project is compile in 2017 version of this.We use 3.5 to 4.7 .NET Framwork to compile it.
## Basic Implementation
We implemented our project by using Array.
## Additional Implementation
We also use list and linked list which is the built in class in MS Visual Studio in C# in order to implement this project.
## Testing The Code And Inputs
User define 3 inputs for our project:


             First input for how many numbers to be sorted. 
             Second input for minimum element in the list to be exist.
             Third input for maximum element in the list to be exist.
After 3 inputs our program is to generate random numbers between minimum an maximum element and sorted through cocktail sort and printed random numbers provide by user range as well as sorted element.
## Handled Exception
Our project handled 4 types of exception:
            
            1-ArithmeticException
            2-StackOverFlowException
            3-FormatException
            4-ArgumentOutOfRangeException
### ArithmeticException:
                  
    It is occur when we provide length of number less then 0.This says that Arithmetic over or underflow has occurred.
### StackOverFlowException:
                  
    It is occur when in put number less then -2,147,483,648 and greater than +2,147,483,647 because we initializes the inputs as Int32.This says that value was either too large or to small for an int 32 or A Stack has overflowed.
### FormatException:
                  
    It is occur when we provide any character instead of numbers in the inputs.This says input string was not in correct format.
### ArgumentOutOfRangeException:
                  
    It is occur when we provide minimum number greater than minimum number.This says that 'minValue' cannot be greater than maxValue Parameter name: minValueoccurred or Argument value is out of range.
## POSTER
We have also implemented our project infront of our teacher so we are uploaded our project poster with our code file you can find it in COCKTAIL SORT folder.
