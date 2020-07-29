# python-todo-list

* ❓ &nbsp;[fundamental] shallow copy vs deep copy, values vs references
* ❓ &nbsp;[scope] lexical scope
* ❓ &nbsp;[list] a slicing of a list is a (shallow) copy of the original list. Change it will not change the original one.
* ✅ &nbsp;[dict] sort dict by values
```python
x = {'a':10, 'b':100, 'c':1}
sorted(x.items(), key=lambda x:x[1])
```
* ✅ &nbsp;add to list, dict, and set
```python
a = [1, 2, 3]
a.append(1000)

b = {1, 2, 3}
b.add(1000)

c = {'a':10, 'b':100, 'c':1}
c.update(x=1000)
```
* ❓ &nbsp;[import] import matplotlib.pyplot as plt vs from matplotlib import pyplot as plt
* ❓ &nbsp;[generator] generators, coroutines, etc
* ❓ &nbsp;[OOP] OOP, magic functions, decorators, etc
* ❓ &nbsp;[visualization] use funcAnimation in matplotlib.animation
* ❓ &nbsp;[OOP] class attributes vs object attributes in Python? My answer is No.
* ❓ &nbsp;[OOP] why does __iadd__ return self?

