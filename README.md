# info3-lab07-testing

## 1. Getting started
<b>Give the equivalence classes for testing a method that determines the absolute value of an integer using the closed-box methodology. Don’t peek at the code yet! Now check out absolute.py in the repository and give test cases covering each branch for a open-box test. Define suitable test cases based on your analysis.</b>

A method that returns the absolute value of an Integer needs to remove the '-' identifier of that Integer, if there is one. This results in two execution paths and the following equivalence classes:
```
]-infinite, 0[ , [0, infinite[
```

## 2. Closed-box test
<b>Look at the grading scale at the bottom of the page (Which is not the grading scale for this course). Give the equivalence classes for a program that loops until a “-1” is entered, asking for the number of points on this scale, prints the appropriate letter grade (A-F), and then prints the average number of points when “-1” has been entered. Develop one test case for each equivalence class. Test your test cases with GradingScale.class - this is a java programm. No fair decompiling the class! Report on the results. Did you find any errors?</b>

## 3. Open-box test / path coverage

<b>Examine the code for TaxTime.py. Draw a code graph of the main class! How many independent paths are there? What are the conditions that cause each of the paths to be taken? Draw up a table giving you an overview of the conditions. Give test cases that exercise each path. Are there any errors in the program (besides the size of the tax bite)?</b>
4. Reflection Reflect on the differences of the two strategies to find test cases.
