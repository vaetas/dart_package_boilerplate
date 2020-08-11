# Dart Lang Package Boilerplate

This package includes basic `pubspec.yaml` configuration, required folders and strict linting using `pedantic`.

This boilerplate if for pure Dart packages without dependency on Flutter. If you want to create Flutter package use following command.

```
flutter create --template=package name
```

## Get started

1. Change `name`, `description` and `homepage` in `pubspec.yaml`.

2. Change package dependency name in `example/pubspec.yaml` according to main package name.

3. Change your name in `LICENSE`.

4. Put correct info into `CHANGELOG.md`.

5. Create `lib` folder with implementation files. `lib` folder should contain single Dart file with same name as package and `src` folder with other files.