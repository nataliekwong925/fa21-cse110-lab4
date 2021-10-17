1. Line 12 will print the value of i. At this point, the value of i is 3 because i starts at 0 and increments until i is the length of the prices list, which has a length of 3.
2. Line 13 will print the latest value that was assigned to discountedPrice, which will be 150 since 300 is the last value in discountPrices and it's multiplied by 0.5 (since 1-discount = 0.5)
3. Line 14 will print the latest value that was assigned to finalPrice, which is 150 because the latest value of discountedPrice was 150, and finalPrice is equal to the rounded value of 150*100 and then divided by 100.
4. The function will return the list discounted, which is equal to [50, 100, 150]. This is because the function discountPrices takes the list [100, 200, 300] and returns a list where each of these values are multiplied by 0.5 and then rounded if necessary.
5. The code will cause an error because the variable i is trying to be accessed outside its block scope, and so it is not defined
6. The code will cause an error because the variable discountedPrice is trying to be accessed outside its block scope, and so it is not defined
7. Line 14 will print the latest value of finalPrice, which is 150 since finalPrice is half the value of discountedPrice. It won't cause an error because it's accessing finalPrice within the block scope it was defined in.
8. The function will return [50, 100, 150] for the same reason it returned this in #4. The code will not cause an error because it's accessing discounted within the block scope it was defined in.
9. The code will cause an error because he variable i is trying to be accessed outside its block scope, and so it is not defined
10. Line 12 will print the value of the variable length, and so it will print 3 because the length of prices is 3.
11. The function will return [50, 100, 150] for the same reason it returned this in #4. The code will not cause an error although discounted is a constant variable, it is okay to push new elements into the list because this action does not reassign the variable's value.
12.  a. student.name
     b. student['Grad Year']
     c. student.greeting()
     d. student['Favorite Teacher'].name
     e. student.courseLoad[0]
13. a. '32' since '2' is converted to a string
    b. 1 since '3' is converted to a number
    c. 3 since null is converted to 0
    d. '3null' since null is converted to a string
    e. 4 since true is converted to 1
    f. 0 since false and null are both converted to 0
    g. '3undefined' since undefined is converted to a string
    h. NaN since undefined is converted to a number (which is NaN)
14. a. true since '2' is converted to a number
    b. false since '2' and '12' are both strings and '12' is before '2'
    c. true since '2' is converted to a number
    d. false since 2 and '2' are different types
    e. false since true is converted to 1
    f.true since Boolean(2) is true because 2 is not an empty value
15. The regular equality check "==" can convert values of different types in order to compare them. The strict equality check "===" does not use type conversion and returns false if the values are different types.
17. The array [2, 4, 6] will be returned from the function being called. The for loop on Line 3 iterates through each element in [1, 2, 3], and multiplies each element by 2 through the doSomething function before adding it to the newArr array which is ultimately what is returned from the function.
19. The code outputs 1 then 4 then 3, and then waits 1 second before printing 2. So it prints out 1432, with each number on its own line.