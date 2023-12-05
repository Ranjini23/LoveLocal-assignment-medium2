# LoveLocal-assignment-medium2
Given an integer array of size n, find all elements that appear more than ⌊ n/3 ⌋ times.

defines a function majority_elements that finds elements that appear more than ⌊n/3⌋ times in a given list of integers, where n is the length of the list.

step 1 -> Function Definition: defining the function named majority_elements that takes a list of integers(nums) as its input.

step 2 -> Handling Empty List: Checks if the input list nums is empty. If so, it returns an empty list.

step 3 -> Initialization of Candidates and Counts: Initializes two candidate elements (candidate1 and candidate2) and their corresponding counts (count1 and count2).

step 4 -> Finding Candidates: Iterates through the input list nums and updates the candidates and counts based on certain conditions.

step 5 ->Counting Candidates: Counts the occurrences of the two candidates in the original list.

step 6 -> Checking Majority Elements: Checks if the counts of the candidates exceed ⌊n/3⌋, and if so, adds them to the result list.

step 7 -> Taking User Input and Printing Result: Takes user input for the number of elements and the list of numbers, calls the majority_elements function with the provided list, and prints the result.

Example 1:

Input: nums = [3,2,3]

Output: [3]

Example 2:

Input: nums = [1]

Output: [1]

Example 3:

Input: nums = [1,2]

Output: [1,2]
