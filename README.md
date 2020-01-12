# Algorithms & Data Structures (with Python)
Reminding myself that all it takes is practice, dedication and hard work. I put this off for too many years ☹️ Here I made this repository to help me keep track of some of the questions / solutions I have done on Leetcode.

### PROBLEMS COMPLETED:
#### Easy:
**24/12**
- [x] [x] 760 Find Anagram Mappings (redid 11/01 improved)
- [x] [x] [ ] 1266 Minimum Time Visiting All Points [Solution to study](https://leetcode.com/problems/minimum-time-visiting-all-points/discuss/436317/python-3-Easy-peasy-lemon-squeezy) (redid 11/01 - no improvement)
- [x] [x] 1221 Split a String in Balanced Strings (redid 11/01 improved!!) (redo again)
- [x] [x] 1119 Remove Vowels from a String (redid 11/01 and improved)
- [x] [x] 1295 Find Nu  mbers with Even Number of Digits (redid 11/01 and improved)
- [x] [x] 71 Jewels and Stones (redid 11/01 and improved)
- [x] [x] 1290 Convert Binary Number in a Linked List to Integer (redid 11/01 and improved) (however, try bitwise next time)
- [x] [x] 938 Range Sum of BST [Youtube Video Explanation](https://www.youtube.com/watch?v=FMFytleZRWA) (getting better ... but redo again)

**25/12**
- [x] [x] 1252 Cells With Odd Values in a Matrix [https://leetcode.com/problems/cells-with-odd-values-in-a-matrix/discuss/456746/python3-simple-and-memory-saving-solution] (redid 11/01 - improved)
(learn that solution ^ but came up with my own one too)

**30/12**
- [x] [x] 1134 Armstrong Number [Solution to study](https://leetcode.com/problems/armstrong-number/discuss/455073/Python-3-90) and
[Good solution demonstrating use of list comprehensions](https://leetcode.com/problems/armstrong-number/discuss/455393/Python3-One-liner-beats-98) (improved 11/01)
- [x] [x] 1213 Intersection of Two Arrays (redid 11/01 - improved) [try this again with a PQ]

**03/01**
- Think Like a Programmer (V. Anton Spraul) Recursion Problems
- [x] [x] 1086 High Five (improved 11/01 but didn't used the optimal data structure)
- [x] [ ] 1299 Replace Elements with Greatest Element on Right Side
- [x] [ ] 344 Reverse String (easy problem to learn to optimise)
- [x] [ ] 136 Single Number (study XOR bitwise operators and how it works)

**05/01**
- [x] [ ] 412 FizzBuzz
- [x] [ ] 104 Max Depth of Binary Tree
- [x] [ ] 206 Reverse Linked List
- [x] [ ] 237 Delete Node in a Linked List
- [x] [ ] 203 Move Zeroes [Solution to Study](https://leetcode.com/problems/move-zeroes/discuss/391025/2-methods-for-python-simple-code) and study this method too: [Link](https://leetcode.com/problems/move-zeroes/discuss/72012/Python-short-in-place-solution-with-comments)
- [x] [ ] 169 Majority Element [Solution to Study](https://leetcode.com/problems/majority-element/discuss/51712/Python-different-solutions-dictionary-bit-manipulation-sorting-divide-and-conquer-brute-force-etc)
- [x] [ ] 242 Valid Anagram [Solution to Study](https://leetcode.com/problems/valid-anagram/discuss/66499/Python-solutions-(sort-and-dictionary))
- [x] [ ] 217 Contains Duplicate

**06/01**
- [x] [ ] Convert Sorted Array to BST (Redo this everyday until I finally understand it)
- [x] [ ] Roman to Integer
- [x] [ ] Best Time to Buy and Sell Stock II 

**07/01**
- [x] [ ] 171 Excel Sheet Column Number (redo and study all the solutions)
- [x] [ ] 387 First Unique Character in a String (yayyyy)

**08/01**
- [x] [ ] 371 Sum of Two Integers (redo this and understand the Python error handling)

**11/01**
- Redid all problems from 24/12
- Redid all problems from 25/12
- Redid all problems from 30/12
- [x] [ ] 1 Two Sum (remember how to optimise this)
- [x] 125 Valid Palindrome (note that in this version, if there is a space or non-alphanumeric character, you simply ignore it)
- [x] 21 Merge Two Sorted Lists (redo this one) (try and write this recursively and study it) [https://leetcode.com/problems/merge-two-sorted-lists/discuss/472279/Python-Recursive-Solution]

**12/01**
- [ ] 1099 Two Sum Less Than K
- [x] 350 Intersection of Two Arrays II
- Redid Two Sum
- [x] Two Sum II - Input Array is Sorted (redo this with binary search!)
- [ ] Maximum Subarray

#### Medium:
**12/01**
- [ ] 15 3Sum (try this med)

#### Things to do
- Radix Sort
- Counting Sort
- Heap Sort
- Topological sort
- Determine if a string is an int or a double
- Find the shortest palidrome in a string
- Print all permutations of a string
- Find the only element in an array that occurs once (did this multiple times but keep forgetting) (remember bitwise operators always undo each other if they match)
- Permutations
- Backtracking
- Permutations and palindromes
- Iterators in Python
- Graphs


Permutation
#Sample questions
You are given a 7 digit phone number, and you should find all possible letter combinations based on the digit-to-letter mapping on numeric pad and return only the ones that have valid match against a given dictionary of words.
Give all possible letter combinations from a phone number.
Generate all subsets of a string.
Print all possible N pairs of balanced parentheses.
E.g. when N is 2, the function should print (()) and ()().
E.g. when N is 3, we should get ((())), (()()), (())(), ()(()), ()()().
Source
Given a list of arrays, return a list of arrays, where each array is a combination of one element in each given array.
E.g. If the input is [[1, 2, 3], [4], [5, 6]], the output should be [[1, 4, 5], [1, 4, 6], [2, 4, 5], [2, 4, 6], [3, 4, 5], [3, 4, 6]].

### My Learnings:
- Use % 10 to get the last digit
- Use // 10 to get the whole number without the last digit 
- For the two above points, loop it until != 0 (this is the base case)
- *=2 is same as <<=1 (revise this)
- Use list comprehension with joins
- Use multiple pinters
- Useful to use enumerate function in Python
- Head recursion is where the recursive call comes BEFORE other processing in the function (recursive call happens before the other processing)
- Tail recursion is where the processing occurs BEFORE the recursive call - recursive call is the last step in the function (recursive call is postponed until the end)
- If you set("aabc"), you get {a, b, c} (useful in finding distinct characters) [https://leetcode.com/problems/count-substrings-with-only-one-distinct-letter/]
- Use the functions for dictionarys i.e. .keys() returns the keys in an object e.g. 
        for i in dictionary.keys():
            print(i)
    - Use .get() to get the value of the respective key you are getting
- Make use of being able to traverse Python backwards easily e.g. (len(aList) - 1, -1, -1)
- Make use of XOR and reduce for linear time array questions (bitwise solution) [problem 136]
- Remember you can use XOR (bitwise operators) and with the case of XOR, you can XOr in any order and it will be the same as long as you XOR all the elements.
i.e. a XOR b = b XOR a
(a XOR b) XOR c == a XOR (b XOR c) returns the same thing. Hence if you had [4, 1, 2, 1, 2], 1 XOR 1 will cancel out to 0, 2 XOR 2 will cancel out to 0 and 4 will be the only number left so we know that that is the number that is different. 
- Be careful with Binary Trees: 1) they don't have to be balanced 2) You don't need a while loop to iterate through it if you already are already recursively going through the tree. For this particular question, I only need to check whether the root exists or not: [https://leetcode.com/problems/maximum-depth-of-binary-tree/]
- In a Linked List question, be careful of your loop constraint i.e. while current.next is not None or while current is not None [in reversing a list, we only need to know about the current]
- When asked to delete an entry from a linked list without the head, you CANNOT delete it. You can only copy the values from the next part of the linked list into where it is now (overwrite it)
- Use a lag variable if you have two pointers and need to replace or move something
- Make use of the count function to find how many times something appears
- Remember to use the SET function for questions containing duplicates in an array or similar
- When you have 2 pointers, the base case will usually be when the left crossing the right (recall binary search)
- Use subtraction of ordinal values to find out how far away a character is from a character e.g. to find out how far away you are from A: ord(char) - ord('A) - 1 (instead of creating a dictionary)
- Useful to understand how to use Python Collections (import collections) - collections.Counter literally just builds the dictionary for you
- Use del to delete something from a python dictionary e.g. d = {'a': 1, 'b': 2} --> del['a'] becomes d = {'b': 2}
- Whenever you need to implement an operation without an operator - [BIT SHIFTING](https://www.youtube.com/watch?v=qq64FrA2UXQ) &, ^ and <<
- Generate all, print all, compute all means BACKTRACKING (https://www.youtube.com/watch?v=Zq4upTEaQyM0)
- Make use of swapping e.g. x1, y1 = x2, y2 in questions that involve coordinates. Also with coordinate questions, if you want to maximise movement, you need to max(abs(x2 - x1), abs(y2 - y1))
- If something says "BALANCE this" and you need two things to equal each other, you can just +1 if its L and -1 if its R (one variable plus and minus it instead of keeping track of two variables)
(https://leetcode.com/problems/split-a-string-in-balanced-strings/discuss/403836/C%2B%2BJavaPython-Easy-Solution)
- Much more effective to go through a list with conditions via list comprehensions!!!!
- If it's not a balanced BST, chances are your base case won't be 'if root.left is None and root.right is None'. For unbalanced ones, you usually use 'if root.left' or 'if root.right'
- When you are manipulating something, make sure you save an ORIGINAL COPY OF IT for later if you need it. E.g. when I always do N //=10 and then check whether it works but it doesn't because 
N is now zero (example q: https://leetcode.com/problems/armstrong-number/submissions/)
- If you have a nested list i.e. [[1,91],[1,92],[2,93],[2,97],[1,60],[2,77],[1,65],[1,87],[1,100],[2,100],[2,76]], you can iterate through everything using 'for index, score in items'
- Use dictionary.items() to get the items i.e. dict_items([(1, 'a'), (2, 'b'), (3, 'c')])
- In linked lists, it is useful to make a dummy node so we can return this node at the end (points to the head of the list). Also use CUR to always point to the working head of the list (https://leetcode.com/problems/merge-two-sorted-lists/)
- Using enumerate function is very useful when your dictionary indexing gets complicated (https://leetcode.com/problems/two-sum/discuss/17/Here-is-a-Python-solution-in-O(n)-time - see first comment)
- Be careful of intersection of two arrays (whether they want all occurrences of duplicates or not) - you can use pointers if you sort it!
- get() method for dictionary is useful as if you do not normally, if it does not exist in the dictionary, it will error. However, get() will simply return the value. You can default this to a number e.g. get(value, 0) means if the value doesn't exist in the dictionary, it will simply return 0
You can initialise the dictionary really easily this way
```
nums = [4, 9, 5, 6]
count = {}
for num in nums:
    count[num] = count.get(num, 0) + 1

print(count)
```

#### Struggles with Recursion
Just want to say that this [chapter](https://nostarch.com/download/samples/TLAP_ch6.pdf) really helped.
The first thing about recursion is DO NOT THINK about all the steps in recursion. This is the Big Recursive Idea.
