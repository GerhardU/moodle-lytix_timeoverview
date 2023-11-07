# lytix\_timeoverview

This plugin is a subplugin of [local_lytix](https://github.com/llttugraz/moodle-local_lytix).
The `lytix_timeoverview` module serves as a comprehensive tool to provide a detailed view of time-related metrics in Moodle. This plugin is especially essential for capturing user interactions and activities that are not automatically logged by Moodle, particularly within the custom-developed dashboard.

## Table of Contents

- [Installation](#installation)
- [Requirements](#requirements)
- [Features](#features)
- [Configuration](#configuration)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [API Documentation](#api-documentation)
- [Subplugins](#subplugins)
- [Privacy](#privacy)
- [FAQ](#faq)
- [Known Issues](#known-issues)
- [Changelog](#changelog)
- [License](#license)
- [Contributors](#contributors)

## Installation

1. Download the plugin and extract the files.
2. Move the extracted folder to your `moodle/local/lytix/modules/` directory.
3. Log in as an admin in Moodle and navigate to `Site Administration > Plugins > Install plugins`.
4. Follow the on-screen instructions to complete the installation.

## Requirements

- Moodle Version: 4.1+
- PHP Version: 7.4+
- Supported Databases: MariaDB, PostgreSQL
- Supported Moodle Themes: Boost

## Features

- Utilizes PHP for backend operations, ensuring smooth data storage and retrieval.
- Interactions recorded via the dashboard are stored in the backend for future access and analysis.

## Configuration

Describe here how to configure the plugin after installation, including available settings and how to adjust them.

## Usage

Explain how to use the plugin with step-by-step instructions and provide screenshots if they help clarify the process.

## Dependencies

- [local_lytix](https://github.com/llttugraz/moodle-local_lytix).
- [lytix_config](https://github.com/llttugraz/moodle-lytix_config).
- [lytix_logs](https://github.com/llttugraz/moodle-lytix_logs).

## API Documentation

If your plugin offers API endpoints, document what they return and how to use them here.

## Subplugins

If there are any subplugins, provide links and descriptions for each.

## Privacy

Detail what personal data the plugin stores and how it handles this data.

## FAQ

**Q:** Frequently asked question here?
**A:** Answer to the question here.

**Q:** Another frequently asked question?
**A:** Answer to the question here.

## Known Issues

- Issue 1: Solution or workaround for the issue.
- Issue 2: Solution or workaround for the issue.

## Changelog

### Version v1.1.3

- Release of the plugin for Moodle 4.2 and 4.3.
- Move the calculation to lytix_helper.
- Disable grunt because of an error in the CI.

## License

This plugin is licensed under the [GNU GPL v3](LINK_TO_LICENSE).

## Contributors

- **Günther Moser** - Developer - [GitHub](LINK_TO_GITHUB_PROFILE)
- **Alex Kremser** - Developer - [GitHub](LINK_TO_GITHUB_PROFILE)
