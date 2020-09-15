# Reading 02

## Java Loops:

1. For Loops:
- The condition for a For Loop is always evaluated before each iteraiton of the loop
- The condition contains initialization, boolean expression to be evaluated and the step, all of which are optional (ex: for( ; ; ){ } // Creates an infinite loop)

2. While Loops:
- This loop repeats statement or code block as long as the conditional boolean expression is true
- If a condition is false, it is possible for the loop to not run even once

3. Do While loops:
- Do-while loops are almost identical to while loops except that the condition evaluation happens AFTER the first iteration of the loop
- The kep difference between while-loops and do-while loops is that do-while loops are always run at least once

## Java Imports:

### What are Java Imports?
- these are prepackaged classes that we can use in our projects
- in order to use them, they need to be imported first

Example:
````
import java.util.Calendar;
import java.util.Date;
````

These import statements at the top of the file allow us to use the calendar and date utilities in our code.
Import statement can be added with this shortcut using Sprint STS IDE:
1. Classes that haven't been imported cna be automatically detected with a shortcut key
2. Press Crtl-Shift-O (the letter, not zero)
3. Spring will ask you if you want to import the utilities you used on your code
4. Select theones you want to import and they will be added to the top of your class file

