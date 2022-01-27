<div align="center">
<img src="https://github.com/MaxBec/hassio-diyHue/blob/master/diyhue/logo.png">
<h1>Home Assistant Add-on: diyHue</h1>
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
<br>
<p>Run <a href="https://diyhue.org">diyHue</a> as a Home Assistant Add-on</p>
</div>

## About

diyHue provides a Ecosystem for several Smart Home Solutions, eliminating the need for vendor specific Bridges and Hardware. Written in Python and Open Source, you are now able to import and control all your Lights and Sensors into one System. Lightweight and resource friendly, to run on small
devices like the RPi .... 24/7

The Best part? No Cloud connection by Design!

Enjoy your diyHue enlighted Home.

![diyHue ecosystem](https://raw.githubusercontent.com/diyhue/diyhue.github.io/master/assets/images/hue-map.png)

## Installation

The installation process is pretty easy and straight forward, like for any other third-party Home Assistang Add-on.

Add the repository URL under **Supervisor → Add-on store → ⋮ → Manage add-on repositories**:

    https://github.com/r0bb10/ha-addons

## Support

All documentation and instructions can be found over at [diyhue.readthedocs.io](https://diyhue.readthedocs.io/)

If you need help with diyHue you can get support from other users, aswell as the maintainer.

### Slack [![JoinSlack](https://img.shields.io/badge/Join%20us-on%20Slack-green.svg)](https://join.slack.com/t/diyhue/shared_invite/enQtNzAwNDE1NDY2MzQxLTljNGMwZmE0OWRhNDIwM2FjOGM1ZTcxNjNmYjc5ZmE3MjZlNmNjMmUzYmRkZjhhOGNjOTc4NzA0MGVkYzE2NWM)

Use Slack for a general chat or fast live support.

However: Since Slack is faster at providing live Support but not as good when it comes to save and show known Issues, we kindly ask you to open a Topic at our Discourse group. This will provide Help for others in the future.

### Discourse [![Discourse](https://img.shields.io/discourse/users?server=https%3A%2F%2Fdiyhue.discourse.group)](https://diyhue.discourse.group)

Our Board might already have your fix and answer ready. Have a look!

> General Note: Please provide some Logs to make it easier for all of us. Enable Debug by manually starting diyHue with additional `--debug true` argument.

## Contribute

diyHue is Opensource and maintained by volunteers in their free time. You are welcome to contribute and become a recognised member of the diyHue community. Feel free to add PR and Commits to our Dev Branch. If you are experienced in

-    Webdesign
-    Python
-    Arduino
-    Coding in general

We highly appreciate your support, making diyHue even better!

## Credits

-    Ben ([@cheesemarathon](https://github.com/cheesemarathon)) All fancy github integrations
-    [Stephan van Rooij](https://github.com/svrooij) - zigbee2mqtt integration
-    [@avinashraja98](https://github.com/avinashraja98) - Hue Entertainment server
-    Federico Zivolo ([@FezVrasta](https://github.com/FezVrasta)) Internal WebGUI
-    [@J3n50m4t](https://github.com/J3n50m4t) - Yeelight integration
-    Martin Černý ([@mcer12](https://github.com/mcer12)) - Yeelight color bulb
-    probonopd https://github.com/probonopd/ESP8266HueEmulator
-    sidoh https://github.com/sidoh/esp8266_milight_hub
-    StefanBruens https://github.com/StefanBruens/ESP8266_new_pwm
-    Cédric @ticed35 for linkbutton implementation
-    [@cheesemarathon](https://github.com/cheesemarathon) - Help with Docker images
-    [@Mevel](https://github.com/Mevel) - 433Mhz devices
-    [@Nikfinn99](https://github.com/Nikfinn99) - PCB designs
-    [@crankyoldgit](https://github.com/crankyoldgit) - IR Remote library
-    Max Beckenbauer ([@MaxBec](https://github.com/MaxBec)) For the original diyHue addon!!

## License

[![license](https://img.shields.io/badge/license-GPLv3%2FApache%202.0%2FCC%20BY--SA%204.0-blue.svg)](https://github.com/diyhue/diyHue/blob/master/LICENSE.md)
