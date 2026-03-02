##### 🟢 LEVEL 0 — FOUNDATION (Must Do First)

##### 🔹 Arrays (10 Questions)

##### 

1. ##### Find sum of array
2. ##### Find maximum and minimum element
3. ##### Count even and odd numbers
4. ##### Reverse an array
5. ##### Check if array is sorted
6. ##### Find second largest element

##### 

##### 🔹 Strings (10 Questions)

##### 

1. ##### Print each character
2. ##### Reverse a string
3. ##### Check palindrome
4. ##### Count vowels and consonants
5. ##### Convert lowercase to uppercase manually
6. ##### Remove spaces
7. ##### Count frequency of characters
8. ##### Compare two strings
9. ##### Check if string contains substring
10. ##### Find length without using built-in method

##### 

##### 🟡 LEVEL 1 — BASIC INTERVIEW LEVEL

##### 🔹 Arrays (15 Questions)



1. ##### Two Sum (Brute Force)
2. ##### Move all zeros to end
3. ##### Remove duplicates from sorted array
4. ##### Rotate array by 1
5. ##### Rotate array by k
6. ##### Majority element (Brute)
7. ##### Best Time to Buy and Sell Stock
8. ##### Merge two sorted arrays
9. ##### Find missing number (0 to n)
10. ##### Intersection of two arrays
11. ##### Union of two arrays
12. ##### Check if array is palindrome









1. ##### Sort array of 0s and 1
2. ##### Leaders in array
3. ##### Find duplicate number

##### 

##### 🔹 Strings (15 Questions)

1. ##### 
2. ##### Valid palindrome (ignore special chars)
3. ##### Valid anagram
4. ##### Longest common prefix
5. ##### Reverse words in a string
6. ##### Check rotation of string
7. ##### String compression
8. ##### First non-repeating character
9. ##### Valid parentheses
10. ##### Count substrings
11. ##### Check isomorphic strings
12. ##### Roman to integer
13. ##### Integer to Roman
14. ##### Remove duplicates
15. ##### Group anagrams
16. ##### Count and say

##### 

##### 🟠 LEVEL 2 — STRONG INTERMEDIATE

##### 🔹 Arrays (15 Questions)



1. ##### Maximum subarray (Kadane)
2. ##### Subarray sum equals k
3. ##### Longest consecutive sequence
4. ##### 3Sum
5. ##### Container with most water
6. ##### Product of array except self
7. ##### Set matrix zeroes
8. ##### Merge intervals
9. ##### Find peak element
10. ##### Search in rotated sorted array
11. ##### Next permutation
12. ##### Rearrange array by sign
13. ##### Find all duplicates
14. ##### Trapping rain water
15. ##### Gas station problem

##### 

##### 🔹 Strings (15 Questions)



1. ##### Longest substring without repeating characters
2. ##### Minimum window substring
3. ##### Longest palindromic substring
4. ##### Palindromic substrings count
5. ##### Decode string
6. ##### Multiply strings
7. ##### Compare version numbers
8. ##### Simplify path
9. ##### Implement strStr()
10. ##### Z-function / pattern matching basic
11. ##### Reorganize string
12. ##### Partition labels
13. ##### Word pattern
14. ##### Add binary
15. ##### Basic calculator

##### 

##### 🔵 LEVEL 3 — ADVANCED INTERVIEW

##### 🔹 Arrays

##### 

1. ##### Subarrays divisible by k
2. ##### Maximum product subarray
3. ##### Sliding window maximum
4. ##### Largest rectangle in histogram
5. ##### Max points on a line
6. ##### Candy problem
7. ##### Jump game
8. ##### Jump game II

##### 

##### 🔹 Strings



1. ##### Word break
2. ##### Text justification
3. ##### Edit distance
4. ##### Wildcard matching
5. ##### Regular expression matching

##### 

##### 🔴 LEVEL 4 — FAANG HARD

##### 

##### These are optional but powerful:

##### 

##### Arrays

##### 

1. ##### Median of two sorted arrays
2. ##### Count of smaller numbers after self
3. ##### Reverse pairs

##### 

##### Strings

##### 

1. ##### Minimum insertion to form palindrome
2. ##### Shortest palindrome
3. ##### Scramble string









❓ Why do we use StringBuilder here?



Because in Java:



String is immutable.



That means once a string is created, it cannot be changed.



🔴 What happens if we use normal String?



If you write:



result = result + ch;



Every time this runs:



A new String object is created



Old string is copied



New character is added



Old object is discarded



So if your string has 1000 characters:



👉 It creates 1000 new objects 😱

👉 Very slow

👉 Memory waste



Time complexity becomes:



O(n²)

🟢 What StringBuilder Does



StringBuilder is mutable.



That means:



It modifies the same object



No new object creation every time



Much faster



result.append(ch);



It simply adds the character inside the same memory.



Time complexity:



O(n)



