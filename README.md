# quiz-2-correction
# Quiz 2 correction
1.Write the following mathematical expressions in Java. Assume variables `a`, `b`, and `c` have been declared and initialized.
**answer** (-b + Math.sqrt(b*b -4*a*c)) / (2 * a)
2. Complte he truth table

| A      | B    |
| ------------- |
| true | true   |
| true | false  |
| false | true  |
| false  | false |
| A and B | A   or B  |
| ------- | --------- |
| true| true |
| false | true |
|false | true| 
|false | true|
3.
Select the true expressions.
  1 >= 2 || !false is 'true'
  true && !true  is  'true '
    true != false 'false'
  !(3 % 2 == 1) && true 'false'
4.
you can omit an else statement if there is no tsaks define
5.
`int m = 2;

int n = 5;

if (m * m >= n + n) {

    n = n - 1;

    m = (m + 1) + n;

} else {

    m = (m + 10) * 2;

    n = n + 1;

}

**answer** 
| 'm'           | 'n'           |
| ------------- | ------------- |
| 2             |         5     |
| 24            |         6     |

6
'''
b
c
'''
7.
`nt x = 1;

if (x >= 2)

   System.out.println("A");

else if (x == 3 || x <= 4)

   System.out.println("B");

else

   System.out.println("C");

if (x <= 5)

   System.out.println("X");

if (x != 6 && x > 7)

   System.out.println("Y");

else

   System.out.println("Z");`

   **answer**

   '''
   B
   X
   Z
   '''
8.
`int x = 2;

int y = 3;

if (x < 10 && 5 >= y) {

   System.out.println("where?");

   if (y < 0  || y == 3)

      System.out.println("here");

   else

      System.out.println("there");

} else {

   if (x == 2 || x != 3)

      System.out.println("this");

   else

      System.out.println("that");

   System.out.println("what?");

}

System.out.println("why?");`
**answer**
'''
where
here
why
'''
8.
String strOne = "code";

String strTwo = new String("code");

if (strOne == strTwo)

   System.out.println("equal");

else

   System.out.println("not equal");

if (strOne.equals(strTwo))

   System.out.println("equal");

else

   System.out.println("not equal");

9.
`String strOne = "code";

String strTwo = new String("code");

if (strOne == strTwo)

   System.out.println("equal");

else

   System.out.println("not equal");

if (strOne.equals(strTwo))

   System.out.println("equal");

else

   System.out.println("not equal");`
**annswer**
```
not equal

equal
```
10. int x = 2;

switch (x) {

    case 0:

        System.out.println("one");

        break;

    case 1:

        System.out.println("two");

        break;

   default:

       System.out.println("three");

        break;

}

System.out.println("done!");
**answer**
```
three

done!
```
11.`char ans = 'b';

switch (ans){

    case 'a':    System.out.println("Congratulations!");

    case 'b':    System.out.println("Incorrect");

    case 'c':    System.out.println("Incorrect");

    default:     System.out.println("Invalid choice!");

}`

**answer**
```
Incorrect

Incorrect

Invalid choice!
```

12.
Write a boolean expression that is true if the first character in the string variable str is a upper-case alphabetic character. Assume str has been declared and initialized. Hint:  Use the charAt method.

```
'A' <= str.charAt(0) && str.charAt(0) <= 'Z'

```
13. Write an if-else statement that displays "___ is even" if the value of the int variable num is even, otherwise display "___ is odd" (the blank must be the value of num). Assume num has been declared and initialized.

    
**answer**
`if (num % 2 ==0) {

   System.out.println(num + " is even");

} else {

   System.out.println("num + "is odd");

}`



  
