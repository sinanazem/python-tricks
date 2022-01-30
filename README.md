# Python Tricks


<img src="https://www.inspiredpython.com/favicon.svg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" height=350 width=500 />
     
     
### 1. Slices     
 ```    
 s = slice(3,6)
list_ = [1, 3, 'a', 'b', 5, 11, 16]
text = 'DataScience'
tuple_ = (1,2,3,4,5,6,7)
print(list_[s])
print(text[s])
print(tuple_[s])
``` 

### 2.Sorting a list of lists
```
lst = [[2, 7], [7, 3], [3, 8], [8, 7], [9, 7], [4, 9]]

lst.sort(key = lambda inner:inner[1])
print(lst)

lst.sort(key = lambda inner:inner[0])
print(lst)
```

### 3.Merging two Dictionaries
```
# Python code to merge dict using a single
# expression
def Merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res
     
# Driver code
dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}
dict3 = Merge(dict1, dict2)
print(dict3)
```

### 4.Underline utilization in integer
```
num1 = 100_000_000
num2 = 12_003_420_005
total = num1 + num2
print(f'{total: ,}')
```

### 5.Library for opening each websites
``` 
import webbrowser
webbrowser.open('https://www.hejazizo.com/')
```
