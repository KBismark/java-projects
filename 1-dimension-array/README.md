An array is a simple data structure used to store a collection of data in a contiguous block of memory. Each element in the collection is accessed using an index, and the elements are easy to find because they're stored sequentially in memory.    

Because the collection of elements in an array is stored as a big block of data, we typically use arrays when we know exactly how many pieces of data we're going to have. For example, you might use an array to store a list of student ID numbers, or the names of state capitals. To create an array of integers named ***MyArray*** that can hold four integer values, you would write the following code:    

`int[] myArray = new int[4];`    
This sets aside a block of memory that's capable of storing **4** integers. Each integer storage cell is assigned a unique index ranging from **0** to one less than the size of the array, and each cell initially contains a **0**. In the case of ***MyArray***, we can store integers at indices **0**, **1**, **2**, and **3**. Let's say we wanted the last cell to store the number **12**; to do this, we write:    

`myArray[3] = 12;`    
Similarly, we can print the contents of the last cell with the following code:    

`System.out.println(myArray[3]);`    
The code above prints the value stored at index  **3** of **myArray**, which is  **12** (the value we previously stored there). It's important to note that while Java initializes each cell of an array of integers with a **0**, not all languages do this.    

## Task    

Find task at [Hackerrank challenges](https://www.hackerrank.com/challenges/java-1d-array-introduction/problem)   
