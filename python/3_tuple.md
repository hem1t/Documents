# Tuple in Python

Tuples are designed to store heterogeneous data stored under contiguous memory.

Tuples are immutable and indexed data.

###### Defining Tuple
```python
# Tuple by comma
a = 1, # (1,)
a = 1, 2, "cat" # (1, 2, "cat")

# Using iterables
tuple([1, 2, "cat"]) # (1, 2, "cat")
tuple("cat") # ('c', 'a', 't')

# Functions return tuple using comma
def house_address():
    return "Quiet Villa", 12, "Street", "Rd"

house_address() # ("Quiet Villa", 12, "Street", "Rd")
```


<!--  LocalWords:  Tuple Tuples
 -->
