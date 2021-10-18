1. "values added: 20"  add is true so it goes into the if statement and adds the two numbers and stores it into result and appends it to the string "values added:"

2. "final result: 20" there is an else but this console.log sits outside of it so it occurs after the if statement, which adds 10 and 10 to result which then holds 20 and appends it to the string

3. "values added: 20"  add is true so it goes into the if statement and adds the two numbers and stores it into result and appends it to the string "values added:"

4. error because use of let keyword defines variable only in scope of the if statement so the print statement call of the variable result does not exist.

5. error because you cannot reassign variable declared with const keyword

6. error on line 9 because of const reassignment error. line 13 will not get to execute