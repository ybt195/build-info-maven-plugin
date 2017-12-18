# Contribution Guide

Looking to contribute to the project? Here is how you can get started.

## Filing an Issue

A good starting place for projects is to file issues and contribute to their discussions. These can come 
in the form of feature requests, general discussion threads or bug reports.

### Feature Requests

If you have a feature request, you can create an issue on the [Github Issues](https://github.com/ybt195/build-info-maven-plugin/issues) 
page and tag it with the "feature" label.

### General Discussions

General discussions and questions are more than welcomed. Feel free to create an issue on the 
[Github Issues](https://github.com/ybt195/build-info-maven-plugin/issues) page and tag it with the
"discussion" label.

### Bug Reports

Please report any standard bugs on the [Github Issues](https://github.com/ybt195/build-info-maven-plugin/issues) page.
For security related issues, please email the repository owner rather than filing the issue on github.

## Contributing Code

To get started with writing code for this project, look through the open issues and find something you like.

### Getting Started

To get started with development, you will need the following installed:
- Maven v3.5.2
- Java v1.8

You can check that these are installed with:
```bash
mvn enforcer:enforce
```

Additionally, you will need to clone (and fork if you choose to do so) the repository:
```bash
git clone git@github.com:ybt195/build-info-maven-plugin.git
```

To check that your installation is fully working, go to the root directory of the repository and type:
```bash
mvn install
```

### Code Guidelines

This project is primarily written in scala and uses maven as its build system.

Please read the [Scala Style Guide](https://docs.scala-lang.org/style/) for general scala information, but
be aware that there may be some overwritten rules that are enforced with scalastyle. The scala style
guide can be found [here](scalastyle-config.xml).

You can run the scalastyle checker with:

```bash
mvn scalastyle:check
```

### Submitting a Pull Request

Once you have completed your changes, you can [open a pull request](https://help.github.com/articles/about-pull-requests/).

In addition to your changes, be sure to add your changes to the [Changelog](CHANGELOG.md) in the current unreleased section.

By submitting a patch, you agree to allow the project owners to license your work under the terms of the Apache 2.0 License.
