# OpenTelemetry php contrib library

![CI Build](https://github.com/open-telemetry/opentelemetry-php-contrib/workflows/PHP%20QA/badge.svg)
[![codecov](https://codecov.io/gh/open-telemetry/opentelemetry-php-contrib/branch/main/graph/badge.svg)](https://codecov.io/gh/open-telemetry/opentelemetry-php)


## Current Project Status
This project currently lives in a pre-alpha status.  Our current release is not production ready; it has been created in order to receive feedback from the community.

For more information, please, consult the documentation of the main [OpenTelemetry php project](https://github.com/open-telemetry/opentelemetry-php).

## Issues

Issues have been disabled for this repo in order to help main consistency between this repo and the main opentelemetry-php repo.  If you have an issue you'd like to raise about this issue, please use the [OpenTelemetry PHP Issue section](https://github.com/open-telemetry/opentelemetry-php/issues/new/choose).  Please prefix the title of the issue with [opentelemetry-php-contrib].

## Installation
### Install  individual packages:
(This is the recommened way to install the components)


Refer to the documentation for the individual components on how to install them


- [AWS](/src/AWS/README.md)
- [Symfony SdkBundle](/src/Symfony/OtelSdkBundle/README.md)

## Usage/Examples   

### AWS
- You can find examples on how to use the ASW classes in the  [examples directory](/examples/aws/README.md).

### Symfony
#### SdkBundle
- The documentation for the Symfony SdkBundle can be found [here](/src/Symfony/OtelSdkBundle/README.md).
- An example symfony application using the SdkBundle can be found [here](https://github.com/opentelemetry-php/otel-sdk-bundle-example-sf5).


## Development

Please, consult the documentation of the main [OpenTelemetry php project](https://github.com/open-telemetry/opentelemetry-php).

### Subprojects
This repository is organised into multiple separate sub-projects, under `/src`.
Please remember to run all tests as you develop, the makefile supports a `PROJECTS` variable, which corresponds to the path of the project (relative to `src/`), eg

```
$ PROJECT=Symfony PHP_VERSION=8.1 make all
```