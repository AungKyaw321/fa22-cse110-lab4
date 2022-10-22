1. Line 12 will return the total iterations which is 3 because i variable is declared as a var and var has no block scope so even though it was declared in the for block I can still call the variable outside of that block.
2. Line 13 will return the discountedPrice variable as 150 because discountedPrice variable is declared as a var and var has no block scope so even though it was declared in the for block I can still call the variable outside of that block.
3. Line 14 will return the finalPrice variable as 150 because discountedPrice variable is declared as a var and var has no block scope but finalPrice was declared in the function block so I can still call it in the console.log which is also in the function block.
4. This function will return the discounted array since I ran console.log on line 19 and it returned the array. It returns that because discounted is a var variable adn because var doesn't have a block scope it returns the discounted array.
5. Line 12 will return an error because the let variable cares about block scope and since i is declared in the for loop block the when console.log calls it outside the for block it is undefined.
6. Line 13 will return an error because the let variable cares about block scope and since discountedPrice is declared in the for loop block the when console.log calls it outside the for block it is undefined.
7. Line 14 will return finalPrice variable as 150 because let datatype cares about block scope and since finalPrice is declared in the function block and console.log calls finalPrice variable in the function block it returns the value of finalPrice.
8. This function will return the discounted array because let datatype cares about block scope and since discounted is declared in the function block and console.log calls discounted array in the function block it returns the value of discounted.
9. At line 11 it returns an error because i is a variable with a let datatype which means that it cares about block scope and because it was declared in the for loop and we are calling console outside the for loop i is undefined.
10. At line 12 it returns 3 because length is a variable with const datatype and because length wasn't updated at line 12 it just returns the length of the prices array.
11. This function returns the discounted array because even though discounted is a const datatype push variables into the array it just means that every value in each index of the array will have a const datatype.
12. 
    A. student.name
    B. student["Grad Year"]
    C. student.greeting();
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13.  <br>
    A. 32 because 3 is a string in this case so when we add it it concatenates them instead resulting in '3' + 2 being 32.
    B. 1 because for substraction it converts all operands to numbers so when we do '2' - 1 it returns 1
    C. 3 because when we add null's numeric value is 0 so when we do the operation 3 + null then we get 3
    D. 3null because since 3 is a string addition operator treats both 3 and null as strings and concatenates them
    E. 4 because true's integer value is 1 so when we add it to 3 it returns 4 
    F. 0 because both false's and null's integer values are 0 so when we do false + null we are adding 0 + 0 which is just 0 
    G. 3undefined  because 3 is a string addition treats the both operands as strings and concatenates them which results in 3undefined
    H. NaN because for subtraction it converts all operands to numbers so the string 3 is converted to a number 3 but undefined doesn't have a number so NaN gets returned. 
14.  <br>
    A. true because the string 2 becomes a number 2 and so when we compare '2' > 1 it returns true since 2 is greater than 1 
    B. false because alphabetically 1 is less than 2 so when we compare '2' < '12' it will mean that 2 is greater than 12 thus returning false
    C. true because the string 2 gets converted to number so wehn we compare 2 with '2' then it is true 
    D. false because === operator compares both the values and the datatypes as well so because 2 is equals to 2 the number, 2 a number is not equals to 2 a string so it returns false
    E. false because the numeric value of true is 1 so when we do the comparison it gets converted to 1 so the statement 2 == true is false
    F. true because === compares data types and because both true and Boolean(2) are booleans it is true. Then when we compare operands we can see that Boolean(2) just means true so true === Boolean(2) is the same as true === true which would return true.
15. The difference between == and === is that while == does the type comparison of the operands before comparing them, === compares the values and the data types of the operands.
16. The result is an array [2,4,6] because the modifyArray function is given an array which is [1,2,3] and a callback function called doSomething which will be executed when called in the modifyArray function. Then we do the for loop and in the for loop we populate our newArr array by calling on the function and giving it each integer of the array so for example in the first iteration we would call the doSomething function and give it an input of the array[0] which is 1 then doSomething would multiply it by 2 and return that and then that result will be pushed into the newArr and we do that until we get to the array.length so we end up returning the newArr which now has [2,4,6].
17. 1,4,3,2