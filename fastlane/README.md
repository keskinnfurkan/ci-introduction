fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios resolve_dependencies

```sh
[bundle exec] fastlane ios resolve_dependencies
```

Resolve Swift Package Manager dependencies

### ios build

```sh
[bundle exec] fastlane ios build
```

Build the project for simulator (Debug, no code signing)

### ios unit_tests

```sh
[bundle exec] fastlane ios unit_tests
```

Run unit tests (ci-introductionTests)

### ios ui_tests

```sh
[bundle exec] fastlane ios ui_tests
```

Run UI tests (ci-introductionUITests)

### ios tests

```sh
[bundle exec] fastlane ios tests
```

Run all tests — unit and UI (ci-introductionTests + ci-introductionUITests)

### ios ci

```sh
[bundle exec] fastlane ios ci
```

Full CI pipeline — build, unit tests, and UI tests

### ios release

```sh
[bundle exec] fastlane ios release
```

Archive and upload to TestFlight (requires App Store Connect API Key)

### ios bump_build

```sh
[bundle exec] fastlane ios bump_build
```

Increment the build number in the Xcode project

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
