# project-build-examples 6.0
sample projects to demonstrate project CI/CD features of the [`project-build-plugin`](http://axonivy.github.io/project-build-plugin/release/6.0/plugin-info.html).

## compile-test
Simple multi module build with an ivy project and extra project to test it. To build the ivy project and run its tests proceed as follows:
- install a maven runtime https://maven.apache.org/install.html
- download and unpack this branch as ZIP (or clone it with git) https://github.com/axonivy/project-build-examples/archive/6.0.zip
- open a command line and navigate into the unpacked compile-test folder
- run `mvn clean package` to build the ivy project and run its tests.
