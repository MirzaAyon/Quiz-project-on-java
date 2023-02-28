## Quiz-project-on-java


### Project scenario
#### Create a quiz program that will take questions, option and answer from admin user and save it to the question bank. Then if any user want to give the quiz, random 5 questions will be shown to the user from the question bank.

##### Program output:

Add Quiz
Start Quiz
if user select option 1, then system will tell user to input a question, 4 options and correct ans to save data in a quiz bank. The quiz bank will be a json file. For an example,

System>Please add a ques here: User>
#### Which testing is done by developer?
System>Input options. Option 
- a: User> Unit Testing Option 
- b:User> Integration Testing Option 
- c:User> Sanity Testing Option 
- d:User> Regression Testing System> <br> Please input the correct ans User> a <br> System: Quiz saved at the database. Do you want to add more? (y/n) <br>
if user press y, then the previous scenario will happen again otherwise the program will be closed.

If user select option 2, then,<br>
System> You will be asked 5 questions, each questions has 1 marks

#### Which testing is done by developer? 
a. Unit Testing
b. Integration Testing
c. Sanity Testing
d. Regression Testing
User> a
System> Correct!
else not correct,
System: Not correct
##### Finally 5 different random questions will appear from your question database. At least add 15 questions from any category from testing.
Result: You got [correct_marks] out of 5

#### JSON Format:
[ <br>
{ <br>
"Question":"Which testing is done by developer?", <br>
"option a":"Unit Testing", <br>
"Option b":"Integration Testing", <br>
"Sanity Testing":"Sanity Testing", <br>
"Option d":"Regression Testing",<br>
"answer":"a"<br>
},<br>
{<br>
"Question":"Which is functional testing?", <br>
"option a":"Load Testing",<br>
"Option b":"Security Testing", <br>
"Sanity Testing":"Gorilla Testing", <br>
"Option d":"Benchmark Testing", <br>
"answer":"c" <br>
}<br>
]

### Project video



https://user-images.githubusercontent.com/68238652/221851398-a398b157-bffd-4ca5-9dd2-825b2cd8a9ad.mp4

