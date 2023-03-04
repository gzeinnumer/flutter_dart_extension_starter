# flutter_dart_extension_starter

- Point 1

```dart
extension Extension on String{
  String addCat(){
    return '$this edit';
  }
}
```
```dart
String _counterv2 = "add ".addCat();
String _counterv2 = 0.toString().addCat();
```

- Point 2

```dart
extension SeparedList<T> on List<T>{
    List<T> separated(T separator){
        final newList = <T>[];

        return newList;
    }
}
```
```dart
[].separated(Spacer();
```