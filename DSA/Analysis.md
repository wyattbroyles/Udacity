## Task0

**Description**: The problem involves finding the first record of texts and the last record of calls. 

**Approach**: Printed the 0th iteration of teh texts array to find the first text record. Printed the last iteration of the calls array using len() - 1 to find the last call record.

**Complexity Analysis**:
- **Algorithm**: Two print statements 
- **Big O Notation**: $O(n)$ where $n$ is the number of elements in each list
- **Justification**: Each element is accessed once; hence, the time complexity is directly proportional to the list size.

## Task1

**Description**: The problem involves finding the unique number of telephone numbers in the records

**Approach**: Iterated through the calls and texts list to add each number to one set of numbers

**Complexity Analysis**:
- **Algorithm**: Two for loops that run through each element of each list once.
- **Big O Notation**: $O(n + m)$ where $n$ is the number of elements in the calls list and $m$ is the number of elements in the texts array.
- **Justification**: Each element is accessed once; hence, the time complexity is directly proportional to both list sizes.

## Task2

**Description**: The problem involves finding the telephone number that has spent the longest time on the phone.

**Approach**: Iterated through the calls array while performing logic to find the largest number of seconds spent on the phone

**Complexity Analysis**:
- **Algorithm**: A single loop runs through each element of the array once.
- **Big O Notation**: $O(n)$ where $n$ is the number of elements in the array.
- **Justification**: Each element is accessed once; hence, the time complexity is directly proportional to the array size.

## Task3

**Description**: The problem involves finding all of the area codes and mobile prefixes called by people in Bangalore as well as finding the percentage of calls where the caller and receiver are both located in Bangalore.

**Approach**: Iterated through the calls list while performing logic to find numbers with 080 prefixes .

**Complexity Analysis**:
- **Algorithm**: One for loop runs the main logic, and another for loop prints each line
- **Big O Notation**: $O(n)$ where $n$ is the number of elements in the array.
- **Justification**: Each element is accessed once; hence, the time complexity is directly proportional to the array size.

## Task4

**Description**: The problem involves finding telephone numbers that are possibly telemarketers.
**Approach**: Iterated through both lists a single time to perform logic to single out telemarketer numbers.

**Complexity Analysis**:
- **Algorithm**: One for loop runs through each element of the calls array once and one for loop runs through each element of the texts array once.
- **Big O Notation**: $O(n + m)$ where $n$ is the number of elements in the calls list and $m$ is the number of elements in the texts list.
- **Justification**: Each element is accessed once; hence, the time complexity is directly proportional to the list sizes.