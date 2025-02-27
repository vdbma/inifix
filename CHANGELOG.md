# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.9.0] - 2021-10-28

ENH: improve schema validation and add a file validation pre-commit hook
[PR #74](https://github.com/neutrinoceros/inifix/pull/74)

## [0.8.0] - 2021-10-26
This version is identical to 0.7.0 except that `FutureWarning`s are now raised for
api calls using future positional-only arguments using the keyword syntax.

## [0.7.0] - 2021-10-26

This version is identical to 0.6.0 except that it's compatibly for Python 3.6 to
3.10. Positional-only arguments are not specified any more because their are not
available for Python versions earlier than 3.8 Warnings may be added in a
following version to discourage usage of keyword syntax for these arguments.
