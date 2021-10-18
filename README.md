# CIS223_Task2

In this practice, we will be implementing several custom methods for the linked list class.
- You are required to use python.
- For help you can use the lecture slides.

Given the code for the following linked list class...

<hr>

## The Problem - Part 1 (3 points)

Complete the <b>printrange</b> method. The method takes two integer numbers x and y as input and print the items from position x to y (Assuming the first item is at position 1 and x>=y).<br>
<br>
<b>Example 1:</b><br>
P = 1->2->3->4->5<br>
<code>P.printrange(3,5)</code> will print <code>3 4 5</code><br>
<br>
<b>Example 2:</b><br>
P = None<br>
<code>P.printrange(3,5)</code> will print <code>“No item in range”</code><br>
<br>
<b>Example 3:</b><br>
P = 1->2->3->4->5<br>
<code>P.printrange(3,10)</code> will print <code>3 4 5</code><br>

<br><hr>

## The Problem - Part 2 (4 points)

Complete the <b>alternateListjoin</b> method. Both p and q are LinkedList objects. The method inserts nodes of linked list q at alternate position of the list pointed by self.<br>
<br>
<b>Example 1:</b><br>
P = 1->3->5->7->9 and<br>
q = 2->4->6->8->10<br>
<code>P.alternateListjoin(q)</code> method will result in <code>P = 1->2->3->4->5->6->7->8->9->10</code> and <code>q = null</code><br>
<br>
<b>Example 2:</b><br>
P = 1->3->5 and<br>
q = 2->4->6->8->10<br>
<code>P.alternateListjoin(q)</code> method will result in <code>P = 1->2->3->4->5->6</code> and <code>q = 8->10</code><br>
<br>
<b>Example 3:</b><br>
P = 1->3->5->7->9 and<br>
q = 2->4->6<br>
<code>P.alternateListjoin(q)</code> method will result in <code>P = 1->2->3->4->5->6->7->9</code> and <code>q = null</code><br>

<br><hr>

## The Problem - Part 3 (3 points)

Write a code to test your implementation for various <em>cases</em>.<br>
