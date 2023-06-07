# Jellyfin Server Add-on

![Supports amd64 Architecture][amd64-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports aarch64 Architecture][aarch64-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg

This [Home Assistant](https://www.home-assistant.io/addons/) add-on installs the
[Jellyfin](https://jellyfin.org/) server. It does not provide any integrations.

Server is exposed on port `8096`.

Configuration and caches are stored on `share` (not in config), therefore
its data will not be deleted when add-on is uninstalled, and must be deleted
manually. This is intentional.

## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Hass.io add-on.

1. [Add my Hass.io add-ons repository][repository] to your Hass.io instance.
1. Install this add-on.
1. Click the `Save` button to store your configuration.
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well.
1. Carefully configure the add-on to your preferences, see the official documentation for for that.

[repository]: https://github.com/PrimusNZ/hassio-addons