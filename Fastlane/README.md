fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios resolve_dependencies
```
fastlane ios resolve_dependencies
```
Resolve External Dependencies (the shell script makes Bitrise work)
### ios lint
```
fastlane ios lint
```
Run linting
### ios test
```
fastlane ios test
```
Run unit tests
### ios version
```
fastlane ios version
```
Create a new version

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
