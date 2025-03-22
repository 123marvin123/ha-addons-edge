# Home Assistant 123marvin123 Edge Add-on Repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this repository is to provide an add-on to use [Profilarr](https://github.com/Dictionarry-Hub/profilarr).
Additional add-ons might follow in the future.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

[![Add repository on my Home Assistant][repository-badge]][repository-url]

Use the following URL to add this repository:

```txt
https://github.com/123marvin123/ha-addons-edge
```

## Add-ons provided by this repository

### &#10003; [Profilarr][addon-profilarr]

![Latest Version][profilarr-version-shield]
![Supports armhf Architecture][profilarr-armhf-shield]
![Supports armv7 Architecture][profilarr-armv7-shield]
![Supports aarch64 Architecture][profilarr-aarch64-shield]
![Supports amd64 Architecture][profilarr-amd64-shield]
![Supports i386 Architecture][profilarr-i386-shield]

Configuration management tool for Radarr/Sonarr that automates importing and version control of custom formats and quality profiles.


[:books: Profilarr add-on documentation][addon-doc-profilarr]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

Open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Profilarr][profilarr-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

[addon-profilarr]: https://github.com/123marvin123/addon-profilarr/tree/v1.0.1
[addon-doc-profilarr]: https://github.com/123marvin123/addon-profilarr/blob/v1.0.1/README.md
[profilarr-issue]: https://github.com/123marvin123/addon-profilarr/issues
[profilarr-version-shield]: https://img.shields.io/badge/version-v1.0.1-blue.svg
[profilarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[profilarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[profilarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[profilarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[profilarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[gitlabci-shield]: https://gitlab.com/123marvin123/ha-addons-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/123marvin123/ha-addons-edge/pipelines
[issue]: https://github.com/123marvin123/ha-addons-edge/issues
[license-shield]: https://img.shields.io/github/license/123marvin123/ha-addons-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html
[repository-badge]: https://img.shields.io/badge/Add%20repository%20to%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[repository-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/123marvin123/ha-addons-edge