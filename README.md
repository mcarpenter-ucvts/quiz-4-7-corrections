# Quiz 4

02. Using the prompt function will make a pop-up box appear while also prompting the user to input a response. Using the alert function is correct because we only want a pop-box with the message
03. Using console.log('x') will print "x" to the console. The first choice is correct because you want to print the values stored in x and y to the console.
07. Undefined is correct because there are two names for "nothing", Undefined and null. Object is correct because
08. "" is a falsey value because it is a string with a length of 0. Undefined is a falsey value because when used it returns as false.
09. Answer 1 is correct because x needs to be
10. The fourth answer is correct because when using the math object, it is PI not pi. Using "pi" is not correct because the correct property name is "PI".

11.
```
function payingTheBill() {
  let guests;
  let name;
  let bill;
  let y;

  name = prompt("What restaurant are you dining at?");
  guests = prompt("How many guests are dining with you?");
  bill = prompt("What is the total cost of the dinner?");

  guests = parseInt(guests);
  bill = parseInt(bill);

  y = (bill / (guests + 1)).toFixed(2);


  alert("Dinner at " + name + " doesn't come cheap! Everyone owes $" + y + "!");
}
```
```
function classScheduling() {
  let students;
  let course;
  let capacity;
  var x;
  var y;
  var z;

  students = prompt("Enter the number of students in the class (the class of 2021)");
  course = prompt("Enter a course being taught at the school");
  capacity = prompt("Enter the maximum capacity of the selected course");

  x = Math.ceil(students / capacity);
  y = course;
  z = students;

  console.log("" + x + " sections of " + y + " are required to satisfy the demand of " + z + " students.");
}
```
## Quiz 5

01. This is the correct answer because === is equal to and compares both value and data type; and !== is not equal to and compares both value and data type. The first statment is asking for a condition that would make x and y have equivalent values and data types and the second statement asks for a condtion that would make x and y have different values or different data types. Therefore, the conditions above are the right answers that will satisfy the requirements.
03. the "!==" and "===" are correct because it performs a strict equality test that means both data and type must match. "!=" is correct because means "not equal to" which is comparing two values. "==" is correct because it means "equal to" and it compares two values.
04. "===", "==", "!==", and "!=" are not correct because they are not logical operators. They are valid relational operators.
07. The second answer is correct because it is the simplest way to achieve the goal. It simply uses relational operators instead of both relational and logical. Using logical operators add more work and confusion. It is simply not necessary to use logical operators to achieve the goal.
08. The first answer is correct because the break statements are imperative to switch statements. If the break statements are not there the statement will execute code for multiple cases. We need the break so that the code found in the particular case is executed and only that code.
10. [insert answer]
11. [insert answer]
12. [insert answer]
15. I got this question wrong because I forgot how loops were executed. The correct answer would have been in the order of: setup, expression, loop body, update, and return to step 2. This is the order of how the components are executed.

### Quiz 6

01. [insert answer]
03. Console.log is incorrect because console.log does not necessarily return a value yet prints whatever you tell it to print to the console. However, the prompt function returns a value
04. The first answer is correct because it gives a better description of what the function is going to do. Adding the parameters gives the user a better understanding of what is going to happen.
05. "They will both run indefinitely" is correct because the code will continue to run without a break statement. A break statement is needed to eventually stop the code from running when the desired result is reached.
06. I got this question wrong because for this question, I was to consider a given function and select what could be determined based on the info provided. I did not select the choice which stated "The function is not designed to accept any parameters." This is also a correct answer as there was nothing between the parenthesis which determines what the parameters are.
07. "The extra arguments will be ignored" is the correct answer because you can put in how many ever parameters. Even if you do not end up using some of the parameters, as long as now value is assigned to them they will be ignored.
08. This is the correct revision that will make the function accept as parameters the values being divided. The answer I selected just named variables and prompted the user to enter any two two numbers, in which a divided by b was returned.
09. [insert answer]
10. The first answer is correct because the name of the function is mystery. The third answer is correct because the function is not designed to accept parameters because no parameters are given to the function.
11. The last answer is correct because const and let are block scope.
13. "A ReferenceError will occur on line 10" is the correct answer because the variable y cannot be logged to the console because it is not a global scope variable. It is a block scope variable that can only be referenced inside that block of code or if statement.
15. I got this question wrong because I said the following code snippet would only print "4" to the console. However, "undefined" would also be printed to the console because it meets the parameters.

#### Quiz 7

09. I got this question incorrect because I answered with false instead of true. The correct answer is true the code segment was asking to return numbers greater than 100 and less than 999. The values that were returned did meet these parameters
13. [insert answer]
14.  [insert answer]
15. Answer 4 is also correct because you are assigning the values to empty spots in the array. You are allowed to just assign a value to an index number by using nameOfIndex[anyNumberStartingAt0]
