# Analysis
## Problem 1
Data Structure used- **Ordered Dictionary** from Collections 
In Ordered Dictionary, key value pair can be stored since it is a dictionary and the ordered in which the items are insert matters. Here a popitem() method is used to put an item when the cache is full. 
Popitem takes an argument last which when set to false act as FIFO.
###### Time Complexity
Getting an element- It takes **O(1)** complexity since we can access the value directly using key 
Inserting an element- It also takes **O(1)** because it is inserted directly in a dictionary.
###### Space Complexity
Space complexity is **O(n)** where n is the capacity of cache memory.
## Problem 2
In this problem, I iterate through all the files and directory in the root directory. If it files, then we append to a files list and if it a directory then it used recursion to go through that directory again.

###### Time Complexity
Time complexity is **O(d+f)** where d is the total directory present and f is the total number of files present
###### Space Complexity
Space Complexity is **O(n)** where n is the total number of files present ending with the suffix given.
## Problem 3
The problem of Huffman Encoding was solve using different classes like
1.	Node
2.	Queue
3.	Tree
4.	HuffmanEncoder
###### Time complexity
The time complexity would be **O(Ln)**, being L the maximum length of a data. If I had not used a built it functions for sorting the input that takes O(n*log(n)); ending up the time complexity being O(n*log(n)). 
###### Space Complexity
The space complexity is **O(k)**  where k is the size of the employed alphabet.
## Problem 4
In this, user is first search in the users list of the given group. If not present, then we recursively go through the subgroup of that group and check for the user
###### Time Complexity
Worst Case Time Complexity would be **O(u*g)** where u is the lists of users and g is the lists of groups. It is O(u*g) because if the users Is not present, we have to go through all the users list and all the group list
###### Space Complexity
Space complexity is also **O(u*g)** for storing list of users and list of groups
## Problem 5
This problem is solved with concept of linked list. I have included some methods for Blockchain-
- Append
-	Search
-	Size
-	To_list

###### Time Complexity
The complexity for the various method implemented are given below-
-	Append: O(1)
-	Search: O(n)
-	Size: O(n)
-	To_list: O(n)

###### Space Complexity
The space complexity of the blockchain depending on the number of block that is created due to inserting of data. So, it is **O(n)**.
## Problem 6
For this problem, for both union and intersection, I converted the linked list into list for simpler operation. 
###### Time Complexity
-	Union- Time complexity is O(n) for concatenation operator where n is the size of the concatenated list
-	Intersection- Time complexity is **O(n*n)** considering O(n) for checking if an element is present in another list.
###### Space Complexity
Space complexity is **O(n)**


