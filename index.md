Hi! This is lab report 5, we will explore grading script this time.
>Part 1 the grade.sh code


```
rm -rf student-submission 1> out.txt 2> out-err.txt
git clone $1 student-submission 1> git.txt 2> git-err.txt
score=0


cd student-submission
if [ -f ListExamples.java ]
then
    echo "ListExamples.java file found"
else
    echo "ListExamples.java file not found"
    echo " You have earned "$score " out of 3"
    exit 1
fi

cd ..
cp -r TestListExamples.java student-submission/
cd student-submission
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar ListExamples.java

if [ $? -eq 00 ]
then
    echo "Successfully compile all the files"
else
    echo "There is some compile error"
    echo " You have earned "$score " out of 3"
    exit 1
fi

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

if [ $? -eq 00 ]
then
    GRADE=3
    echo "Cong! You passed all tests!"
    echo " You have earned "$score " out of 3"
else
    echo "Try again, some tests not passed"
    echo " You have earned "$score " out of 3"
fi
   
```
>Part2 3 submissions loaded on the browser


![Image](image51.jpg)
![Image](image52.jpg)
![Image](image53.jpg)


>Part3 trace the script with compile error

https://github.com/ucsd-cse15l-f22/list-methods-compile-error this is the student submission

```
rm -rf student-submission 1> out.txt 2> out-err.txt
```
This line is for removing the former student submission file and save the standard output to out.txt and standard error to out-err.txt.
Right now, both files are empty.

```
git clone $1 student-submission 1> git.txt 2> git-err.txt
```
Then, we try to cloning the student submission, which is https://github.com/ucsd-cse15l-f22/list-methods-compile-error in this case. the standard output is aved into git.txt and the standard error is saved to git-err.txt

```
GRADE=0 
```
This initializes the grade and return the grade to zero.

For the first if statement, we are checking if ListExamples.java exists and been found. There is no standard error and the standard output is
```
ListExamples.java file found
```
the return code is zero.

```
cd..
```
This return to the home directory and has no standard output or error, the return code is zero.
```
cp -r TestListExamples.java student-submission/
```
This copies TestListExamples.java and everything in the directory of student-submission. There is no standard output or error, the return code is zero.
```
cd student-submission
```
This change to student-submission directory and has no standard output or error, the return code is zero.
```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
```
This imports JUnit. and runs ListExamples.java. It has no standard output but it has standard error, the return code is nonzero.
The stardard error is as follows:
```
ListExamples.java:15: error: ';' expected
        result.add(0, s)
                        ^
1 error
```
Then, we run to the if statement ``` if [ $? -eq 00 ] ``` to check, the if statement return false, we skip the then statement
```then
    echo "Successfully compile all the files"
 ```
so we went into else statement
```
else
    echo "There is some compile error"
    echo " You have earned "$score " out of 3"
    exit 1
```
The standard output is 
```
 There is some compile error
 You have earned 0  out of 3
 ``` 
 there is no standard error and the code exit early.
 The following is the code that we do not need to run due to exit early.
 ```
 java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples

if [ $? -eq 00 ]
then
    GRADE=3
    echo "Cong! You passed all tests!"
    echo " You have earned "$GRADE " out of 3"
else
    echo "Try again, some tests not passed"
    echo " You have earned "$GRADE " out of 3"
fi
```



This is the end of Lab report 5. Thank you for reading.
