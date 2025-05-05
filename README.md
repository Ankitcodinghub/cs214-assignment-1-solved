# cs214-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS214 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs214-assignment-1-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98315&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS214 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problems Problem 1

Different variations of types int and float exist in C++ and other languages. They are usually limited by minimum and maximum values. Sometimes it is desired to have versions of these types with unlimited bounds. Java solves this problem by providing BigInteger and BigDecimal classes. In this problem it is required to develop a new C++ type (class) that can hold unlimited decimal integer values and performs arithmetic operations on them. You will develop in C++ a class, BigInt that supports writing

statements with extremely long integer values like these:

BigInt num1(“123456789012345678901234567890”); BigInt num2(“113456789011345678901134567890”); BigInt num3 = num2 + num1;

cout &lt;&lt; “num1 = ” &lt;&lt; num1 &lt;&lt; endl;

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
cout &lt;&lt; “num2 = ” &lt;&lt; num2 &lt;&lt; endl; //236913578023691357802369135780

cout &lt;&lt; “num2 + num1 = ” &lt;&lt; num3 &lt;&lt; endl;

Your task is:

<ol>
<li>(1) &nbsp;Design the class BigInt that has the following public interface (set of operations available
to use by developers using the class): [18 points, 3 points for each function]

BigInt (string decStr); // Initialize from string and rejects bad input BigInt (int decInt); // Initialize from integer

BigInt operator+ (BigInt anotherDec);

BigInt operator= (BigInt anotherDec);

Int size();

You will also need to overwrite the &lt;&lt; operator as follows:

friend ostream&amp; operator &lt;&lt; (ostream&amp; out, BigInt b)

Using data encapsulation, you are free to store the digits of the big decimal integer in whatever container you like. You might store them in an array, a vector, a string or whatever. These are details that are not important to the user of your class. You will need to build + and – operations that work on the representation you chose.
</li>
<li>(2) &nbsp;Implement the class BigInt and write five test cases (including –ve numbers) to test it. Implement a program that runs the test cases and verifies the result. [7 points, 2 for each test case and 2 for the class]</li>
<li>(3) &nbsp;Name a folder “A1_P1_ID1_ID2” and put your files inside it (even if it’s only one file)</li>
</ol>
Problem 2

You will develop an application for performing calculations on fractions.

(1) First, develop a class Fraction that represents a fraction by one integer divided by

another, e.g.,1/3 or 3/7. [24 points]

a. This class defines adding, subtracting, multiplying, dividing and comparing (&lt;, &gt;, ==, &lt;= and &gt;=) fractions by overloading the standard operators for these operations. [18 points]

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>It should also contain a function for reducing fractions. For example 2/6 is reduced after
calling the function to 1/3, etc. [2 points]
</li>
<li>You also need to overload I/O operators to be able to input and output fractions naturally
using &gt;&gt; and &lt;&lt; operators. [4 points]
</li>
</ol>
<ol start="2">
<li>(2) &nbsp;Separate class specifications from implementation by creating Fraction.h for specs and Fraction.cpp for implementation. [2 points]</li>
<li>(3) &nbsp;Second, develop a class FractionCalculator that utilizes the class Fraction and allows the user to input a fraction and perform calculations by adding, subtracting, etc. another fraction and then keeping the result as a fraction for further calculations. [4 points]</li>
<li>(4) &nbsp;Nameafolder“A1_P2_ID1_ID2”andputyourfilesinsideit(evenifit’sonlyonefile)</li>
</ol>
Problem 3

You will develop an application for matrix calculations.

<ol>
<li>(1) &nbsp;It is required to design and implement a generic class Matrix, in the form of a class template that accepts a type parameter. This way, when the class Matrix is instantiated, we decide if it should accept float, int or double, etc. [2 points]</li>
<li>(2) &nbsp;Matrix class holds a matrix of any size and allocates the required memory as needed. [2 points]</li>
<li>(3) &nbsp;Matrix class should have a destructor that frees used memory at the end of lifetime of each
Matrix objects. [2 points]
</li>
<li>(4) &nbsp;Matrixclassspecificationsshouldbeinaseparateheader“.h”file.[2points]</li>
<li>(5) &nbsp;It should have a pointer-to-pointer attribute that points to the matrix content. It should havesuitable constructors and methods for allocating the required memory space based on the dimensions decided by the user. [2 points]</li>
<li>(6) &nbsp;Overload standard operators and I/O operators to enable Matrix class with addition, subtraction and multiplication and suitable input and output capabilities. Add a method for matrix transpose. [12 points,2 points for each function]</li>
<li>(7) &nbsp;Then develop a MatrixCalculator class which offers the user a menu of operations to perform on int matrices as follows. Each of these options should be able to accept matrices of varying dimensions, which the user inputs. For multiplication, the calculator should check that two matrices are of dimensions n x m and m x p. [8 points, 2 for each choice]</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
1- Perform Matrix Addition

