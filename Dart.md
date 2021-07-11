# Dart

## Variable/Data Structure
#### Definition
```
var name = 'Voyager I';
var year = 1977;
var antennaDiameter = 3.7;

# array
var flybyObjects = ['木星', '土星', '天王星', '海王星'];

# dict
var image = {
  'tags': ['土星'],
  'url': '//path/to/saturn.jpg'
};
```

#### Data Structure Iteration
###### Map
```
if (image.containsKey('tags')) {
  print(image['tags'])
}

for(MapEntry e in image.entries) {
  print("Key ${e.key}, Value ${e.value}")
}

```

###### Array
```
if (flybyObjects.contains('木星')) {
  print('木星')
}

for(var c1 in flybyObjects) {
  print(c1)
}
```

## Common Libs

## Snippet
