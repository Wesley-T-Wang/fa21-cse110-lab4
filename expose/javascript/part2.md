1. 3 since var i is defined in discountPrices it prints the value that the function finished with

2. 150 because the item at the last index of the loop/array is 300 which gets its 50 percent discount applied to end up at 150 and the variable is declared within the scope of the function

3. 150 because last item in the array is set to 150 after the loop and that is what discountedPrice is set to and then final price just gets a multiplied, divided, and rounded version of that number which just ends up as 150

4. [50, 100, 150].  applying a 50 percent decrease aka diving by 2 gets us to these values. it sets each item in the array to their 50 percent discount prices.

5. error because let defines it in the scope of the for loop and the console log statement is outside of the loop

6. error because the let keyword only keeps discountedPrice inside the scope of the for loop and the console log is outside of the loop

7. 150 final price is defined in the beginning of the function which is in the same scope as the console log which appears later in the function. neither are in their own code block or for loop so they are in the same scope.

8. [50, 100, 150] because the discounted is declared at the beginning and is in the same scope as in the console log statement so it has access and is modified within the for loop that sets these values as mentioned above.

9. error since i is declared with let so the i variable can only be accessed within the for loop.

10. 3 since the length const variable is declared at the beginning of the function so it is in the same code block as the console log statement and the length is originally 3.

11. [50, 100, 150] same output as mentioned above. making discounted a const doesn't change anything because it is an array and you can alter the contents as long as you don't reassign it to a new array

12. 
        a  `student['name'];`

        b  `student['Grad Year'];`

        c  `student['greeting']();`

        d  `student['favorite teacher']['name'];`

        e  `student['courseLoad'][0]`

13. 
        a  32 concatenating a 3 and a 2 sticks them together side by side

        b  1 you cannot substract strings so it is converted to a number 3 to compute 1 

        c  3 because the null is just treated as 0

        d  4 adding number value of true is 1 so adding 1 to 3 gets 4

        e  NaN since undefined does not get converted to 0 like null does and it doesn't know what to do with it an NaN is returned

14. 
        a  true 2 is converted to a number which is larger than 1 mathematically

        b  true 2 and 12 are converted to numbers and 2 is in fact smaller than 12

        c  true 2 is converted to a number and 2 and 2 have the same value

        d  false the triple equals checks if they are the same type and since one is a number and the other is a string it is false

        e  false, true is converted to a 1 not a 2 and 1 does not equal 2

        f  true the Boolean() returns true if the number is not 0 and the number 2 is not 0 and since it returns a boolean type they are the same type so === holds

15. == checks same value === also checks if they are declared as the same type

16. see file

17. [2,4,6]. we pass [1,2,3] in and the callback function doSomething which multiplies the number by 2. the modify array function creates an empty array and then loops through and pushes the result of the callback function on each element of the array and set it to the newarr which gives 2 4 6.

18. see file

19. output should be 

        1

        4

        3

        2