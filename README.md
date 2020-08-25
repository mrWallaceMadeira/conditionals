# `If` two roads diverged in a yellow wood
This is where the rubber hits the road, folks.\
Prior to this lesson our programs looked like a straight line.
```
  String myString = "Mr.Wallace";
  String newString = myString + " teaches Intro to CS";
  System.out.println(newString);
  
```
Each of these three lines will be run by the computer (unless I missed an error).\
We'll learn how to make more complex programs by adding new 'paths' to our code

![noIdea](noIdea.gif)

----

### `If` & `else`
The two basic control flow mechanisms are if/else statements.\
Unlike `String myString = "computer";` if/else statements don't declare variables or assign value.\
They work like this&nbsp; :arrow_down: 
```
  int myInt = 10;
  if (myInt == 10) {
    System.out.println("It was ten.");
  }
  else {
    System.out.println("It wasn't ten.");
  }
```
So what do we notice here?
  - [x] `==` the comparison operator we covered in booleans
      - **Remember**: this statement will evaluate to `true` or `false`
  - [x] Some of these: `{}` lil' guys

All if/else statements _must_ take a boolean statement within their `()`.\
Think of it like a yes/no question
  - If the answer is yes, do the stuff inside `{}` 
  - If it's no, do the stuff inside the `{}` that correspond with else

### :hand:&nbsp; Stop!
Watch [this](https://youtube.com)

### `If` + `else` = `else if` ?
You might have noticed that `else` statements are a sort of 'catch-all'.\
Meaning, if the  `if` statements aren't true, we run the else statement.\
But what if we only have `if` statements, or we only want if statements to run in a specific scenario?\
Enter `else if` & nested `if`

###### Let's start with an example
```
  int myInt = 1;
  if (true) {
    myInt = 2;
    if (false) {
      myInt = 3;
    }
  }
  else if (true) {
    myInt = 4;
  }
  else {
    myInt = 5;
  }   
```
A _lot_ going on here. Watch [this video](https://youtube.com) to see how it works.

### :performing_arts:&nbsp; C'est fini 
Entry ticket [here](https://forms.office.com/Pages/ResponsePage.aspx?id=P9fbuiFvgkyZJ5ogeV5C0bXAAGShYuhAq0O_bKHZJnxUNEg2TVE1TElGOTBBQVlOMDdWUzJBOEszSCQlQCN0PWcu)


