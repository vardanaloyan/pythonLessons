# Lists

- Mutable data structure

```python
lst = [1, 2, 3, 4]
other_list = [1, 2, "three"]
>>> lst[0]
1
>>> lst[-1]
4
>>> other_list[1]
2
>>> other_list[2]
'three'
>>> other_list[2][0]
't'
>>> other_list[1][0]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'int' object is not subscriptable
```

# Useful methods

- append

```python
>>> lst = [1, 2, 3, 4]
>>> lst.append("Hello")  # Add "Hello" string to the list
>>> lst
[1, 2, 3, 4, 'Hello']
>>>
>>> lst.pop()  # Return and Delete last item
'Hello'
>>> lst
[1, 2, 3, 4]  # List has been mutated
>>>
>>> lst.pop(2) # Return and Delete item in index 2
3
>>> lst
[1, 2, 4]
>>> del lst[-1]  # remove item
>>> lst
[1, 2]
>>> for i in lst:
...     print(i)
... 
1
2
>>> 
```

# Dictionary

- Mutable data structure
- In other languages they are also called mapping

```python
# Key value pairs
>>> dct={
... 97: "a",
... 98: "b",
... 99: "c",
... }  # Create dict
>>> dct  # See a dict
{97: 'a', 98: 'b', 99: 'c'}
>>> dct[97]  # Get value for key 97
'a'
>>> dct[98]  # Get value for key 98
'b'
>>> dct[99]  # Get value for key 99
'c'
>>>
>>> dct[100]="d"  # Add an item into a dict
>>> dct
{97: 'a', 98: 'b', 99: 'c', 100: 'd'}
>>> del dct[97]  # Delete an item from the dict
>>> dct
{98: 'b', 99: 'c', 100: 'd'}
```

