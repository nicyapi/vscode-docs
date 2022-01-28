---
Order:
Area: setup
TOCTitle: Raspberry Pi
ContentId: E059E35A-8AD0-4D4A-9BE1-E23D45D75C1C
PageTitle: Running Visual Studio Code on Raspberry Pi OS
DateApproved: 01/29/2021
MetaDescription: Get Visual Studio Code up and running on Raspberry Pi OS.
---
# Visual Studio Code on Raspberry Pi

You can run Visual Studio Code on [Raspberry Pi](https://www.raspberrypi.org) devices.

[![Raspberry Pi Logo](images/raspberry-pi-os/RPi-Logo-Landscape-Reg-SCREEN.png)](https://www.raspberrypi.org)

## Installation

Visual Studio Code is officially distributed via the [Raspberry Pi OS](https://www.raspberrypi.org/software/operating-systems) (previously called Raspbian) APT repository.

You can install it by running:

```bash
sudo apt update
sudo apt install code # or code-insiders
```

## Updates

Your Raspberry Pi should handle updating VS Code in the same way as other packages on the system:

```bash
sudo apt update
sudo apt upgrade code # or code-insiders
```

You can always check when a new release is available in our [Updates](/updates) page.

## Next steps

Once you have installed VS Code, these topics will help you learn more about it:

* [Additional Components](/docs/setup/additional-components.md) - Learn how to install Git, Node.js, TypeScript, and tools like Yeoman.
* [User Interface](/docs/getstarted/userinterface.md) - A quick orientation to VS Code.
* [User/Workspace Settings](/docs/getstarted/settings.md) - Learn how to configure VS Code to your preferences through settings.
