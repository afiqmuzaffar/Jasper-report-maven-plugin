# 2.8

- Update to Jasper 6.15 
- Other dependency updates
- [Ability to <skip> the compilation](https://github.com/alexnederlof/Jasper-report-maven-plugin/pull/69)
- [Set default threads to the number of processors](https://github.com/alexnederlof/Jasper-report-maven-plugin/commit/ccde203ebdf3648e4be0b84647da26d71937e860)  

# 2.7

- Update to Jasper 6.11.0

# 2.6

- Update to Jasper 6.9.0

# 2.5

- Update to Jasper 6.8.0
- Bug fix typo in xmlValidation https://github.com/alexnederlof/Jasper-report-maven-plugin/pull/51

# 2.4

- Update to Java 8, and new Plugin Mojo style with annotations
- Added `additionalClasspath` option to support adding extra libraries to the classpath.
- Updated to jasper 6.7

# 2.3

- Backwards compatibility to Java 1.6
- Close open input skills after usage

Big thanks to @brunoabdon

# 2.2

- Configuration option to always compile all files

# 2.1

- Added `failOnMissingSourceDirectory` property, so that one can continue the build while sourceDirectory does not exist.

# 2.0

This release sets Jasper to version 6 and updates some other deps. Also uses the 
new OSS release system instead of the old OSS parent pom.
This release requires using Maven 3.x.

# 1.9

- Fixes a bug that required a dependency on Servlet. [#13](https://github.com/alexnederlof/Jasper-report-maven-plugin/issues/13)

# 1.8

- Fixes [#7](https://github.com/alexnederlof/Jasper-report-maven-plugin/issues/7) For each `.jrxml` file search the compiled .jasper if not found or older than source file recompile it.
- Fixes [#9](https://github.com/alexnederlof/Jasper-report-maven-plugin/issues/9) Project classpath added to ClassLoader.

Thanks to [@lucarota](https://github.com/lucarota)

# 1.7

 - Allows developers to set additional properties [#5](https://github.com/alexnederlof/Jasper-report-maven-plugin/pull/5). Thanks to [@Plozi](https://github.com/plozi)

# 1.6

- Prepared the project to be hosted on Maven central. No code changes.

# 1.5

- Allow setting of a custom compiler.

# 1.4

-	Updated the Jasper version
