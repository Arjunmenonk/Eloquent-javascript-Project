# Project Title

A Programming Language

Getting Started These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites

Visual studio code

## How to Execute

1.  One.js(Sum of Range)

     Create a function with name as Range which accepts 3 parameters (start, end, step = start < end ? 1 : -1) 
  
  Inside function declare the array as empty (i.e) let array=[];
  
  Check the condition whether value of step is > 0 or not, if > then 
  
  for (let i = start; i <= end; i += step) 
      
  array.push(i);
 
 Create a loop as
 
 for (let i = start; i >= end; i += step) array.push(i);
 
 return the array outside.
    
    
  Create another function with name as sum and accepts single parameter   (i.e) array
  
  Inside the function declare a variable total and initialize its value to 0.
  
  Then create a loop as 
  
  for (let value of array) 
      
  total += value;
  
  This loop will allow the variable to add the values and store.
     
  Finally return the total
     
  Outside the function print the range values and total sum of the range.
     
2. Two.js(Reversing an Array)

  Create a function with name as ReverseArray(array)
  
  Inside function initialize value of Outpus as[]
  
  Then create a for loop, for (let i = array.length - 1; i >= 0; i--)
  
  Inside loop push the array list by value of i.
  
  Return the output outside the loop.
  
  Again create a function with name reverseArrayInPlace(array)
  
  Inside function create a loop as
  
  or (let i = 0; i < Math.floor(array.length / 2); i++)
  
  Inside loop 
  
  Swapping is done
  
  let old= array[i]
  
  array[i] = array[array.length - 1 - i];
     
  array[array.length - 1 - i] = old;
  
  Return the array outside the loop.
  
  utside the function print the reverse array,specify the array values and print reverse array in place as arrayvalue.
  
3. Three.js(A List)

4.Four.js(Chessboard)

Once the code is typed in Visual studio code, Save the file with .js extension

In the left tab,the file name will be displayed, right click the file and click "Open in Terminal

Type node and the filename.js to execute

## Authors

Marijn Haverbeke

## License 

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments 

* Hat tip to anyone whose code was used 

* Inspiration 

* etc
