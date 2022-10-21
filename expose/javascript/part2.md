1. Line 12 will return the total iterations which is 3 because i variable is declared as a var and var has no block scope so even though it was declared in the for block I can still call the variable outside of that block.
2. Line 13 will return the discountedPrice variable as 150 because discountedPrice variable is declared as a var and var has no block scope so even though it was declared in the for block I can still call the variable outside of that block.
3. Line 14 will return the finalPrice variable as 150 because discountedPrice variable is declared as a var and var has no block scope but finalPrice was declared in the function block so I can still call it in the console.log which is also in the function block.
4. This function will return the discounted array since I ran console.log on line 19 and it returned the array. It returns that because discounted is a var variable adn because var doesn't have a block scope it returns the discounted array.
5. Line 12 will return an error because the let variable cares about block scope and since i is declared in the for loop block the when console.log calls it outside the for block it is undefined.
6. Line 13 will return an error because the let variable cares about block scope and since discountedPrice is declared in the for loop block the when console.log calls it outside the for block it is undefined.
7. Line 14 will return finalPrice variable as 150 because let datatype cares about block scope and since finalPrice is declared in the function block and console.log calls finalPrice variable in the function block it returns the value of finalPrice.
8. This function will return the discounted array because let datatype cares about block scope and since discounted is declared in the function block and console.log calls discounted array in the function block it returns the value of discounted.
9. s
10. s
11. s
12. s
13. explain!
    A. 32
    B. 1
    C. 3
    D. 3null
    E. 4 because true's integer value is 1 so when we add it to 3 it returns 4
    F. 0
    G. 3undefined
    H. NaN
14. explain!
    A. true
    B. false
    C. true
    D. false
    E. false
    F. true
15. diff between == and ===