2- Perform Matrix Subtraction 3- Perform Matrix Multiplication 4- Matrix Transpose

(8) Name a folder “A1_P3_ID1_ID2” and put your files inside it (even if it’s only one file) Problem 4 [5 points]

The given function ListPermutations below prints all the permutations of a given string. It is required to modify this function so that it only prints unique strings. The current function will do exhaustive recursion to calculate all permutations. So, if the given string has duplicate characters, the output will have duplicate words. For example, if it is given the string “Makka”, it will print “Mkkaa” four times. Try this function and see how it works.

It is required to change the code so that it only prints unique combinations formed from the characters of the string. So for the above mentioned example, it should print “Mkkaa” once.

Hint. To solve this, all what you need is storing each new word you form. Before printing a new word or storing it, check if it is not already stored. You will need an array, a vector or a set to store the words formed so far.

Name a folder “A1_P4_ID1_ID2” and put your files inside it (even if it’s only one file)

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
void RecPermute(string soFar, string rest) {

if (rest == “”) // No more characters cout &lt;&lt; soFar &lt;&lt; endl; // Print the word else // Still more chars

// For each remaining char

for (int i = 0; i &lt; rest.length(); i++) {

string next = soFar + rest[i]; // Glue next char

string remaining = rest.substr(0, i)+ rest.substr(i+1); RecPermute(next, remaining);

} }

// “wrapper” function

void ListPermutations(string s) { RecPermute(“”, s);

}

Problem 5 [20 points]

You will develop an application for performing operations on strings.

<ol>
<li>(1) &nbsp;First,developaclassStudentNamethatrepresentsyourfullnameandhasonlyavariablename of type string. [2 points]</li>
<li>(2) &nbsp;Your class should contain a constructor that takes a string from user. The input string should contain at least 2 spaces. If the user violates this rule, you should copy the last name many times to make the names variable a name with 2 spaces. [4 points]

e.g., “ahmed Mohamed sayed”➔ “ahmed Mohamed sayed”</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
“sara ahmed” “Khaled”

“aya ali ahmed sayed”

</div>
<div class="column">
➔“sara ahmed ahmed” ➔“ khled Khaled Khaled” ➔“ aya ali ahmed sayed”

</div>
</div>
<div class="layoutArea">
<div class="column">
(3) Addafunctionprintthatprintsthedetailedpartsofthenameeachinoneline.[4points] 5|Page

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1 e.g., “aya ali ahmed sayed”

detailed parts of the name are: 1) aya

2) ali

3) ahmed 4) sayed

<ol start="4">
<li>(4) &nbsp;Add function replace(int i,int j) that replaces the name at position I with the name at position j and return true if operation is valid and false if one of the two indices is out of range. [5 points] e.g., “ahmed hassan ali”
replace(1,2)➔true➔“Hassan ahmed ali” replace(3,1)➔true➔“ali Hassan ahmed” replace(2,4) ➔ false
</li>
<li>(5) &nbsp;Write a main function and 5 test cases with different names. For each test case you should call the replace function and the print function to check the effect of the replacement if valid.

[5 points]</li>
<li>(6) &nbsp;Nameafolder“A1_P5_ID1_ID2”andputyourfilesinsideit(evenifit’sonlyonefile)</li>
</ol>
Problem 6

Write a program that handles an address book program, to process the following functions

