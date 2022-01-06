```python
List=[]
print("blank list")
print(list)
```

    blank list
    <class 'list'>
    


```python
List=[10,30,40,50,'hy',]
print("\n list number")
print(List)
```

    
     list number
    [10, 30, 40, 50, 'hy']
    


```python
List=[10,30,40,50,]
print("\n list number")
print(List)
```

    
     list number
    [10, 30, 40, 50]
    


```python
List=['happy','im','hello','hy',]
print("\n list number")
print(List)
```

    
     list number
    ['happy', 'im', 'hello', 'hy']
    


```python
List=[10,30,40,50,['happy']]
print("\n list number")
print(List)
```

    
     list number
    [10, 30, 40, 50, ['happy']]
    


```python
list=['p','t','u','k','f']
print(list[2])
print(list[-2])
```

    u
    k
    


```python
my_list=['p','k','d','g','l']
print(my_list[-1])
print(my_list[-3])
```

    l
    d
    


```python
marks=[60,90,80]
print(marks)
```

    [60, 90, 80]
    


```python
marks[1]=100
print(marks)
```

    [60, 100, 80]
    


```python
marks.append(50)
print(marks)
```

    [60, 100, 80, 50]
    


```python
marks.extend([60,80,30])
print(marks)
```

    [60, 100, 80, 50, 60, 80, 30, 60, 80, 30]
    


```python
marks.insert(2,60)
print(marks)
```

    [60, 100, 60, 80, 50, 60, 80, 30, 60, 80, 30]
    


```python
print(marks)
```

    [60, 100, 60, 80, 50, 60, 80, 30, 60, 80, 30]
    


```python
marks=[10,20,30,40,50,60]
print(marks)
```

    [10, 20, 30, 40, 50, 60]
    


```python
del marks[4]
print(marks)
```

    [10, 20, 30, 40, 60]
    


```python
marks.clear()
print(marks)
```

    []
    


```python
marks=[20,40,60]
marks.remove(60)
print(marks)
```

    [20, 40]
    


```python
marks.pop()
```




    40




```python
print(marks)
```

    [20]
    


```python
list=['y','p','k','t']
print(list[0:4])
```

    ['y', 'p', 'k', 't']
    


```python
print(list[-2:-1])
```

    ['k']
    


```python
list=["hi","heloo"]
print('oldlist:',list)
list.append("welcome")
print('list:',list)
```

    oldlist: ['hi', 'heloo']
    list: ['hi', 'heloo', 'welcome']
    


```python
list=['hi','hello']
print('old list:',list)
list1=['welcome']
list.append(list1)
print('updated list:',list)
```

    old list: ['hi', 'hello']
    updated list: ['hi', 'hello', ['welcome']]
    


```python
list=['h','i','k','l','p','!']
print('The count of i is:',list.count('k'))
print('The count of i is:',list.count('l'))

```

    The count of i is: 1
    The count of i is: 1
    


```python
list=['a',('k','i'),('a','b'),[8,4]]
count=list.count(('a','b'))
print("The count of('a','b')is:",count)
count=list.count([3,4])
print("The count of[3,4]is:",count)
```

    The count of('a','b')is: 1
    The count of[3,4]is: 0
    


```python
language=['c','c++','python']
language1=['java','COBOL']
language.extend(language1)
print('language list:',language)
```

    language list: ['c', 'c++', 'python', 'java', 'COBOL']
    


```python
language=['c','c++','python']
language_tuple=['JAVA','COBOL']
language_set={'Net','c##'}
language.extend(language_tuple)
print('New language list:',language)
language.extend(language_set)
print('Newest language list:',language)
```

    New language list: ['c', 'c++', 'python', 'JAVA', 'COBOL']
    Newest language list: ['c', 'c++', 'python', 'JAVA', 'COBOL', 'Net', 'c##']
    


```python
list=['k','h','k','l','g','e']
print('The count of i is:',list.index('k'))
print('The count of e is:',list.index('e'))
print('The count of z is:',list.index('z'))
```

    The count of i is: 0
    The count of e is: 5
    


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    ~\AppData\Local\Temp/ipykernel_14972/543633304.py in <module>
          2 print('The count of i is:',list.index('k'))
          3 print('The count of e is:',list.index('e'))
    ----> 4 print('The count of z is:',list.index('z'))
    

    ValueError: 'z' is not in list



