# Essential-Csharp-Interview-Questions

# Question 1
### Difference between Array and ArrayList?
<blockquote>
<p>1. <code>Array</code> is strongly typed and can store only same type of data while <code>ArrayList</code> can store any type of data.</p>
<p>2. <code>Array</code> stores fixed number of elements while <code>ArrayList</code> can store any number of elements as it grows dynamically.</p>
<p>3. In <code>Array</code> no need to cast elements while retrieving whereas in <code>ArrayList</code> items need to be cast to appropriate data type while retrieving.</p>
</blockquote>

# Question 2
### Difference between String and StringBuilder?
<blockquote>
<p>1. <code>String</code> is immutable i.e. if we create a string object then we can't modify it & it always creates new object of string type in memory while <code>StringBuilder</code> is mutable i.e. if we create StringBuilder object then we can perform any operation like insert, replace or append without creating new instance every time.</p>
<p>2. <code>String</code> belongs to System class while <code>StringBuilder</code> belongs to System.Text class.</p>
</blockquote>

# Question 3
### Difference between ArrayList and HashTable?
<blockquote>
<p>1. <code>ArrayList</code> stores only the value at a particular index while <code>HashTable</code> stores data as Key-Value pair.</p>
<p>2. To access value from <code>ArrayList</code>, index number should be passed while to access value from <code>HashTable</code> key should be passed.</p>
</blockquote>

# Question 4
### Difference between while and for loop?
<blockquote>
<p>Both loops are used when a unit of code needs to execute repeatedly.</p>
<p><code>For loop</code> is used when you know how many times you need to iterate through the code whereas <code>while loop</code> is used when you need to repeat something until a given statement is true.</p>
</blockquote>

# Question 5
### Define Boxing and Unboxing?
<blockquote>
<p>Boxing is converting a value type to an object type.</p>
<p>Unboxing is extracting the value type from the object type.</p>
</blockquote>
  ```C#
  int i =13; 
  object myObject = i; //Boxing-implicit 
  i = (int)myObject; //Unboxing-explicit
  ```

# Question 6
### Difference between Constants and Read-Only variables?
<blockquote>
<p>1. <code>Constants</code> are evaluated compile-time while <code>Read-Only variables</code> are evaluated at runtime.</p>
<p>2. <code>Constants</code> only support value-type variables while <code>Read-Only variables</code> can hold reference type variables.</p>
<p>3. <code>Constants</code> should be used when the value won't change during runtime while <code>Read-Only variables</code> are used mostly when their actual value is unknown before the runtime.</p>
</blockquote>

# Question 7
### Difference between == and Equals()?
<blockquote>
<p>1. <code>==</code> is the comparison operator while <code>Equals()</code> compares the contents of a String.</p>
<p>2. <code>==</code> compares the reference identity as well as the contents while <code>Equals()</code> compares only the contents.</p>
</blockquote>

# Question 8
# Question 9
# Question 10

# Question 11
# Question 12
# Question 13

# Question 14
# Question 15
# Question 16

# Question 17
# Question 18
# Question 19

# License

This book is released under a Creative Commons Attribution-Noncommercial- No Derivative Works 3.0 United States License.

What this means is that it is free to read and use, but the license does not permit commercial use of the material (i.e you can freely print out the questions for your own use, but you can't sell it). I'm trying to help so I would greatly appreciate it if you would respect these terms.

Copyright Aditya Kumar, 2017.