<ol>
<li>(1) &nbsp;First,writeaclasscalledPhoneDirectory.Addafirstname,lastnameandphonenumberentry as a private.</li>
<li>(2) &nbsp;Themainprogramusesasimpletext-basedinterfacetogivetheuseraccesstothedirectory.In a while loop, the program presents the user with a menu of options:
<ol>
<li>Add an entry to the directory</li>
<li>Look up a phone number</li>
<li>Look up by first name</li>
<li>Delete an entry from the directory</li>
<li>List All entries in phone directory</li>
<li>Exit form this program</li>
</ol>
</li>
<li>(3) &nbsp;Deleteanentrybyfirstname.[4points]</li>
<li>(4) &nbsp;List the directory in alphabetical order by first name. [4 points]</li>
<li>(5) &nbsp;Use at least 3 sorting techniques for points 3 &amp; 4, to perform time analysis on these different
algorithms. [4 points]
</li>
<li>(6) &nbsp;Lookupanentrybyfirstname.[4points]</li>
<li>(7) &nbsp;Lookupanentrybyphonenumber.[4points]</li>
<li>(8) &nbsp;Nameafolder“A1_P6_ID1_ID2”andputyourfilesinsideit(evenifit’sonlyonefile)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Problem 7 [

If you have a list of songs in a music library and want to sort this list alphabetically. However, you want songs with the title “Untitled” to always appear at the top. Write a function called BiasedSort that accepts a vector by reference and sorts the songs according to the explained rules above.

Name a folder “A1_P7_ID1_ID2” and put your files inside it (even if it’s only one file)

Problem 8

Insertion sort uses linear search to find the right place for the next item to insert. Would it be faster to find the place using binary search (reduce number of comparisons)? We still must shift 1 item at a time from the largest till the right place. Use binary search on the already sorted items to find the place where the new element should go and then shift the exact number of items that need to be shifted and placing the new item in its place. The algorithm works the same, except that instead comparing and shifting item by item, it will compare quickly using binary search but it will still shift one by one till the right place (without comparison).

1) Plot the performance of the algorithm against the original insertion sort.

2) Name a folder “A1_P8_ID1_ID2” and put your files inside it (even if it’s only one file)

Problem 9

In this problem, we will develop classes to use for testing two sorting algorithms (Selection and Quick sort). The class will have methods to support experimenting and analyzing sorting algorithms performance. Below is a high-level UML diagram for your classes. Add any missing details. Testbed class has the following functions that you should complete:

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>(1) &nbsp;GenerateRandomList(min, max, size) Generate a given number of random integer data from a certain range. For example, one can generate a vector/array of 10000 integer numbers that fall in the range from 1 to 100000, e.g., [5554, 32300, 98000, 342, …]</li>
<li>(2) &nbsp;GenerateReverseOrderedList(min, max, size) Generate a given number of reverse ordered integer data from a certain range. You can first generate random data and then sort them reversed</li>
<li>(3) &nbsp;RunOnce(sorter, data, size) Run a given sorting algorithm on a given set of data and calculate the time taken to sort the data</li>
<li>(4) &nbsp;RunAndAverage(sorter, type, min, max, size, sets_num) Run a given sorting algorithm on several sets of data of the same length and same attributes (from the same range and equally sorted; e.g., random or reversed) and calculate the average time</li>
<li>(5) &nbsp;RunExperient (sorter, type, min, max, min_val, max_val, sets_num, step) Develop an experiment to run a given sorting algorithm and calculate its performance on sets of different sizes (e.g., data of size 10000, 20000, etc.) as follows:
<ol>
<li>All sets are generated with values between min and max</li>
<li>First, generate sets_num sets with size min_val. Use RunAndAverage () and
record average time to process the sets
</li>
<li>Next, repeat step ii but with sets whose size increases by step till reaching
max_val. Each time record average time to process the sets
</li>
<li>For example I should be able to design an experiment to run Quick sort
algorithm on randomly sorted integers data taken from the range (1 to 1,100,000) and with input value (data size) from 0 to 100000, with step 5000. This means we will run the algorithms on data sets of 5000, 10000, 15000, …, 100000 randomly sorted integers. Note that with each step you will generate sets_num different sets and take the average of their runs
</li>
<li>The output of the experiment goes to screen as a table with two columns; first column indicates set size, and second column indicates average time</li>
</ol>
</li>
</ol>
Write a main() demo to show that the function works correctly and to measure the performance of Quick sort and Selection sort in cases of random data and reverse ordered data using Testbed class. Draw plots of your results.

