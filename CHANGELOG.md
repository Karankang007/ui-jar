# 1.0.0 (2018-03-11)
Happy to announce v.1.0.0 release of UI-jar!

### Features
* Add possibility to use multiple @hostcomponents


# 1.0.0-rc.1 (2018-02-20)
### Bug fixes
* HostComponent in seperate file is not showing up in Example container
* API Properties for exteded classes are ignored
* File watcher is not working properly on Windows 10 and MacOS

### Features
* Add possibility to use "templateUrl" in a test host component


# 1.0.0-beta.12 (2018-01-30)
### Bug fixes
* Updated typescript version to supported by Angular 5.2

### Features
* View source option now include test code implementation and property bindings
* Source path to each component is now relative to input directory path (before it was absolute path)


# 1.0.0-beta.11 (2017-12-13)
### Bug fixes
* Updated typescript version to supported by Angular 5.1

### Features
* Added possibility to add custom title to each example
* Each example is now displayed separated in the overview tab
* Minor updates in the UI


# 1.0.0-beta.10 (2017-12-04)
### Bug fixes
* Trim whitespaces in component reference name
* Creating new context for each example
* Removed usage of private properties

### Features
* Add possibility to use HttpClientTestingModule for tests


# 1.0.0-beta.9 (2017-11-13)
### Bug fixes
* includes/excludes RegExp is tested against absolute path instead of filename
* ERROR in UIjarModule is not an NgModule

### Features
* Incremental build when using --watch flag
* Updated UI

### Breaking changes
* Fixing typo on "UIjarModule", it's renamed to "UIJarModule" (CamelCase).


# 1.0.0-beta.8 (2017-11-02)
### Bug fixes
* getter/setter methods on properties is now visible in the property list in API view