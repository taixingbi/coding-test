## Collision Handling
A hash collision occurs when a hash algorithm produces the same hash value for two different input values.

### Chaining
https://www.geeksforgeeks.org/hashing-set-2-separate-chaining/
      
The idea is to make each cell of hash table point to a linked list of records that have same hash function value. Chaining is simple, but requires additional memory outside the table.

Advantages:   
1) Simple to implement.  
2) Hash table never fills up, we can always add more elements to the chain. 
3) Less sensitive to the hash function or load factors. 
4) It is mostly used when it is unknown how many and how frequently keys may be inserted or deleted. 
 
Disadvantages: 
1) Cache performance of chaining is not good as keys are stored using a linked list. Open addressing provides better cache performance as everything is stored in the same table. 
2) Wastage of Space (Some Parts of hash table are never used) 
3) If the chain becomes long, then search time can become O(n) in the worst case. 
4) Uses extra space for links. 

### Open Addressing. 
https://www.geeksforgeeks.org/hashing-set-3-open-addressing/           

In open addressing, all elements are stored in the hash table itself. Each table entry contains either a record or NIL. When searching for an element, we one by one examine table slots until the desired element is found or it is clear that the element is not in the table. 
