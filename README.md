Download Link: https://assignmentchef.com/product/solved-cs2400-homework-7-set-class
<br>
Design classes, arrays/vectors in classes, operator overloading, separate compilation.

<strong>You may use any function or library discussed in class or in the chapters we covered from your textbook. Do not use any other libraries or functions. </strong>

Design a class that stores a mathematical <em>set</em> of integers called <strong><em>MySet</em></strong> <strong>(do not use a different name)</strong>. You may assume that the set will never have more than 100 elements.  The class should include the following functions:

<ul>

 <li>A default constructor that initializes a set to the empty set.</li>

 <li>Overload the “^” operator to implement the set membership<em>.</em> Returns true if an element is in the set.</li>

 <li>Overload the “+” operator to add an element to the set. Return the original set with the new element added.</li>

 <li>Overload the “-” operator to remove an element from the set. Return the original set with the new element removed.</li>

 <li>Overload the “+” operator to implement the union of two sets. Returns a new set that contains all the elements of the both sets.</li>

 <li>Overload the “*” operator to implement the intersection of two sets. Returns a new set that contains all the elements that are in both sets.</li>

 <li>Overload the “-” operator to implement the set difference. Returns a new set that contains all the elements that are in the first set but not in the second.</li>

 <li>Overload the “&lt;=” operator to implement the subset. Returns true if all the elements of the first set are in the second.</li>

 <li>Overload the “&gt;=” operator to implement the superset. Returns true if all the elements of the second set are in the first.</li>

 <li>Overload the “==” operator to implement the set equality<em>.</em> Returns true if both sets contain the same elements (in any order).</li>

 <li>A function called <strong><em>toString</em></strong> that returns a set string in the format {1, 2, 3, 4}).</li>

</ul>

The set elements must be sorted.

<ul>

 <li>A function to return the number of elements in the set (<strong><em>size</em></strong>).</li>

 <li>A function to clear the set by removing all the elements (<strong><em>clear</em></strong>).</li>

 <li>Separate the MySet class into two files myset.h and myset.cc.</li>

</ul>

Write a main program to test your code or use the unit tests provided.  make run_tests

<strong>Hints: Follow these steps in order: </strong>

<ol>

 <li>Design the class <em>MySet</em> with an array/vector of integers to store the numbers.</li>

 <li>Write the <em>size</em></li>

 <li>Write the membership function (^).</li>

 <li>Write the <em>+</em></li>

 <li>Write the <em>toString</em></li>

 <li><strong>Test your class before proceeding with the rest of the functions. You may run the provided tests any time by issueing the command “</strong><strong>make run_tests”. It should test all the required functions. </strong></li>

 <li>Write the clear functions.</li>

 <li>Write the remove function (-).</li>

 <li>Write the <em>intersection</em> function (*).</li>

 <li>Write the <em>difference</em> function (-).</li>

 <li>Write the <em>subset</em> function (&lt;=).</li>

 <li>Write the <em>superset</em> function (&gt;=).</li>

 <li>Write the <em>equal</em> function (==).</li>

</ol>