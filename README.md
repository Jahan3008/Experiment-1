# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program

## 1.do while
```
def do_while_example(start):
    result = []
    while True:
        result.append(start)
        start += 1
        if start > 5:
            break
    return result
def test_1():
    assert do_while_example(2) == [2, 3, 4, 5]
def test_2():
    assert do_while_example(2) == [2, 3, 4]
```

## 2.while
```
def while_loop_example(start):
    result = []
    while start < 5:
        result.append(start)
        start += 1
    return result

def test_while_loop_1():
    assert while_loop_example(2) == [2, 3, 4]

def test_while_loop_2():
    assert while_loop_example(2) == [2, 3]
```

## 3.for
```
def for_loop_example(start):
    result = []
    for i in range(start, 5):
        result.append(i)
    return result

def test_for_loop_1():
    assert for_loop_example(2) == [2, 3, 4]

def test_for_loop_2():
    assert for_loop_example(2) == [2, 3]

```

## 4.switch
```
def switch_example(value):
    match value:
        case 1:
            return "One"
        case 2:
            return "Two"
        case _:
            return "Other"

def test_switch_1():
    assert switch_example(1) == "One"
    assert switch_example(2) == "Two"
    assert switch_example(5) == "Other"

def test_switch_2():
    assert switch_example(1) == "Two"


```

## 5.if else
```
def if_else_example(num):
    if num > 5:
        return "Greater"
    else:
        return "Smaller or equal"

def test_if_else_1():
    assert if_else_example(7) == "Greater"
    

def test_if_else_2():
    assert if_else_example(7) == "Smaller or equal"

```


## Output

## do while

<img width="1409" height="618" alt="image" src="https://github.com/user-attachments/assets/d647f056-b54e-479e-9e7c-47880e9a4b0e" />

## while

<img width="1511" height="606" alt="image" src="https://github.com/user-attachments/assets/6af5b8db-3d0a-462a-930a-4aa982ea247e" />

## for

<img width="1621" height="654" alt="image" src="https://github.com/user-attachments/assets/ac436c3b-5f5d-4b30-91f3-8e45a8d48053" />

## switch

<img width="1648" height="524" alt="image" src="https://github.com/user-attachments/assets/4089dbe0-4e9e-46fa-bfe5-8ca924800a93" />


## if else

<img width="1639" height="616" alt="image" src="https://github.com/user-attachments/assets/b97d83ed-1d49-4d36-9aaa-44dea9a57280" />

## Result

Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



