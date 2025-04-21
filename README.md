

```markdown
# Search in Random Array

This is a simple C++ console application that generates an array of random integers and allows the user to search for a number within the array.

## Features

- Fills an array with random numbers between 1 and 100  
- Prints the array contents  
- Asks the user for a number to search for  
- Searches for the number and shows its index and order in the array  
- Displays a message if the number is not found  

## How It Works

1. The program prompts the user to enter the number of elements.  
2. It generates random numbers and fills the array.  
3. It prints all the numbers.  
4. The user is asked to input a number to search for.  
5. If the number exists, its position and order are displayed.  
6. Otherwise, a "not found" message is shown.  

## Example Output

```
Enter number of elements:
5

Array 1 elements:
23 78 12 45 9

Please enter a number to search for?
12

Number you are looking for is: 12  
The number found at position: 2  
The number found its order  : 3
```

## Requirements

- C++ compiler (e.g., g++, MSVC, clang)  
- Basic knowledge of compiling and running C++ programs  

## How to Compile

Using g++:

```bash
g++ -o search_array main.cpp
./search_array
```

