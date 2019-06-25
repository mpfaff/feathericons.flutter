# Feather Icons Flutter

The [Feather](https://feathericons.com/) Icon pack created by [Cole Bemis](https://github.com/colebemis) available as set of Flutter Icons.

Check the [changelog](CHANGELOG.md) for the version of Feather Icons included.

## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  feather_icons_flutter:
    git: git://github.com/MaterialTime/feathericons.flutter.git
```

## Usage

```dart
import 'package:feather_icons_flutter/feather_icons_flutter.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      // Use the FeatherIcons class for the IconData
      icon: new Icon(FeatherIcons.activity), 
      onPressed: () { print("Pressed"); }
     );
  }
}
```
