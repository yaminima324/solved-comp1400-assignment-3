Download Link: https://assignmentchef.com/product/solved-comp1400-assignment-3
<br>
<ol>

 <li><strong>8 </strong>(p. 94) The following if statement is unnecessarily complicated. Simplify it as much as possible.</li>

</ol>

(<em>Hint: </em>The entire statement can be replaced by a single assignment.) if (age &gt;=13)

if (age &lt;=19)

teenage = true

else

teenage = false

else if (age &lt; 13)

teenage = false

<ol start="2">

 <li><strong>11 </strong>(p. 97) Write a program that asks the user for a two-digit number, and then prints the English word for the number:</li>

</ol>

Enter a two-digit number: <u>45 </u>you entered the number forty-five.

<em>Hint: </em>Break the number into two digits. Use one switch statement to print the word for the first digit (“twenty”, “thirty”, and so forth). Use a second switch statement to print the word for the second digit. Don’t forget that the numbers between 11 and 19 require special treatment.

<ol start="3">

 <li><strong>1-3 </strong>(p. 121) What output does each of the following program fragment produce?</li>

</ol>

(a) i = 1;         (b) i = 9384;        (c) i = 5; while (i &lt;= 128) {             do {        j = i – 1;

printf(“%d “, i);               printf(“%d “, i); for (; i &gt; 0, j &gt; 0; –i, j = i-1) i *= 2;                i /= 10;  printf(“%d “, i);

}                                                                  } while (i &gt; 0);

<ol start="4">

 <li>What output does each of the following flowcharts produce? Write a program fragment in C for each</li>

</ol>

of the flowcharts, and submit the codes online. of the flowcharts, and submit the codes online.

<ol start="5">

 <li><strong>11 </strong>(p. 124) The value of the mathematical constant can be expressed as an infinite series:</li>

</ol>

Write a program that approximate <em> </em>by computing the value of

where <em>n </em>is an integer entered by the user. Save and submit the program as a3 epsilon0.c.

<ol start="6">

 <li><strong>12</strong>∗ (p. 124) The attached flowchart a3 epsilon.rap provides a modified solution to Q3.5. It allows for continuous addition of terms until the current term becomes less than a small (floating-point) number <em>ε </em>entered by the user. Write an equivalent program in C, and save and submit the program as a3 epsilon1.c.</li>

</ol>

(<em>Hint: </em>In implementation, be careful with different types between the two sides of an assignment statement.)