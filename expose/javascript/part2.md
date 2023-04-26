1. it will print 3, because i is declared with var, so its scope is the entire function. i = 3 after the for loop because prices.length = 3
2. it will print 150, because discountedPrice is declared with var, so its scope is the entire function. the last time discountedPrice is updated, it is equal to prices[2] * 0.5, which is 150
3. it will print 150, because finalPrice is declared with var, so its scope is the entire function. the last time finalPrice is updated, it is equal to Math.round(150 * 100)/100, which is 150
4. it will return [50, 100, 150]. the function takes each price and multiplies it by (1 - discount) and rounds to 2 decimal places. 
5. error, because the scope of i is in the for loop, and line 12 is outside the for loop
6. error, because the scope of discountedPrice is in the for loop, and line 13 is outside the for loop
7. it will print 150, because the scope of finalPrice is the entire function
8. it will return [50, 100, 150], same reason as 4
9. error, same as question 5
10. it will print 3, since prices.length is 3
11. it will return [50, 100, 150], same reason as 8
12.
    1. student.name
    2. student["Grad Year"]
    3. student.greeting()
    4. student["Favorite Teacher"].name
    5. student.courseLoad[0]
13.
    1. "32", 2 -> "2"
    2. 1, "3" -> 3
    3. 3, null -> 0
    4. "3null", null -> "null"
    5. 4, true -> 1
    6. 0, false -> 0 and null -> 0
    7. "3undefined", undefined -> "undefined"
    8. NaN, subtract only works on numbers, and undefined can't be turned into a number
14.
    1. true, "2" -> 2
    2. false, in string comparison, "2" > "1"
    3. true, "2" -> 2
    4. false, 2 and "2" are different types
    5. false, true -> 1
    6. true, Boolean(2) = true
15. == will try to convert the values into the same type before checking for equality, === will not do any type conversion, so it will only return true if the 2 values have the same type and value
16. check .js file
17. [2, 4, 6]. the function goes through each array element and calls callback on it, returning a new array. callback doubles the number, so the new array has all of the elements from [1, 2, 3] but doubled
18. check .js file
19. prints 1, 4, and 3, then prints 2 after 1 second
