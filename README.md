# unit_3-discussion

Unit 3 Discussion: List Operations
Overview
This assignment examines insertion, deletion, and searching in Python lists.

Learning Objectives
Insert values into a list
Delete values from a list
Search for values in a list
Analyze list behavior and performance
Requirements
Test insertion at the beginning, middle, and end.
Test deletion at the beginning, middle, and end.
Search for existing and missing values.
Demonstrate edge cases.
Create a real-world scenario.
Discussion Board Reflection
Add your reflection to your initial post on the discussion board in LEO.

Your reflection should be approximately 150–200 words and address the following questions:

What concepts or skills did you learn while completing this assignment?
What challenges did you encounter, and how did you overcome them?
How do list operations impact performance in real-world applications?
Implementation
I implemented an ordered service-desk ticket list. This included implementing the insert_at function using the insert() method, the delete_at function using index validation and the pop() method, and the search_value function using a sequential loop. I left the TODO prompts and comments as is, and added my own implementation comments below them.

For the deletion operations I used nonnegative integer indexes, returning None for invalid indexes and not modifying the list. For the searches I returned the first index matching the search value, or -1 if no value was found. For the insertion operations I used Python’s built-in insert() method, so for example if the index given was greater than the length of the list then it would be clamped to the end of the list.

Running the program
python unit3_discussion.py
I ran the program multiple times to verify that all list operations worked correctly. The output confirmed that insertion at the beginning, middle, and end of the list updated the list as expected. I also tested deletion and search operations, including edge cases such as invalid indexes and empty lists. The results showed that the program handled each scenario correctly and produced the expected output.

Performance

For this assignment, I created a Python program that demonstrates different list operations, including inserting, deleting, and searching for values. I tested adding elements at the beginning, middle, and end of a list to observe how the positions of existing elements changed after each insertion. I also removed elements from different locations and verified that the list updated correctly after each deletion. In addition, I searched for both existing and missing values to demonstrate successful and unsuccessful search operations. I tested several edge cases, including deleting from an empty list, searching an empty list, and using invalid indexes. For my real-world example, I used a student course schedule where courses can be added, removed, and searched. This assignment showed how lists can be used to organize and manage data efficiently in everyday situations.

Reflection

Completing this assignment helped me gain a better understanding of how Python lists work and how different operations impact performance. I learned that when an element is inserted or removed, Python may need to shift other elements in the list, which can affect efficiency depending on where the operation occurs. One challenge I faced was keeping track of index positions after multiple insertions and deletions because the list changed throughout the program. I overcame this challenge by testing each operation step by step and reviewing the output carefully after every change. I also learned the importance of validating indexes before deleting items and handling edge cases to prevent errors. Understanding list operations is valuable because lists are commonly used in many real-world applications such as course registration systems, online shopping carts, playlists, and social media feeds. As applications grow larger, choosing efficient data structures becomes increasingly important for performance and usability.
