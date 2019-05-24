## Points to Remember

1. Numpy is the N-Dimensional Array Storage
2. Fast, Mathematical computational Libary
3. It is implementated in C, So it can store homogeneous data
4. It has lot of in-built functions
5. Entire `scikit learn`(Popular Machine Learning Library) is internally built using Numpy.

## How Numpy works? Why it is so fast compared to list?

1. Let's see how python list stores data...
        list_1 = [1, 2, "Hello", 5.5]
         * As this list has 4 elements, it create 4 references.
         * The way list stores data and points to the memory is using References. 
         * List doesn't holds data, it stores the references for all elements. That's why it able to handle the Heterogeneous Data(which means single list can hold data with different data type).
         
2. But Numpy is homogeneous data structure
         * How to Import Numpy Library 
             `import numpy as np`
         * How to store data in Numpy
             ` abc = n.array([1,2,3,4])`
         * It stores data as C-array stores...
             ==> Numpy allocates data in memory itself
         * As memory holds the data directly, Numpy is more faster than list. We can fetch the data in single step directly from Memory whereas in List its two step process(1. have to go to memory, memory will point to reference(some address) 2. Then have to go to that address, to fetch the data )
         
         
## Steps to Follow to get mastering in Numpy

1. Numpy Initialization and Creation
2. How to access, Split, reshape and stack the numpy data structure
3. What are the Methods and functionalities their in Numpy
4. Broadcasting (Entire Machine Learning uses it again and again)

         
         

        


