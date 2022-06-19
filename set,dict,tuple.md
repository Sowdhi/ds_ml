```python
lis=[1,2,3,4,5,6]
lis.insert(4,10)
print(lis)
```

    [1, 2, 3, 4, 10, 5, 6]
    


```python
set_var={1,2,3,4}
set_var.add
set_var.clear
set_var.copy
set_var.difference
set_var.difference_update
set_var.discard
set_var.intersection
set_var.intersection_update
set_var.isdisjoint
set_var.issubset
set_var.issuperset
set_var.pop
set_var.remove
set_var.symmetric_difference
set_var.symmetric_difference_update
set_var.union
set_var.update
```




    <function set.update>




```python
Sowdhi={10,20,30,"a","mscs",87.4}
Sowdhi
```




    {10, 20, 30, 87.4, 'a', 'mscs'}




```python
Sowdhi.add(40)
Sowdhi
```




    {10, 20, 30, 40, 87.4, 'a', 'mscs'}




```python
Sowdhi.clear()
Sowdhi
```




    set()




```python
a={1,2,3}
```


```python
Sowdhi=a.copy()
print(Sowdhi)
```

    {1, 2, 3}
    


```python

```




    {1, 2, 3}




```python
a={10,20,30,40}
b={30,40,50,60}
b.difference(a)
```




    {50, 60}




```python
a.difference_update(b)
print("a:",a)
```

    a: {40, 10, 20, 30}
    


```python
b.difference_update(a)
print("b:",b)
```

    b: {50, 60}
    


```python
a.discard(40)
a
```




    {10, 20, 30}




```python
a={1,2,3,4,5}
b={4,5,6,7,8}
print(a.intersection(b))

```

    {4, 5}
    


```python
print(a.isdisjoint(b))
```

    False
    


```python
a={4,5,6,7,8,9}
b={4,5,6,7,8}
print(a.isdisjoint(b))
```

    False
    


```python
a={1,2,9}
b={1,2,3,4,5}
print(a.issubset(b))
```

    False
    


```python
print(a.issuperset(b))
```

    True
    


```python
a={3,3,4,5,6,7,8,9,3,4,6}
a
```




    {3, 4, 5, 6, 7, 8, 9}




```python
a.pop()
```




    4




```python

```


```python
print(a)
```

    {3, 12, 4}
    


```python
a={1,2,3,4,5,6,7,8,9}
a.remove(9)
print(a)
```

    {1, 2, 3, 4, 5, 6, 7, 8}
    


```python
a.symmetric_difference(4)
print(a)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Input In [52], in <cell line: 1>()
    ----> 1 a.symmetric_difference(4)
          2 print(a)
    

    TypeError: 'int' object is not iterable



```python
a={3,4,5,7,8,4,3,6,8}
b={2,4,5,6,7,4,3}
print(a.union(b))
```

    {2, 3, 4, 5, 6, 7, 8}
    


```python
a={1,2,3,3}
c={10,20,30}
a.update(c)
print(a)
```

    {1, 2, 3, 20, 10, 30}
    


```python
dict={"b":2"a":1}
dict.clear
dict.copy
dict.fromkeys
dict.get
dict.items
dict.keys
dict.pop
dict.popitem
dict.setdefault
dict.update
dict.values
```


```python
dict.clear
print(dict)
```

    <class 'dict'>
    


```python
dic={"a":1,"b":2,"c":3}
c=dic.copy()
print(c)
```

    {'a': 1, 'b': 2, 'c': 3}
    


```python
a={"abc","b","c"}
value={1,2,3}
numbers=dict.fromkeys(a,value)
print(numbers)
```

    {'abc': {1, 2, 3}, 'c': {1, 2, 3}, 'b': {1, 2, 3}}
    


```python
marks={"maths":10,"phy":20}
print(marks.get("phy"))
```

    20
    


```python
print(marks.pop("phy"))
```

    30
    


```python
print(marks)
```

    {'phy': 20}
    


```python
marks={"maths":10,"phy":20,"stat":30}
```


```python
print(marks.popitem())
```

    ('stat', 30)
    


```python
print(marks.popitem())
```

    ('phy', 20)
    


```python
marks
```




    {'maths': 10}




```python
marks={"maths":10,"stat":20,"phy":30}
a=marks.setdefault("maths")
print(a)
```

    10
    


```python
print(marks)
print(a)
```

    {'maths': 10, 'stat': 20, 'phy': 30}
    10
    


```python
grades={"sridevi":"a","vyshnavi":"b"}
marks.update(grades)
print(marks)
```

    {'maths': 10, 'stat': 20, 'phy': 30, 'sridevi': 'a', 'vyshnavi': 'b'}
    


```python
print(marks.values())
```

    dict_values([10, 20, 30, 'a', 'b'])
    


```python
a=[1,2,2,2,2,2,2,3,"sowdhi"]
a.count(2)
```




    6




```python
a.index(3)
```




    7




```python
type(a)
```




    list




```python

```
