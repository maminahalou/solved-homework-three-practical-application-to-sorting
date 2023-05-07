Download Link: https://assignmentchef.com/product/solved-homework-three-practical-application-to-sorting
<br>



Consider the attached public dataset about the US Census Bureau Population and Housing Unit Estimates.

You are hired as a <em>software engineer</em> to build a simple program that will do the following:

<ul>

 <li><strong>calculate the percent increase or decrease in population size per state and per region (United States, Northeast, Midwest, South and West) and per state. </strong></li>

 <li><strong>to sort the percent increase (percentage of population change per state and per region) from the highest to the lowest. </strong></li>

</ul>

This could be a repetitive process for the end user, as the population size could change every day depending on the input/data error. Therefore, you will need to design the program to use the fastest sorting algorithm possible to sort the percent increase in population sizes.

In this homework you should empirically experiment sorting algorithms: Merge Sort, Bubble sort, Plain QuickSort and “your” designed version of an enhanced QuickSort (refer to the discussion we had in class on the last slides from chapter 5. You should also refer to the book on the sorting chapter).

Your program shall be able to do the following:

<ul>

 <li>Display the sorted percent change of all states between year X and year Y using a sorted algorithm, where the years X and Y are given as user input form the user and the name of the sorting algorithm is given as input from the user (see 3)</li>

 <li>Display the most similar state to state X in terms of percent change in population for a given year</li>

 <li>(3) Calculate the running time for your algorithm using System and the time function in Java for o Merge Sort o Bubble Sort o Plain QuickSort  o <strong>Improved QuickSort</strong> (comment the QuickSort algorithm and how you have improved it. I recommend looking at the official implementation found in Java for some inspiration)</li>

 <li>Ignore the grey portion in the Excel file and feel free to make changes to the Excel sheet as you see best to make it easy to read using Java and populate an array of State objects.</li>

 <li>Report on a word document the running time for one example of two years of your choice using the different sorting algorithms. Your improved quicksort should have the lowest running time using the <em>lang.System.currentTimeMillis(). </em></li>

</ul>