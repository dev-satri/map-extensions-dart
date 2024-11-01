# Map Extensions
`NOTE:`This code gives key and value from a List by passing index
```
extension MapExtension on Map {
  dynamic valueAtIndex(index) {
    List<dynamic> values = List.from(this.values);
    return values[index];
  }

  dynamic keyAtIndex(index) {
    List<dynamic> keys = List.from(this.keys);
    return keys[index];
  }
}
```
