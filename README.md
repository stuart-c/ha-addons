# Home Assistant Apps

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## Installation

This repository functions as a standard Home Assistant custom Add-on repository. You can add it directly to your Home Assistant instance using the button below:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fstuart-c%2Fha-addons)

Alternatively, add it manually:
1. Navigate in your Home Assistant frontend to **Settings** -> **Add-ons** -> **Add-on store**.
2. Click the three vertical dots (&#8942;) in the upper right corner and select **Repositories**.
3. Add `https://github.com/stuart-c/ha-addons` and click **Add**.
4. The add-on will now be available for configuration and installation.

## Apps provided by this repository

### &#10003; [eInk Layout Manager][addon-eink]

![Latest Version][eink-version-shield]
![Supports armhf Architecture][eink-armhf-shield]
![Supports armv7 Architecture][eink-armv7-shield]
![Supports aarch64 Architecture][eink-aarch64-shield]
![Supports amd64 Architecture][eink-amd64-shield]
![Supports i386 Architecture][eink-i386-shield]

Manage multiple eInk displays with advanced layouts via OpenDisplay

[:books: eInk Layout Manager app documentation][addon-doc-eink]

### &#10003; [ik_llama.cpp Server][addon-llama]

![Latest Version][llama-version-shield]
![Supports armhf Architecture][llama-armhf-shield]
![Supports armv7 Architecture][llama-armv7-shield]
![Supports aarch64 Architecture][llama-aarch64-shield]
![Supports amd64 Architecture][llama-amd64-shield]
![Supports i386 Architecture][llama-i386-shield]

High-performance llama.cpp fork for Pi 5

[:books: ik_llama.cpp Server app documentation][addon-doc-llama]


[addon-eink]: https://github.com/stuart-c/addon-eink/tree/v0.9.0
[addon-doc-eink]: https://github.com/stuart-c/addon-eink/blob/v0.9.0/README.md
[eink-issue]: https://github.com/stuart-c/addon-eink/issues
[eink-version-shield]: https://img.shields.io/badge/version-v0.9.0-blue.svg
[eink-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[eink-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[eink-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[eink-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[eink-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-llama]: https://github.com/stuart-c/addon-llama/tree/v0.1.8
[addon-doc-llama]: https://github.com/stuart-c/addon-llama/blob/v0.1.8/README.md
[llama-issue]: https://github.com/stuart-c/addon-llama/issues
[llama-version-shield]: https://img.shields.io/badge/version-v0.1.8-blue.svg
[llama-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[llama-amd64-shield]: https://img.shields.io/badge/amd64-no-red.svg
[llama-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[llama-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[llama-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[license-shield]: https://img.shields.io/github/license/stuart-c/ha-addons.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg