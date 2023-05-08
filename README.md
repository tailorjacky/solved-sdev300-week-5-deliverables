Download Link: https://assignmentchef.com/product/solved-sdev300-week-5-deliverables
<br>
<strong>Overview</strong>: In this week, you have studied additional Python language syntax including File I/O, Exceptions and Object-Oriented Programming. The Lab for this week demonstrates your knowledge of this additional Python functionality. Be sure to use the examples in the textbook reading along with the associate libraries, functions and processes when completing the assignments for this week.







<strong>Submission requirements for this project include 4 files. (Zipping them into one file is acceptable and encouraged):  </strong>




<ul>

 <li>Python Data Analysis Code</li>

 <li>2 Input Files (Same files supplied to you)</li>

 <li>Word, Excel or PDF file containing your test results</li>

</ul>




<strong>Python Applications for Lab4: (total 100 points):  </strong>




This exercise <strong>(80 points) </strong>allows a user to load one of two CSV files and then perform histogram analysis and plots for select variables on the datasets. The first dataset represents the population change for specific dates for U.S. regions. The second dataset represents Housing data over an extended period of time describing home age, number of bedrooms and other variables. The first row provides a column name for each dataset. The following columns should be used to perform analysis:




<ul>

 <li>csv:</li>

 <li>Pop Apr 1</li>

 <li>Pop Jul 1</li>

 <li>Change Pop</li>

</ul>




Housing.csv:

<ul>

 <li>AGE</li>

 <li>BEDRMS</li>

 <li>BUILT</li>

 <li>ROOMS</li>

 <li>UTILITY</li>

</ul>




Notice for the Housing CSV file, there are more columns in the file than are required to be analyzed. You can and should still load each column.




Specific statistics should include:




<ul>

 <li>Count</li>

 <li>Mean</li>

 <li>Standard Deviation</li>

 <li>Min</li>

 <li>Max</li>

 <li>Histogram</li>

</ul>




A user interface might look similar to this:




***************** Welcome to the Python Data Analysis App**********

Select the file you want to analyze:

<ol>

 <li>Population Data</li>

 <li>Housing Data</li>

 <li>Exit the Program</li>

</ol>




1

You have entered Population Data.  Select the Column you want to analyze:

<ol>

 <li>Pop Apr 1</li>

 <li>Pop Jul 1</li>

 <li>Change Pop</li>

 <li>Exit Column a</li>

</ol>

You selected Pop Apr 1

The statistics for this column are:

Count = 10000

Mean = 32.5

Standard Deviation = 4.5

Min = 53.2

Max = 12.5

The Histogram of this column is now displayed.







Select the Column you want to analyze:

<ol>

 <li>Pop Apr 1</li>

 <li>Pop Jul 1</li>

 <li>Change Pop</li>

 <li>Exit Column</li>

</ol>

d

You selected to exit the column menu  Select the file you want to analyze:

<ol>

 <li>Population Data</li>

 <li>Housing Data</li>

 <li>Exit the Program</li>

</ol>




3

*************** Thanks for using the Data Analysis App**********

If an inappropriate entry is detected, the program should prompt for a correct value and continue to do so until a correct value is entered.

Hints:




<ol>

 <li>Use the Pandas, Numpy, MatplotLib and other Python modules when appropriate.</li>

 <li>Be sure to install the required Python modules in your environment before you import or try to use them in your code. For example, pip install each of the required modules that are external Python libraries that you need.</li>

 <li>If an inappropriate entry is detected, the program should prompt for a correct value and continue to do so until a correct value is entered.</li>

 <li>Use comments to document your code</li>

 <li>Test with many combinations.</li>

 <li>Use pylint to verify the code style – the goal is a 10!</li>

 <li>The user Interface should continue to run until the user indicates they are ready to exit.</li>

 <li>Be sure to review the previous readings and modules as you may need to use statistics and other modules to complete this lab.</li>

</ol>




<ol start="2">

 <li><strong>(20 points)</strong> Document your testing results using your programming environment. You should also include and discuss your pylint results for the application. The test document should include a test table that includes the input values, the expected results and the actual results. A screen capture should be included that shows the actual test results of running each test case found in the test table. Be sure to include multiple test cases to provide full coverage for all code and for each function you develop and test.</li>

</ol>


