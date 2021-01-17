# data-structure-in-python


Accessing elements from a tuple:- 
# Accessing tuple elements using indexing
my_tuple = ('p','e','r','m','i','t')

print(my_tuple[0])   # 'p' 
print(my_tuple[5])   # 't'

# IndexError: list index out of range
# print(my_tuple[6])

# Index must be an integer
# TypeError: list indices must be integers, not float
# my_tuple[2.0]

# nested tuple
n_tuple = ("mouse", [8, 4, 6], (1, 2, 3))

# nested index
print(n_tuple[0][3])       # 's'
print(n_tuple[1][1])       # 4

Output:- 
p
t
s
4

Deleting  different dictionary elements :- 


key_to_be_deleted = 'this'
# As 'this' key is present in dict, so pop() will delete
# its entry and return its value
result = word_freq_dict.pop(key_to_be_deleted, None)
print("Deleted item's value = ", result)
print("Updated Dictionary :", word_freq_dict)

Output:-
Deleted item's value =  43
Updated Dictionary : {'Hello': 56, 'at': 23, 'test': 43}
