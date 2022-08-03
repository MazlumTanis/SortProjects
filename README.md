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
      
