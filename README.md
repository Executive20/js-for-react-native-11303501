# STUDENT ID - 11303501

TASK ONE

Explanation:
processArray Function:

The function takes an array of numbers as its argument.
It uses the map method to iterate over each element in the array and applies the following logic:
If the number is even (checked using num % 2 === 0), it squares the number (num * num).
If the number is odd, it triples the number (num * 3).
The function returns a new array with the transformed numbers.
Example Usage:

An example array of numbers (numbers) is defined.
The processArray function is called with this array.
The original and processed arrays are logged to the console for demonstration purposes.

TASK TWO

Explanation:
processArray Function:

This function takes an array of numbers and returns a new array where each even number is squared and each odd number is tripled.
The map method is used to create the new array based on the conditions.
formatArrayStrings Function:

This function takes two arrays as arguments: one array of strings and another array of numbers.
It first checks if the lengths of the two arrays are the same. If not, it throws an error.
It then uses the map method to iterate over the strings array. For each string, it checks the corresponding number in the numbers array:
If the number is even, the string is converted to uppercase using str.toUpperCase().
If the number is odd, the string is converted to lowercase using str.toLowerCase().
The function returns the modified array of strings.
Example Usage:

An array of strings (strings) and an array of numbers (numbers) are defined.
The processArray function processes the numbers array.
The formatArrayStrings function is then called with the strings array and the processed numbers array.
The results are logged to the console.

TASK THREE

Explanation:
createUserProfiles Function:

Takes two arguments: originalNames (an array of original names) and modifiedNames (an array of modified names).
Checks if the lengths of the two arrays are the same. If not, it throws an error.
Uses the map method to iterate over the originalNames array. For each name, it creates an object with the following properties:
id: an auto-incremented ID starting from 1.
originalName: the original name from the originalNames array.
modifiedName: the corresponding modified name from the modifiedNames array.
Returns an array of these objects.
Example Usage:

Defines an example array of original names (originalNames).
Defines an example array of modified names (modifiedNames), which should come from the formatArrayStrings function (as explained in Task 2).
Calls the createUserProfiles function with these arrays.
Logs the resulting array of user profiles to the console.
