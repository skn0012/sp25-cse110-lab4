## Part 2

# Questions

1. 3 is printed because there are only 3 elements in 'prices'.
2. 150 is printed because the last value for discountedPrice is 150.
3. 150 is printed because the last value for finalPrice is 150.
4. The function returns [50, 100, 150]. For 100, discountedPrice = 50, finalPrice = (50 * 100) / 100 = 50. For 200, discountedPrice = 100, finalPrice = (100 * 100) / 100 = 100. For 300, discountedPrice = 150, finalPrice = (150 * 100) / 100 = 150. Thus, the function returns [50, 100, 150].
5. The code returns an error because i is defined using 'let' in the for loop and thus, is only defined in the for loop so the program cannot find i.
6. The code returns an error because discountedPrice is defined using 'let' in the for loop and thus, is only defined in the for loop so the program cannot find discountedPrice.
7. 150 is printed because the last value for finalPrice is 150 and is defined for the whole function.
8. The function returns [50, 100, 150]. For 100, discountedPrice = 50, finalPrice = (50 * 100) / 100 = 50. For 200, discountedPrice = 100, finalPrice = (100 * 100) / 100 = 100. For 300, discountedPrice = 150, finalPrice = (150 * 100) / 100 = 150. Thus, the function returns [50, 100, 150]. The use of 'let' to define variables does not affect the calculation of the final array (discounted).
9. The code returns an error because i is defined using 'let' in the for loop and thus, is only defined in the for loop so the program cannot find i.
10. 3 is printed because there are only 3 elements in 'prices' and there is not an attempt to assign a new element to length.
11. The function returns [50, 100, 150]. For 100, discountedPrice = 50. For 200, discountedPrice = 100. For 300, discountedPrice = 150, (150 * 100) / 100 = 150. Thus, the function returns [50, 100, 150]. The use of 'let' and 'const' to define variables does not affect the calculation of the final array (discounted).
12. - student.name
    - student['Grad Year']
    - student.greeting()
    - student['Favorite Teacher'].name
    - student.courseLoad[0]
13. - '3' + 2 = '32'. This happens since when adding a string and a number, the number is turned into a string and concatenates them.
    - '3' - 2 = 1.  This happens since subtraction turns both sides into a number.
    - 3 + null = 3. This happens since null is treated as 0.
    - '3' + null = This happens since addition causes string concatenation.
    - true + 3 = 4. This happens since true is treated as 1.
    - false + null = 0. This happens since false and null are treated as 0.
    - '3' + undefined = '3undefined'. This happens since addition causes string concatenation.
    - '3' - undefined = NaN. This happens since subtraction turns both sides into a number and you cannot subtract by undefined.
14. - '2' > 1 = true. This happens since 2 is converted into a number and 2 > 1 is true.
    - '2' < '12' = false. This happens since JS compares the left most character ('2' < '1' = false).
    - 2 == '2' = true. This happens since == converts types so 2 == 2 is true.
    - 2 === '2' = false. This happens since === checks values and types, thus 2 is not the same as '2'.
    - true == 2 = false. This happens since true becomes 1 and 1 does not equal to 2.
    - true === Boolean(2) = true. This happens since Boolean(2) = true, thus, true === true.
15. == allows type conversion while === requires both value and type to match.
16. Done in part2-question16.js.
17. The result will be [2,4,6] because the modifyArray function takes in the [1,2,3] array and puts it in 'array' then doubles each element in the array.
18. Done in part2-question18.js.
19. - 1
    - 3
    - 2
