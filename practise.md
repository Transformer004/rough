

```python
s='I love volleball'
for i in range(0, len(s)):
    print (s[i],end='')
```

    I love volleball


```python
k="pynativepynvepynative"
d3={}
for i in k:
    if i in d3:
        d3[i]=d3[i]+1
    else:
        d3[i]=1
print(d3)
```

    {'p': 3, 'y': 3, 'n': 3, 'a': 2, 't': 2, 'i': 2, 'v': 3, 'e': 3}
    


```python
string=input()
sub_string=input()
count=0
def count_substring(string, sub_string):
    if sub_string in string:
        count=count+1
    
    return(count)



count_substring(string, sub_string) 
```


```python
S=input()
if S.isalnum()==True:
    print(True)
else:
    print(False)
if S.isalpha()==True:
    print(True)
else:
    print(False)
if S.isdigit()==True:
    print(True)
else:
    print(False)
if S.islower()==True:
    print(True)
else:
    print(False)
if S.isupper()==True:
    print(True)
else:
    print(False)
```

    qA2
    True
    False
    False
    False
    False
    


```python
S=input()
for i in len(S.split()):
    if i.isupper()==True:
        print(True)
    else:
        print(False)
```

    qA2
    


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-12-9c0cd43bb1b7> in <module>
          1 S=input()
    ----> 2 for i in len(S.split()):
          3     if i.isupper()==True:
          4         print(True)
          5     else:
    

    TypeError: 'int' object is not iterable



```python

```
