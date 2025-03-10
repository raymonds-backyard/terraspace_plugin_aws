# Changelog

All notable changes to this project will be documented in this file.
This project *loosely tries* to adhere to [Semantic Versioning](http://semver.org/).

## [0.3.3] - 2021-12-14
- [#10](https://github.com/boltops-tools/terraspace_plugin_aws/pull/10) implement expand_string? to not expand aws arn values

## [0.3.2] - 2021-12-14
- [#9](https://github.com/boltops-tools/terraspace_plugin_aws/pull/9) support separate aws account for s3 backend bucket

## [0.3.1] - 2021-12-14
- [#8](https://github.com/boltops-tools/terraspace_plugin_aws/pull/8) use region configured in the backend.tf for the s3 client

## [0.3.0] - 2020-11-15
- [#5](https://github.com/boltops-tools/terraspace_plugin_aws/pull/5) helper and secrets support
- aws_secret and aws_ssm helpers

## [0.2.2]
- #4 default access logging to false
- set prefix to @folder for performance improvement

## [0.2.1]
- #3 quiet s3-secure messages

## [0.2.0]
- #2 include layer interface, update template to expansion method

## [0.1.0]
- Initial release
