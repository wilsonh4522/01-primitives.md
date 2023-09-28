# Process Writeup

## Name: Wilson Huang
## Course: APSCA
## Period: 7
## Concept: Primitives

### Introduction
In APCSA (Advanced Placement Computer Science A), we are learning about Java. Learning Java is somewhat similar to Javascript; so learning Java has so far been easier due to my background knowledge in JavaScript. But I have faced challenges throughout my learning experience. In the past 2 weeks or so we have been learning about unit 1 (primitives) in a website called ProjectStem. We later took an exam about primitives in which I did good on. In the text below I will show you my challenges and takeaways when learning about primitives.

### Challenge 1
One challenge I had when learning Java is puting the semicolon after each line of code. This may seem simple but I am still getting used to Java. Last year I learned about Javascript which wasn't to sensitve about the comma but with Java, it is the opposite.
#### Wrong line of code
```java
System.out.println(numItem + " " + item + " at " + itemWeight + " pounds each will weigh " + totalWeight + " pounds total")
```
As you can see here, the code above will show an error because there is no semi colon. I spent a while looking to see whats wrong with the variables, addition signs, and quotes.
#### Correct line of code
```java
System.out.println(numItem + " " + item + " at " + itemWeight + " pounds each will weigh " + totalWeight + " pounds total");
```

### Challenge 2
Another challenge I had is rounding. Rounding in Java was different than rounding in math. For an example if you wanted to round 9.6 to the nearest whole number, it would be 9 in java instead of a 10. This confused me when I learned it. Then I learned that you can add 0.5 so that it rounds to the nearest whole numner. So 9.6 would be 10.
#### Example
```java
int rounded = (int) (overall + 0.5);
overall = 2.4 //3
overall = 1.7 //2
overall = 8.5 //9
```

### Challenge 3
The last challenge I faced was after finshing unit 1 we had to take an exam on it. I got 2 questions wrong. I was confused on how I got one wrong. The question asked us to print the tens column of an integer stored in x?
#### Incorrect
```java
System.out.print(x % 10 / 10);
```
I chose this because I was confused on what the mod did. If I take a number like 85 it would output 0.5 which is incorrect
#### Correct
```java
System.out.print(x / 10 % 10);
```
This choice is correct because if you were to take a number like 85 again it would output 0.85

### Takeaways
* Always take notes because they will come in handy when you are confused about something. For an example I should've taken more notes about what mod does because I foregot
* You should plug in a random number to see the output. For example if I plugged in a number during the test I could get the answer
