# Find-Smallest-element-in-an-array-using-Python

Find smallest element in an array using Python

In this section we will learn how to find smallest element in an array using python programming language which is the scripting language. If we want to find smallest element from the array enter by the user so we have to compare one element to other until we get the desired element and print it.

Program to find Smallest element in an array using Python
To find the minimum element in the given list or array we can use different approaches to get the minimum element. Here, in this page we will discuss the following algorithms to find the minimum/smallest element.

Method 1 : Using Iteration
Method 2 : Using sorting
Method 3 : Using min() function
Method 1 :
Take a variable say mini to store the minimum element of the array.
Set mini = arr[0]
Run a loop over the array
Check if(arr[i]<mini) then set mini = arr[i]
After complete iteration print mini.
Method 1 : Python code
Run
arr = [10, 89, 9, 56, 4, 80, 8]
mini = arr[0]

for i in range(len(arr)):
  if arr[i] < mini:
     mini = arr[i]

print (mini)
Output :
4
Related Pages
Given a string s, remove all its adjacent duplicate characters recursively
 
Find Largest element in an array
 
Find Smallest Element in an Array

Find the Smallest and largest element in an array

Find Second Smallest Element in an Array

Calculate the sum of elements in an array 

Method 2 :
Sort the array using sort() function.
Print the first element of the array.
Smallest element using python
Method 2 : Python Code :
Run
arr = [10, 89, 9, 56, 4, 80, 8]
arr.sort()

print (arr[0])
Output :
4
Method 3 :
Using min() inbuilt function.

Declare an array.
Print the min(arr)
Output :
4
Method 3 : Python code
Run
arr = [10, 89, 9, 56, 4, 80, 8]
print (min(arr))