Name a folder “A1_P9_ID1_ID2” and put your files inside it (even if it’s only one file) Notes:

In problems 8 and 9 requires you to plot your results which means you provide chart in excel document with a table of the numbers you obtained from the experiment.

The plot will have running time (in sec or msec) which is represented on y-axis and size of the data on x- axis. Array size rages from 100 to 1000000 or more.

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 10 [

In this problem, you should develop a linked list class similar to that provided in the C++ STL.

The public interface of your class should provide basic insertion and deletion functions. In addition, it should provide an iterator class as an inner class in order to access the data stored in the list. For example, if we have a list of three elements, and want to access the second element, we should declare an iterator and initialize it to the position of the first element, and move to the second position as shown in the code below:

<pre>list&lt;int&gt; myList;
myList.push_back(1);
myList.push_back(2);
myList.push_back(3);
list&lt;int&gt;::iterator it = myList.begin();
it++;
</pre>
cout&lt;&lt; *it;

notice the usage of the scope operator in the declaration of the iterator, this is because the iterator class is defined as an inner class inside the list class:

<pre>template&lt;class type&gt;
class myList {
public:
class iterator {
</pre>
// your code for the iterator class here };

// your code for the list class here

};

Your list class should be a template class. [3 points]

The list class should have the following public interface:

• list() – default constructor. [3 points]

• list(type value, int initial_size) – constructs a list having ‘initial_size’ elements whose values are ‘value’. [3 points]

• ~list() – a destructor to clear the list and leave no memory leaks. [3 points]

• int size() – returns the current number of elements in the list. [3 points]

• void insert(type value, iterator position) – adds an element at position specified by the iterator. For example, if the passed iterator currently points to the second element, this element will be shifted on position, and the new value should be added at the second position. [3 points]

• iterator erase(iterator position) – erases the element specified by the iterator and return an iterator to the next element, throws exception if position points after

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
• list&lt;type&gt;&amp; operator = (list&lt;type&gt; another_list) – overloads the assignment operator to deep copy a list into another list and return the current list by reference. [4 points]

• iterator begin() – returns an iterator pointing to the first element. [3 points]

• iterator end() – returns an iterator pointing after the last element. [3 points]

You should develop an iterator class the following public interface:

• void operator ++ () – overloads the operator ++, it should advance the iterator one position towards the end of the list, throws exception if it is currently pointing after the last element. [3 points]

• void operator — () – overloads the operator –, it should move the iterator one position toward the beginning of the list, throws exception if it is currently pointing to the

first element of the list. [3 points]

• type&amp; operator * () – overloads the dereference operator to return the value contained in the current node by refence to allow its modification. [3 points]

• bool operator == (const iterator &amp;) – overloads the equality comparison operator, should return true if the passed operator points to the same node. [3 points]

All node pointers in the list class of the iterator class should be private and inaccessible from outside of the class. [3 points]

No memory leaks or dangling pointers. [3 points]

It is highly recommended to implement it as a double linked list, however, it is up to you.

As mentioned above, our .end() function should return an iterator pointing to a position after the last element as the STL .end() function does. This can be done easily by having a dummy node after the actual tail, this dummy node contains no data, but mark the end of the list. So, physically, our list is never empty, which will ease the implementation of insertion and remove operations, as now we don’t have to handle an “empty list” case. However, this dummy node should be disregarded when we return the size.

Write a main function to test all the above

Name a folder “A1_P10_ID1_ID2” and put your files inside it (even if it’s only one file)

Rules

<ul>
<li>Cheating will be punished by giving -2 * assignment mark.</li>
<li>Cheating is submitting code or report taken from any source that you did not fully write
yourself (from the net, from a book, from a colleague, etc.)
</li>
<li>Giving your code to others is also considered cheating. Both the giver and the taker will get –
10.
</li>
<li>People are encouraged to help others fix their code but cannot give them their own code.</li>
<li>Do not say we solved it together and we understand it. You can write the algorithm on paper
together but each group should implement it alone.
</li>
<li>If you do not follow the delivery style (time and files names), your assignment will be rejected
&nbsp;
</li>
</ul>
</div>
</div>
</div>
