# Transmission - Home Assistant add-on

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

This repository provides a [Transmission](https://transmissionbt.com/) add-on for [Home Assistant](https://www.home-assistant.io/).

<img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/transmission.png" width="720" height="300">


Learn more about the Transmission BitTorrent client from the official Transmission website: https://transmissionbt.com/

Read the [detailed documentation](./transmission) of this Home Assitant Transmission add-on.

To install, add this repository to your Home Assistant add-ons Store by clicking here:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmaorcc%2Fhassio-addon-transmission)

More details on installing and configuring this add-on can be found in the add-on docs, [here](./transmission/).

If you like it, please ⭐ this github repository. Thank you! <big>🙏</big>

<img src="https://www.home-assistant.io/images/home-assistant-logo-vertical.svg" width="200" height="200">

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

