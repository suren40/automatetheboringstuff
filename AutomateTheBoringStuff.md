
# AUTOMATE THE BORING STUFF WITH PYTHON
This note contains everything related to above book. I am learning python using the video 
version of this book.

#### INSTALLATION
[DOWNLOAD LINK](https://www.python.org/downloads/)
* Try to use python3

---

#### QUICK NOTES
It's necessary to use stackoverflow if code is not working.
Here are some points to follow while wanting for help.
* Specify whole thing what are you trying to do not only what I did.
* Use the pastebin.com or gist.github.com for pasting the whole code
* Specifie the point where we get error message.




## EXPRESSION, DATATYPE, STATEMENTS,VARIABLES
----
### POINT TO BE NOTED
* If there is evaluation that is called **Expression** if no evaluation only **Statement**
* The term **Variable** is actually **ObjectReference** So try to use OR.



```python
2 + 3

```




    5



###### DATATYPE
Remember they are represented as class int,float,str,bool so we can use the variable as object hence we can inherite the 
function.

* INTEGER(int)
* FLOATING (float)
* STRING(str)
* BOOLEAN(bool)


### INTEGER
AS NAME SUGGEST


```python
num = 20
num2 = -30
sum = num + num2
print(sum)
type(sum)
type(-30)


```

    -10
    




    int



##  FLOATING


```python
num = 30.25
num2 = 31.6
sum = num + num2
print(sum)
type(sum)
```

    61.85
    




    float



# STRING


```python
NAME = 'SURENDRA '
SNAME = 'TAMANG'
FNAME = NAME + SNAME
print(FNAME)
print(type(FNAME))

```

    SURENDRA TAMANG
    <class 'str'>
    

## BOOLEAN
*Note  Use first letter Capital while using boolean e.g False or True*
* It only has two values 




```python
condition = False
condition2 = True
if condition2:
    print(type(condition))
```

    <class 'bool'>
    

## Program1
Asking for the name and age and print it



```python
# This is the first program
userName = input("Enter your Name ")
userAge = input("Enter your age ")
print(f'Hello {userName}. \n Nice to meet you!. You will be {int(userAge)+1} in a year.')
```

    Enter your Name Surendra Tamang
    Enter your age 22
    Hello Surendra Tamang. 
     Nice to meet you!. You will be 23 in a year.
    

## FLOW CONTROL

### COMPARISON OPERATOR
PYTHON HAS 6 COMPARISON OPERATOR

| Comparison Operator | Meaning  |
| --- |:-----:|
| == | Equal to |
| != | Not Equal to|
| < | Less than|
| > | Greater than|
| =< | Less or equal to|
| => | Greater or equal to|

* Always Compare with left.




```python
print(42 == '42')
print(43 != 42)

```

    False
    True
    

### BOOLEAN OPERATORS
* and 
* or
* not
#### Follow the truth table.



```python
print(True and False)
print(True or True)
print(not True)
# Not operator is use in only one bool.


```

    False
    True
    False
    

## IF, ELIF AND ELSE STATEMENT
#### POINT TO BE NOTED
* : is indentation which will to seperate the function 
* Inside the function we use next statement which using tab.
* Every statements inside the function are called block
* blank space in **if** are false and other are true


```python
if '':
    print('Hello '+ '!'*5)
```


```python
if 'Not Blank space':
    print('Hello '+ '!'*5)
```

    Hello !!!!!
    


```python
bool(0)
```




    False




```python
bool(1333)
```




    True




```python
bool(0.0555)
```




    True




```python
bool(2-2)
```




    False




```python
bool('')
```




    False




```python
bool('Not_blank')
```




    True




```python
name = 'surendra'
if name == 'Surendra':
    print('printFirst')
elif name == 'Surendra':
    print('printSecond')
else:
    print('Print Last')
```

    Print Last
    


```python
name = 'surendra'
if name == 'Surendra':
    print('printFirst')
    # using the lower fuction on the string object
elif name == 'Surendra'.lower():
    print('printSecond')
else:
    print('Print Last')
```

    printSecond
    

### WHILE LOOP
Printing the file until the condition true
* It is used for iteration purpose.



```python
spam = 1
while spam < 5:
    print(f'{spam} is repeated!' )
    spam +=1
```

    1 is repeated!
    2 is repeated!
    3 is repeated!
    4 is repeated!
    

**EXAMPLE OF WHILE**


```python
name = 'surendra'
ans = ''
while ans != name:
    ans = input('Enter your name? ')
print('Thank You! for your visit')
```

    Enter your name? surendra
    Thank You! for your visit
    

### Use of break, pass, continue
* break --> It will break the loop.
* pass--> It will pass with no any statement
* continue --> It will neglect the below statement  and jumps back to the condition and recheck the condition.

## FOR LOOP
-- It is use for the fixed repetitive task.


```python
num = 0
for num in range(1):
    print(num)
```


```python
for i  in [1,2,3]:
    print(i)
```


```python

```


```python

```


```python

```


```python

```
