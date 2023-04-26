# DSCL-EXP-Singly-Linked-LIST
Description: This C program searches for a specific integer key in an integer array using a linear search algorithm. If the key is found in the array, the program returns the index of the element where the key is found, otherwise, it returns a message that the element is not found.

Algorithm:

Initialize an integer flag to 0. Declare an integer array 'arr' and initialize its values. Declare an integer key and initialize it to 10. Initialize an integer index to store the index of the key in the array. Use a for loop to iterate over each element of the array from 0 to 5. Within the loop, check if the current element is equal to the key. If it is, set the flag to 1 and store the index of the element in the index variable. If the flag is set to 1, print the message "Element is found at index+1" where index is the variable storing the index of the key in the array. If the flag is still 0 after the loop, print the message "Element not found".

Output: The output of this program is "Element is found at 5" as the key 10 is found at the 5th index of the array.
