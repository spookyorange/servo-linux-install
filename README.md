# Install tarball version of Servo with just a basic script!

A script to easily install Servo the tarball way on your Linux machine!

Warning: This project appears to be very new and very unstable(understandably), so while this script is pretty safe to run, please note that it might cause problems if the developers decide to introduce breaking changes in the general project structure. In the event of that happening, please open up a PR, or an issue at the very least <3.

Note: This installation script is by no means affiliated with Servo, The Linux Foundation, The Linux Foundation Europe projects, or their maintainers.

## Usage

Clone the repo and run the script
```bash

git clone https://github.com/spookyorange/servo-linux-install.git
cd servo-linux-install
sh ./install.sh

```

To remove the application(if it has been installed with this method)
```bash

sh ./uninstall.sh

```

To update the app manually, simply run the install script again.

```bash

sh ./install.sh

```

## Details

The script will install the application in the following destinations if you have installed locally:

- ~/.tarball-installations/servo
- ~/.local/bin/servo
- ~/.local/share/applications/servo.desktop
- Also wherever the app data may be at(app decides it and it may change, also may depend on machine your configuration)

## Tested Distros

- Fedora by Spookyorange
- SteamOS(Steam Deck) by Spookyorange

## Contributing

If you have a distro that you would like to add to the list of tested distros, please submit a pull request with the changes you made to the script and the distro you tested it on.
