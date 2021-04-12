# Dart Lang Package Boilerplate

This package includes basic `pubspec.yaml` configuration file, required folders, and strict linting using `pedantic` package and my custom lints.

This boilerplate is for pure Dart packages without dependency on Flutter. If you want to create Flutter package use following command.

```
flutter create --template=package name
```

## Get started

1. Change `name`, `description` and `homepage` in `pubspec.yaml`.

2. Change package dependency name in the `example/pubspec.yaml` according to your package name.

3. Change your name in the `LICENSE` file.

4. Put correct info into the `CHANGELOG.md` file.

5. Create `lib` folder with implementation files. `lib` folder should contain a single Dart file with same name as your package and a `src` folder with implementation files.