```python
vowels=['a','i','o','u']
print("old list=",vowels)
vowels.insert(1,'e')
print("new list=",vowels)
```

    old list= ['a', 'i', 'o', 'u']
    new list= ['a', 'e', 'i', 'o', 'u']
    


```python
list = [{1,2},[5,6,7]]
print('old List:',list)
number_tuple = (3,4)
list.insert(1,number_tuple)
print('updated list:',list)
```

    old List: [{1, 2}, [5, 6, 7]]
    updated list: [{1, 2}, (3, 4), [5, 6, 7]]
    


```python
list=['python','java','C++','french','c']
return_value=list.pop(3)
print('return value:',return_value)
print('updated list:',list)
```

    return value: french
    updated list: ['python', 'java', 'C++', 'c']
    


```python
language=['python','java','c++','c']
print('return value:',language.pop())
print('updated list:',language)
print('return value:',language.pop(-1))
print('updated list:',language)
```

    return value: c
    updated list: ['python', 'java', 'c++']
    return value: c++
    updated list: ['python', 'java']
    


```python
old_list=[1,2,3]
new_list=old_list
new_list.append('a')
print('new list:',new_list)
print('old list:',old_list)
```

    new list: [1, 2, 3, 'a']
    old list: [1, 2, 3, 'a']
    


```python
list=[1,2,3,4]
new_list = list[:]
new_list.append(5)
print('old list:',list)
print('new list:',new_list)
```

    old list: [1, 2, 3, 4]
    new list: [1, 2, 3, 4, 5]
    


```python
list=[3,4,5,6,7,8,9]
print('original list:',list)
list.remove(4)
print('updated list elements:',list)
```

    original list: [3, 4, 5, 6, 7, 8, 9]
    updated list elements: [3, 5, 6, 7, 8, 9]
    


```python
list=[1,2,3,4,5,6]
print('original list:',list)
reversed_list=list[::-1]
print('reversed list:',reversed_list)
```

    original list: [1, 2, 3, 4, 5, 6]
    reversed list: [6, 5, 4, 3, 2, 1]
    


```python
list=[1,2,3,4,5,6,7]
print('original list:',list)
list.reverse()
print('reversed list:',list)
```

    original list: [1, 2, 3, 4, 5, 6, 7]
    reversed list: [7, 6, 5, 4, 3, 2, 1]
    


```python
list=[1,8,2,9,4,10,6]
print('original list:',list)
list.sort()
print('sorted list:',list)
```

    original list: [1, 8, 2, 9, 4, 10, 6]
    sorted list: [1, 2, 4, 6, 8, 9, 10]
    


```python
list=[1,2,3,4,5,6,7]
print('original list:',list)
list.sort(reverse=True)
print('sorted list:',list)
```

    original list: [1, 2, 3, 4, 5, 6, 7]
    sorted list: [7, 6, 5, 4, 3, 2, 1]
    


```python
list=[2,3,4,5,7,6,7]
all(list)
```




    True




```python
list=[2,3,4,5,7,6,7]
any(list)
```




    True




```python
list=[2,3,4,5,7,6,7]
enumerate(list)
```




    <enumerate at 0x22a4615a700>




```python
list=[1,2,3,4,7]
print("length of list:",len(list))
```

    length of list: 5
    


```python
list=[1,2,3,4,7]
print("sum of list:",sum(list))
```

    sum of list: 17
    


```python
list=[1,2,3,4,7]
print("sorted of list:",sorted(list))
```

    sorted of list: [1, 2, 3, 4, 7]
    


```python
list=[1,2,3,4,7]
print("largest number is:",max(list))
print("smallest number is:",min(list))
```

    largest number is: 7
    smallest number is: 1
    


```python
list=[1,2,3,4,7]
print("list of list:",list(list))
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    ~\AppData\Local\Temp/ipykernel_14972/1091602959.py in <module>
          1 list=[1,2,3,4,7]
    ----> 2 print("list of list:",list(list))
    

    TypeError: 'list' object is not callable



```python

```
