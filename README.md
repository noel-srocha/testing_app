# Testing App

A new Flutter project.

## Getting Started

1) Clone or fork the project and type the command below on your project terminal:

```
flutter create .
```

This will recreate all platforms specific native code that is necessary when building Flutter projects.

If you need only some specific platforms, run the command below:

```
flutter create --platforms android,ios . // windows, macos, linux, web 
```

2) Make sure you have all the dependencies set up:

```
flutter pub get
```

3) Add your tests at the specified folders:

```
/integration_test
/test
/test_driver
```

4) Use the following commands to your applicaton (it's recommend that you have a device ready if you plan to run the test on it):

```
flutter test
flutter test {file_test.dart path}
flutter run {file_test.dart path}
flutter test --coverage
```

5) Start Coding and have fun!
