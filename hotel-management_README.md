**Explanation :**
The Hotel Management System we will build will be a simple console-based application that allows users to check-ins, check-outs and view the availability of rooms. We have used single class in program to make it as easy as possible. Main class consists of main method, switch case and other required methods for check-ins and check-outs. For rooms 2D array has been used to store room number and guest name in that room. A 2D array in Java is a multidimensional array that represents a table or matrix of values. It is an array of arrays, where each element of the array is itself an array. This array has been initialized as room numbers from 1 to 10 and guest name as empty which will get updated as per check-ins of guests. Menu will provide four options as – check-in, check-out, view occupancy and exit. Scanner class used for taking input from user through keyboard. For check-in user needs to provide room number. Given room number will get checked as it is valid or not and if that room is empty then system will ask for guest name. Check-out process is based on room number. Again, the conditions will get checked for room validation. If room number is valid then assign that room as ‘empty’.  For viewing the occupancy simple for loop to retrieve data of 2D array has been used. As array starts from index 0, we need to minus one from provided input of room number. Checking conditions properly for each operation is important to make this system transparent. Switch case shows the menu options and each case of switch case, the appropriate method has been called to perform the required operations. Just some basic knowledge of arrays and for loops and you are ready to build your own hotel management system. Happy Coding!