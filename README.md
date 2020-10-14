# LearnPython

print only to be used with paranthesis  , also include new line at end "\n" 

print("hello") similar to cout<<"hello\n" ;

using + in print appends two strings whereas "," adds space between two strings

print("hello"+"world") -> helloworld

print("hello","world") -> hello world

## if statement

```python
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```
Python supports two types of numbers - integers and floating point numbers

```python
myfloat = 7.0
print(myfloat)
myfloat = float(7)
print(myfloat)
```

outputs 7.0
        7.0
    
 Strings are defined either with a single quote or a double quotes
 
 The difference between the two is that using double quotes makes it easy to include apostrophes (whereas these would terminate the string if using single quotes)
        
Assignments can be done on more than one variable "simultaneously" on the same line like this

a, b = 3, 4
print(a,b)


## Lists 

```python
mylist = []
mylist.append(1)
mylist.append(2)
mylist.append(3)
print(mylist[0]) # prints 1
print(mylist[1]) # prints 2
print(mylist[2]) # prints 3

# prints out 1,2,3
for x in mylist:
    print(x)
```

### error 
mylist = [1,2,3]
print(mylist[10])



