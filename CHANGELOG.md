# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.0]

- Prefer mac address as ID if we have a static MAC and only md fingerprint
- Breaking: If you're using a md:*:* fingerprint, verify that it hasn't switched to the mac

## [1.1.2]

- Add support for clearing wifi setting via button on DevKit (as long as it's on GPIO15)

## [1.1.1]

- Fix fingerprinting of udm-pro
- Fix semaphore error

## [1.1.0]

- Go back to active scanning by default (so we can get the names of things)
- Send telemetry only every 15s
- Allow for disabling types of mqtt topics
- M5Sticks now have a UI showing devices that are close

## [1.0.1]

- Added esp32-noupdate

## [1.0.0] - 2021-08-20

- Initial