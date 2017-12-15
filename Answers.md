Tiffany Robbins
    What are the order of insertions/removals for the following data structures?
        Stack-last in first out
        Queue-first in first out
    
    What is the retreival time complexity for the following data structures?
        Linked List-Inserting and deleting done at the head at O(1). But if anywhere else inserting/deleting is done at O(n) because the list is transversed linerally. Searching is done at O(n).
        Hash Table- Inserting and deleting is at O(1) amortized.  Re-size/hashed is at O(n).   
     Binary Search Trees-With Binary search trees the program travels from root to the deapest leaf node. The height lends itself into the search and instert.  This might be represented as O(n).  The search and inserting is represented as O(h) where h equals height as a worst case scenario.  

    What are some advantages to using a Hash Tables over an array in JavaScript?
Hash tables have a faster search time  than arrays.  With arrays unless it is sorted, the program has  to search multiple values to find what its looking for.
With hash tables because you know the value when it was inserted  the program can generate where it will be.  Even if multiple values are in the same bucket there aren't as many values to be searched than what would be in an array 