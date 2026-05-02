# Final Exam
A little ncurses program that lends itself to a class github activity
The exam ( exam2.c ) is a C program that uses ncurses.

## To compile
```
apt install libncurses-dev build-essential
make
```
## To run
After compiling, you'll have an executable `finalexam`. Run this like
```
./finalexam
```
and then you can take the exam!


## Student TODO
The class will help make the final exam by creating questions.
Questions can be submitted via pull request. 
If I review your questions and they're good, I'll accept the PR and they'll become part of the
final.

Then the students must provide some questions in the questions directory.
Each question should be a file called `student_name.txt`
And the file format is like
```
QUESTION
CHOICE1
CHOICE2
CHOICE3
CHOICE4
ANSWER_INDEX
```

Answer index should be a single char from 1-4
