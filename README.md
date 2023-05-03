Download Link: https://assignmentchef.com/product/solved-cs1331-homework-01-age-calculator
<br>
<h1>Problem Description</h1>

You’ve now been introduced writing a program in Java. This means you can write simple, but useful programs! Given your newfound skills, you’ve been hired by a company to calculate the age of customers! You’ve been provided with a Java class, <sub>AgeCalculator </sub>that you need to fill in to the appropriate specifications.

<h1>Solution Description</h1>

For this assignment, you won’t be expected to write your own class. Instead, we’ll provide the class and you simply have to fill in the <sub>main </sub>method. Keep in mind that what you print out should match the defined output <em><sub>exactly</sub></em>. Deviation from what the output should be, even by a character or two, will result in lost points.

To start, save the following code in a file called <sub>AgeCalculator.java</sub>:

<table width="632">

 <tbody>

  <tr>

   <td width="632"><strong>public class </strong>AgeCalculator { <strong>public </strong>static void main(String[] args) { <em>// Do not modify the following line.</em>int birthYear = Integer.parseInt(args[0]); <em>// Part 1:</em><em>// Part 2:</em>}}</td>

  </tr>

 </tbody>

</table>

<h2>Part 1: Calculate the age</h2>

Inside of the main method, create a variable called <sub>age </sub>that can hold integers. Assign to <sub>age </sub>the age of the subject. Assume that someone’s age is the difference between 2019 and their birth year.

<h2>Part 2: Report the age</h2>

Once you calculate the age, it’s time to print it out. Output should be in the form:

This person is [age] years old!

<h1>Testing your app</h1>

In order to test your program, you can run <sub>java AgeCalculator [birth year] </sub>with some example year. For example,

java AgeCalculator 1998 prints out This person is 21 years old!

java AgeCalculator 2001 prints out This person is 18 years old! ___

<strong>Allowed Imports</strong>

To prevent trivialization of the assignment, you are <em><sub>not </sub></em>allowed to import any classes or packages.

<h1>Feature Restrictions</h1>

There are a few features and methods in Java that overly simplify the concepts we are trying to teach. For that reason, do not use any of the following in your final submission:

<ul>

 <li>var (the reserved keyword)</li>

 <li>exit</li>

</ul>

<h1>Collaboration</h1>

<h2>Collaboration Statement</h2>

To ensure that you acknowledge a collaboration and give credit where credit is due, <strong><sub>we require that </sub>you place a collaboration statement as a comment at the top of at least one java file that you submit</strong>. That collaboration statement should say either:

<em>I worked on the homework assignment alone, using only course materials.</em>

or

<em>In order to help learn course concepts, I worked on the homework with [give the names of the people you worked with], discussed homework topics and issues with [provide names of people], and/or consulted related material that can be found at [cite any other materials not provided as course materials for CS 1331 that assisted your learning].</em>

Recall that comments are special lines in Java that begin with <sub>//</sub>.


