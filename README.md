<div align="center">
  <img style="max-height: 200px;" src="./images/barista-icon.png" alt="Barista Cloud Rendering Platform" />

  <h2>Barista Demo App</h2>
  <h3>The Barista Cloud Rendering Platform gives Blender
  Users an affordable platform to render projects remotely using Amazon Web Services</h3>
  <div>
    <a href="https://github.com/baristarender/Barista-Demo/releases/latest">
      <img src="https://img.shields.io/github/release-date/baristarender/Barista-Demo.svg?style=flat-square"/>
    </a>
    <a href="https://npmjs.org/package/Barista-Demo">
      <img src="https://img.shields.io/github/downloads/baristarender/Barista-Demo/total.svg?style=flat-square" alt="downloads" />
    </a>
    <a href="https://github.com/baristarender/Barista-Demo/issues">
      <img src="https://img.shields.io/github/issues/baristarender/Barista-Demo.svg?style=flat-square"/>
    </a>
    <a href="https://opensource.org/licenses/MIT">
      <img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square"/>
    </a>
  </div>
</div>

## Barista Demo

The Barista Demo Application is currently a limited version of the Barista platform to give the community the ability to test the platform before jumping into a version that provides premium support. 

### Limitations

At this time the following areas of the client are limited:

* Instance Availability limited to Test Hardware
* Automatic Downloads are Disabled
* Limited Available Regions
* CPU-only rendering
* Cannot start more than one instance at a time

Since Barista uses your own AWS account, these limitations are mostly in place to keep anyone from accidentally charging large amounts to their AWS account. 


### Taking Precautions

Barista is incredibly powerful, and uses an AWS account you provide. If you are new to AWS, it's highly suggested to read about basic AWS Management. Barista provides all of the needed information in the built-in Documentation (**Help > Documentation**), in section *AWS > EC2 > Instances*. You can also watch the <u>Instance Basics and Manual Shutdowns</u> video on how to manage EC2 hardware found on the [Barista YouTube channel](https://youtu.be/vh70sv7b9fc). 


## Tester Versions

Barista values anyone willing to test new releases, so Development Versions are offered at a reduced price, specifically for those looking to test out new features. People who work to find bugs and help make the platform better through testing may be given premium support for their contributions.


## Installation

First download the binary for your Operating System in the [Releases](https://github.com/BaristaRender/Barista-Demo/releases) section. Follow the instructions below for your preferred OS.

### Windows (Installer)

Double click the Barista Windows Setup executable, and follow the guided instructions to install Barista. Once finished, Barista can be found in the Start Menu.

### Windows (Portable)

Place the Windows Portiable binary anywhere on your Windows system and double-click to launch Barista.

### OSX

Double-click the DMG file to mount the image to your system. Next, move the Barista binary to your Applications folder by clicking and dragging the icon onto the Applications folder in the DMG window. Start Barista from the Applications folder, or using the OSX Spotlight.

### Linux (Desktop) 

Make the Barista AppImage file executable by right-clicking the file, changing the permissions by enabling the user's permissions to execute the file. Once set, double-click the file to start the installation of Barista.

### Linux (CLI)

1. Make the binary file executable:

``$ chmod 755 Barista-{require('../../package.json').version}.AppImage``

2. Next, execute the binary to start and install Barista:

``$ ~/Barista-{require('../../package.json').version}.AppImage``

Note: Supported Desktop Environments will allow Barista to create a desktop shortcut, as well as place Barista into the Graphics folder in your application list. *If your DM doesn't provide the correct icon, use the icon provided in this repository above (images/barista-icon.png).*

## Support

Barista has been extensively documented in its own built-in documentation (**Help > Documentation**) as well as many videos covering the most common topics on the [Barista YouTube Channel](https://www.youtube.com/channel/UCqwiD9xWM49ZkLVHJyWsSug).

If you want premium support directly from the developer, you can get such through the Complete and Developer options on the [Blender Market](https://blendermarket.com/products/barista).

## Outside Support

For anyone looking for additional support outside of dedicated support for Barista, additional support can be provided for the following areas:

* Custom Feature Support for Barista
* General AWS Support
* EC2 Support
* AWS-API Development Support
* Blender Remote Rendering Support
* Linux Architecture Design
