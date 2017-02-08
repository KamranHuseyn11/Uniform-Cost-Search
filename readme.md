Uniform Cost Search
===================


This assignment is implementation of Uniform Cost Search which was a part of **Artificial Intelligence** course taken at **University of Texas at Arlington**

----------


Details
-------------
> **Name:** Vipulkumar Mahadik
> **Language:** Python
> **Course:** Artificial Intelligence
> **Course Number:** CSE5360


----------


Structure
-------------
>- The code is divided into 2 functions, main function and UCF function.
>- Main function reads the command line input and prepares the graph based on the data from the input.txt file.
>- The graph along with source and destination is the passed to the UCF function to calculate the path and cost.
>- The UCF function, if finds the path, returns the full path as list of lists (total route) and total cost.
>- Else if no path is found it returns None.
>- After the result is fetched in the main function the type of result is checked.
>- If type is none it prints out distance: infinity and route: none.
>- Else it prints the total cost returned by the function and then it displays the step by step path to destination.


In depth explanation of code can be found in [file]().



Implementation
-------------
>- Keep the python file and input.txt file in a same directory
>- Execute Command:
>python find_route.py input.txt city1 city2
