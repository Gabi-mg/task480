# task

### How to build the app

- Check Dart version is 3.1.0 or higher
- Check Flutter version is 3.13.2 or higher
- Clone develop branch
- Clean the project:
  `flutter clean`
- Delete autogenerated classes by freezed. If it is the first time, it is not necessary

  ```bash
    find . -name "*.g.dart" -delete
    find . -name "*.freezed.dart" -delete
  ```
- Get packages
  `flutter pub get`
- Flutter code generation
  `flutter pub run build_runner build --delete-conflicting-outputs`
