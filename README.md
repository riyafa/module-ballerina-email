Ballerina Email Library
=======================

  [![Build](https://github.com/ballerina-platform/module-ballerina-email/workflows/Build%20master%20branch/badge.svg)](https://github.com/ballerina-platform/module-ballerina-email/actions?query=workflow%3ABuild)
  [![Daily build](https://github.com/ballerina-platform/module-ballerina-email/workflows/Daily%20build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-email/actions?query=workflow%3A%22Daily+build%22)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-email.svg)](https://github.com/ballerina-platform/module-ballerina-email/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The Email library is one of the standard library modules of the<a target="_blank" href="https://ballerina.io/"> Ballerina</a> language.

It provides implementation for sending emails over SMTP and receiving (with client and listener modes) over POP3 and IMAP4 protocols.

For more information go to [The Email Module](https://ballerina.io/swan-lake/learn/api-docs/ballerina/email/index.html).

For example demonstrations of the usage, go to [Ballerina By Examples](https://ballerina.io/swan-lake/learn/by-example/).

## Building from the Source

### Setting Up the Prerequisites

1. Download and install Java SE Development Kit (JDK) version 8 (from one of the following locations).

   * [Oracle](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)

   * [OpenJDK](http://openjdk.java.net/install/index.html)

        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.
     
### Building the Source

Execute the commands below to build from source.

1. To build the library:

    ```shell script
        ./gradlew clean build
    ```

2. To run the unit tests:

    ```shell script
        ./gradlew clean test
    ```

3. To build the module without the tests:

    ```shell script
        ./gradlew clean build -x test
    ```

4. To debug the tests:

    ```shell script
        ./gradlew clean test -Pdebug=<port>
    ```

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

You can also check for [open issues](https://github.com/ballerina-platform/module-ballerina-email/issues) that interest you. We look forward to receiving your contributions.

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss about code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
