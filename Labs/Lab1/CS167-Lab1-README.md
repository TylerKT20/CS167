# Lab 1

## Student information

* Full name: Tyler Tseng
* E-mail: ttsen017@ucr.edu
* UCR NetID: ttsen017
* Student ID: 862258953

## Answers

- ***(Q1) What is the name of the directory that `mvn archectype:generate` command creates?***
ttsen017_lab1

- ***(Q2) What do you see at the console output when you run the `java` command?***
Hello World!

- ***(Q3) Which of the following is the right way to call the `IsEven` function?***

    - IsEven(5)
    - IsEven.apply(5)
    - new IsEven().apply(5) <-This

- ***(Q4) Did the program compile after you added the `base=0` line?***
No

- ***(Q5) If your answer to (Q4) is No, what is the error message you get?***
"error: local variables referenced from a lambda expression must be final or effectively final Function<Integer, Boolean> divisibleByBase = integer -> integer % base == 0;"
