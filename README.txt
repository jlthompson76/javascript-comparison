JavaScript Conditional Statements: Comparing Values

This JavaScript Comparison Page project will give you more practice in JS.

1. Create an HTML file.  Title it JavaScript Comparison Page or similar.
2. Create a JavaScript file. Link it to your HTML file.
3. Declare a variable x.  Set it equal to 4.
4. Add an if statement that alerts one of the following:
    * "The value is less than 10" (if x is smaller than 10)
    * "The value is greater than 10" (if x is larger)
    * "The value equals 10" (if x = 10)
5. Load your page in a browser to test
6. Change x to be greater than 10 and test again.  Test a few more times with different values.
7. BONUS: Ask the user for a value of x using prompt()

NOTE: the prompt() dialog returns the user's input as a string, not a number (read more ).  Therefore you will have to convert the user's input from a string to a number using the Number() function.  For example, your code might include this line: 
userInput = Number(userInput);

Or you might choose to convert the value inside your conditional statement, like this:

if (Number(userInput) = 10) {
do something
}