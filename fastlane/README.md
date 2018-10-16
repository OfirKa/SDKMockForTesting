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
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios Manually_Run_Tests
```
fastlane ios Manually_Run_Tests
```
Runs tests on your current directory. This option doesn't pull/push/commit or reset git. Make sure you save it on the correct directory. 
### ios Run_Tests_And_Reset
```
fastlane ios Run_Tests_And_Reset
```
Pull latest sdk version, Runs tests on SDK, get frameworks from sdk and resets your SDK back to the latest git version, any other changes would be deleted. Make sure you run this option only after you've ran SDK_Core test with successs.
### ios Version_Upload
```
fastlane ios Version_Upload
```
Runs Tests, tagging, checking pod, commiting and pushing the new version.
### ios ofirTests
```
fastlane ios ofirTests
```


----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
