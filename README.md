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
