#                                                     Insertion Sort

## 1) Insertion sort of [22,27,16,2,18,6]

    [22|,27,16,2,18,6] 
    [22,27|,16,2,18,6]
    [16,22,27|,2,18,6] 
    [2,16,22,27|,18,6] 
    [2,16,18,22,27|,6] 
    [2,6,16,18,22,27|]
    Result => [2,6,16,18,22,27]
    
## Step by step  

    [22,27,16,2,18,6]
    [22,27,16,2,18,6]
    [22,16,27,2,18,6]
    [16,22,27,2,18,6]  
    [16,22,2,27,18,6]  
    [16,2,22,27,18,6] 
    [2,16,22,27,18,6] 
    [2,16,22,18,27,6] 
    [2,16,18,22,27,6] 
    [2,16,18,22,6,27] 
    [2,16,18,6,22,27] 
    [2,16,6,18,22,27]
    [2,6,16,18,22,27]
    Result => [2, 6, 16, 18, 22, 27]
    
    
## 2) Big-O

    Worst Case : O(n^2)
    Avarage Case : O(n^2)
    Best Case : O(n)
    
## 3)Time Complexity

## For example, we are looking for 2 in this array. 

    Worst Case : [27,22,18,16,6,2]
    Avarage Case : [6,2,16,18,22,27]
    Best Case : [2,6,16,18,22,27]
    
## 4)Which case would 18 suit after the array is sorted? 

    Average case because 18 is in the middle of the array.
    
## 5)Insertion sort of [7,3,5,8,2,9,4,15,6] only first 4 steps. 
                                                                       
    [7|,3,5,8,2,9,4,15,6]
    [3,7|,5,8,2,9,4,15,6]
    [3,5,7|,8,2,9,4,15,6]
    [3,5,7,8|,2,9,4,15,6]
      
 # Merge Sort

    Merge sort of [16,21,11,8,12,22] 

    [16,21,11,8,12,22]
    [16,21,11] [8,12,22]
    [16,21] [11] [8] [12,22]
    [16] [21] [11] [8] [12] [22] 
    [16,21] [11] [8] [12,22]
    [11,16,21] [8,12,22]
    [8,11,12,16,21,22]
    
## 2) Big-O

    O(nlog(n))
    
 # Binary Search Tree
## 1) [7,3,5,8,2,9,4,15,6] convert this array into a binary search tree and write the steps. 
    - The root is 7 because it's at the beginning of the series.
    - 5 is written to the left of 7 because it is less than 7.
    - 1 is written to the left of 5 because it is less than 7 and 5.
    - 8 is written to the right of 7 because it is greater than 7.
    - 3 is written to the right of 1 because it is less than 7 and 5 but greater than 1.
    - 6 is written to the right of 5 because it is less than 7 but greater than 5.
    - 0 is written to the left of 1 because it is less than 7, 5 and 1.
    - 9 is written to the right of 8 because it is greater than 7 and 8.
    - 4 is written to the right of 3 because it is less than 7 and 5 but greater than 1 and 3.
    - 2 is written to the left of 3 because it is less than 7, 5, 3 but greater than 1.

![](binaryTree.PNG) 
