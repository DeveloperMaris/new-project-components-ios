# New Project Components (iOS)
A collection of useful files for a new iOS project.

## Version control system

Best practices:
* Provide [.gitignore](./.gitignore) to not push any unnecessary files to project repository. `.gitignore` file can be generated using [gitignore.io](https://gitignore.io/).

## System dependencies

Best practices:
* Use [Gemfile](./Gemfile) to store a list of 3rd party Ruby dependencies for the project, for example, [Fastlane](https://github.com/fastlane/fastlane) or [Cocoapods](https://github.com/CocoaPods/CocoaPods).
* Use [rbenv](https://github.com/rbenv/rbenv) as a Ruby version management tool to switch Ruby versions. Especially if using CI.
* Provide [.ruby-version](./.ruby-version) file to specify used Ruby version.
* Use [Bundler](https://bundler.io) to install Ruby dependencies.

## Environment

Best practices:
* If need to use system environment variables, use [dotenv](https://github.com/bkeepers/dotenv) Ruby gem. It can load variables from [.env](./.env.example) files.

## Project dependencies

Best practices:
* Use [Swift Package Manager](https://developer.apple.com/documentation/xcode/swift-packages) for 3rd party library management.

## Project configuration

Best practices:
* Use [xcconfig](./Configuration) files for configuring project build settings.

## Licence

`new-project-components-ios` is released under the MIT License. See [LICENSE](LICENSE) for details.
