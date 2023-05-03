Download Link: https://assignmentchef.com/product/solved-cs2040c-assignment-2-template-and-linked-list-sorting
<br>
A zip file of the solution files for MS Visual Studio (or .zip of XCode file for Mac users) is provided that contains

<ul>

 <li>The Linked List class mentioned in lecture</li>

</ul>

o simpleLinkedListTemplate.h o simpleLinkedListTemplate.hpp (or .cpp, it doesn’t matter)

<ul>

 <li>A main file to use the Linked List: cpp</li>

 <li>And the files for class Food: h, food.cpp</li>

</ul>

You will <strong>only</strong> submit the modifications in these two files ONLY:

<ul>

 <li>h</li>

 <li>cpp</li>

</ul>

More precisely, you will only submit the following to coursemology only:

<ul>

 <li>The List class declaration (optional, only if you had modified it)</li>

 <li>exist()</li>

 <li>extractMax() reverseOp()</li>

 <li>And any new auxiliary functions you have added.</li>

</ul>

However, you can modify other files, especially for your own testing and debugging. But in our grading, we will assume all the other files are the not changed.

More precisely, you are only allowed to ADD more helping members or methods and you should NOT change the existing implemented declarations and implementations

Look into the main.cpp file. It contains the code:

int main() {   testIntLL();   testFoodExist();   testFoodOpGreaterThan();   testFoodAddition();   testFoodSort();   testReverseOp();   return 0;

}

<h1>Task 1</h1>

The member function exist() is missing. Your job is to implement it in the same way you did in the previous assignment. Here is some sample output:

<h1>Task 2</h1>

Task 2 is to implement the operation “+” for food. For example:

Food food1(“Salad”, 100);

Food food2(“Chicken”, 200);

Food food3(“Curry”, 40);

Food <strong>food23</strong> = food2 + food3;




<strong>So the name of</strong> food23 will be Chicken Curry with 240 calories. Here is the sample output for the code given:




<h1>Task 3</h1>

To implement the function extractMax() in List&lt;T&gt;. This function will

<ul>

 <li>Find the maximum item in the list</li>

 <li>delete the node in the list and return the maximum item</li>

</ul>

Sample output:




If you have done it right, you can use it to sort the list by:

while (!l.empty())

cout &lt;&lt; l.extractMax() &lt;&lt; ” ” ;

cout &lt;&lt; endl




And it should work for any class like Food also, if you implement it correctly:




<h1>Task 4</h1>

Write down your thoughts. What are the disadvantages of the “LinkedList extractMax Sorting”? List at least two disadvantages in coursemology.

<h1>Task 5</h1>

Implement the function reverseOp() in the class List. It will reverse the order of the items in the list. Each time you call l.reverseOp() to modify “itself”. Sample output from the function testReverseOp():




<h1>Extra Tasks (Not Graded)</h1>

If you are looking for extra challenges, you could try the followings by yourself.

<ul>

 <li>Implement the “==“ operators for the class Food</li>

 <li>Google how did we do “cout &lt;&lt; food;”</li>

 <li>Implement another class to use it with the LinkedList Look at the slides for an example of a class called “Hero”.</li>

</ul>


