# Plyer

## Fork Changelog
in this fork ,rather than the PIP version , 2 modules are fixed: camera and vibrator.
To use with buildozer,instead of writing 'plyer' in the requirements line, write `git+https://github.com/tomgold182/plyer.git`

Plyer is a platform-independent api to use features commonly found on various
platforms, notably mobile ones, in Python.

[![coverage](https://coveralls.io/repos/kivy/plyer/badge.svg?branch=master)](https://coveralls.io/r/kivy/plyer?branch=master)
[![travis](https://travis-ci.org/kivy/plyer.svg?branch=master)](https://travis-ci.org/kivy/plyer)
[![appveyor](https://ci.appveyor.com/api/projects/status/k1bwhdie0tfmdq96?svg=true)](https://ci.appveyor.com/project/KivyOrg/plyer)
[![Backers on Open Collective](https://opencollective.com/kivy/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/kivy/sponsors/badge.svg)](#sponsors)


## How

Plyer tries not to reinvent the wheel, and will call for external libraries to
implement the api in the easiest way, depending on the current platform.

- on python-for-android, pyjnius is used
- on kivy-ios, pyobjus is used
- on windows/mac/linux, commonly found libraries and programs will be used


## Supported APIs

| Platform                       | Android | iOS | Windows | OS X | Linux |
| ------------------------------ | ------- | --- | ------- | ---- | ----- |
| Accelerometer                  | ✔       | ✔   |         | ✔    | ✔     |
| Audio recording                | ✔       |     | ✔       | ✔    |       |
| Barometer                      | ✔       | ✔   |         |      |       |
| Battery                        | ✔       | ✔   | ✔       | ✔    | ✔     |
| Bluetooth                      | ✔       |     |         | ✔    |       |
| Brightness                     | ✔       | ✔   |         |      | ✔     |
| Call                           | ✔       | ✔   |         |      |       |
| Camera (taking picture)        | ✔       | ✔   |         |      |       |
| Compass                        | ✔       | ✔   |         |      |       |
| CPU count                      |         |     | ✔       | ✔    | ✔     |
| Email (open mail client)       | ✔       | ✔   | ✔       | ✔    | ✔     |
| Flash                          | ✔       | ✔   |         |      |       |
| GPS                            | ✔       | ✔   |         |      |       |
| Gravity                        | ✔       | ✔   |         |      |       |
| Gyroscope                      | ✔       | ✔   |         |      |       |
| Humidity                       | ✔       |     |         |      |       |
| IR Blaster                     | ✔       |     |         |      |       |
| Light                          | ✔       |     |         |      |       |
| Native file chooser            | ✔       |     | ✔       | ✔    | ✔     |
| Notifications                  | ✔       |     | ✔       | ✔    | ✔     |
| Orientation                    | ✔       |     |         |      |       |
| Proximity                      | ✔       |     |         |      |       |
| Screenshot                     |         |     | ✔       | ✔    | ✔     |
| SMS (send messages)            | ✔       | ✔   |         |      |       |
| Spatial Orientation            | ✔       | ✔   |         |      |       |
| Speech to text                 | ✔       |     |         |      |       |
| Storage Path                   | ✔       | ✔   | ✔       | ✔    | ✔     |
| Temperature                    | ✔       |     |         |      |       |
| Text to speech                 | ✔       | ✔   | ✔       | ✔    | ✔     |
| Unique ID                      | ✔       | ✔   | ✔       | ✔    | ✔     |
| Vibrator                       | ✔       | ✔   |         |      |       |
| Wifi                           |         |     | ✔       | ✔    | ✔     |


## Support

If you need assistance, you can ask for help on our mailing list:

* User Group : https://groups.google.com/group/kivy-users
* Email      : kivy-users@googlegroups.com

Discord channel:

* Server     : https://chat.kivy.org
* Channel    : #dev


## Contributing

We love pull requests and discussing novel ideas. Check out our
[contribution guide](http://kivy.org/docs/contribute.html) and
feel free to improve Plyer.

The following mailing list and IRC channel are used exclusively for
discussions about developing the Kivy framework and its sister projects:

* Dev Group : https://groups.google.com/group/kivy-dev
* Email     : kivy-dev@googlegroups.com

IRC channel:

* Server  : irc.freenode.net
* Port    : 6667, 6697 (SSL only)
* Channel : #kivy-dev


## License

Plyer is released under the terms of the MIT License. Please refer to the
LICENSE file.


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/kivy#backer)]

<a href="https://opencollective.com/kivy#backers" target="_blank"><img src="https://opencollective.com/kivy/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/kivy#sponsor)]

<a href="https://opencollective.com/kivy/sponsor/0/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/1/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/2/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/3/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/4/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/5/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/6/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/7/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/8/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/kivy/sponsor/9/website" target="_blank"><img src="https://opencollective.com/kivy/sponsor/9/avatar.svg"></a>


