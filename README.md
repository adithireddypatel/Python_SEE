# Answers to question number 5 - Python SEE

5a. An input that does not produce the correct answer is:

data1 = {2:20, 3:30, 5:50, 7:70}
data2 = [[2,20], [9,90], [3,30], [5,50], [7,70]]

Key from data2 is not present in data1

5b. This error has been fixed in the code committed to the given repository by changing the indentation of the given code. 

5c. Here are some test cases for the above code:

i. data1 = {2:20, 3:30, 5:50, 7:70}
data2 = [[2,20], [9,90], [3,30], [5,50], [7,70]]
Here data1 has a key missing that exists in data2

ii. data1 = {1:10, 2:20, 3:30, 4:40, 5:50}
data2 = [[1,10], [3,30], [4,40], [5,50]]
Here data2 has a key missing that exists in data1

iii. data1 = {1:10, 2:21, 3:30, 4:40, 5:50}
data2 = [[1,10], [2,20], [3,30], [4,40], [5,50]]
Here data1 has a different value for a key that it shares with data2.
