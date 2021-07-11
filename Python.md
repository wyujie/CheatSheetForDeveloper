# Python

## Variable/Data Structure
#### Definition
```
a = 1
b = 'B'

# List
c = []
c.append(1)
c += [2,3,4]

# Dict
d = {
  'k1': 'v1'
}
d['k2'] = 'v2'


#Set
e = set()
e.add(1)

# Tuple
f = (1, 2, 3)
```

#### Data Structure Iteration
###### Dict
```
if 'k1' in d:
  print(d['k1'])

for k, v in d.items():
  print(k, v)

```

###### List/Tuple/Set
```
for c1 in c:
  print(c1)
```

###### Function
```
# define a function which allows any params and print them
def func1(*args, **kwargs):
  print(args, kwargs)
```


## Common Libs
##### [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)

## Snippet
