# LEGO® MindStorms RCX Archive
An archive of software releases related to the LEGO® MindStorms RCX

> [!IMPORTANT]
> This repository is typically kept in read-only (archive) mode to guard against accidental changes, modifications, or deletions;
however, it can be updated as needed.  Since this repository is typically locked,
please direct any discussion to the [BrickBot organization discussion](https://github.com/orgs/BrickBot/discussions).

&nbsp;
## Official Releases from LEGO®
* [LEGO® MindStorms Robotics Invention System](https://github.com/BrickBot/Archive/releases/tag/LEGO)
* [LEGO® MindStorms RCX Multimedia](https://github.com/BrickBot/Archive/releases/tag/LEGO-Multimedia)

&nbsp;
## Supporting Software
While not directly related to the RCX, they can be of particular value in working with the RCX.
* [com0com](https://github.com/BrickBot/Archive/releases/tag/com0com): A suite of drivers and tools offering virtual serial ports, serial port redirection, and more.  They can even open up new ways of interacting with an RCX via an IR tower.  Coupled with IR-Server in the BrickOS-Bibo repository, a sampling of additional scenarios and capabilities that can be enabled include the following:
  + Communicate with remote RCX devices
  + Enable apps without USB serial support to use USB towers
  + Enable apps without TCP serial support to work with emulators (which use TCP for their “virtual” IR connection)
  + Runs apps on a computer without driver support while connecting an IR tower to a computer with driver support
* [Original NetBeans IDE](https://github.com/BrickBot/Archive/releases/tag/NetBeans) (pre-Apache, as used to be available bundled with the JDK): Was used in the development of some open source software designed for the RCX (e.g. [VisualNQC](https://github.com/BrickBot/VisualNQC))

&nbsp;
## Backwards Compatibility Support
Dependencies and related software that might be of use if setting up a legacy environment or if attempting to run older software under newer operating system versions.
* [Windows Backwards Compatibility](https://github.com/BrickBot/Archive/releases/tag/Win9x): Includes the latest-and-greatest versions of dependencies and related software for setting up to run older apps, whether using a Windows 9x (Windows 95, Windows 98, Windows 98 SE, Windows ME) environment or a more modern one.
