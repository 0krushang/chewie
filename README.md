# Forked Chewie

This repository is a fork of the original Chewie package. It has been modified to meet the requirements of our project within our company.

## 📌 Why This Fork?

We needed to use an older version of Chewie because some of the packages in our project depend on a version that contains a method that was removed in later Flutter updates. Unfortunately, upgrading Chewie was not an option since our Flutter version does not support it.

To overcome this, we forked the original repository and made the necessary modifications while keeping compatibility with our existing dependencies.

## 🎖️ Credits

The original repository belongs to the Flutter Community. Full credit goes to them for their hard work on Chewie.

🔗 **Original Repository:** [fluttercommunity/chewie](https://github.com/fluttercommunity/chewie.git)

## 🔧 Changes Made

- Retained an older version of Chewie with required methods.
- Ensured compatibility with our project's dependencies.
- Minor fixes to align with our Flutter version constraints.

## 🚀 Usage

To use this forked version in your Flutter project, update your `pubspec.yaml` as follows:

```yaml
dependency_overrides:
  chewie:
    git:
      url: https://github.com/0krushang/chewie.git
