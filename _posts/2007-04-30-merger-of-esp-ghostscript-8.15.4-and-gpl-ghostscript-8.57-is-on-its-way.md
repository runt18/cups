---
title: Merger of ESP Ghostscript 8.15.4 and GPL Ghostscript 8.57 is on its way
layout: post
---

As the head branch of Ghostscript is now under GPL (and not only the


- Enhanced PCL XL driver: Duplex and tray selection support
- Shared library and driver (X11) support for Linux/UNIX: Now distributions can have one binary Ghostscript package for both server and desktop
- The "cups" output device that generates a series of raster images for CUPS printer drivers.
- Nearly all known free printer drivers which have to be compiled into Ghostscript - drivers listed with "Execution style: Ghostscript" in the OpenPrinting database. Not included are some obsolete drivers such as hpdj which is replaced by the included pcl3 driver.
- All known Uniprint configuration files (*.upp) as listed on OpenPrinting database
- Patches to add the NOMEDIAATTRS option to Ghostscript, which allows CUPS drivers to use media options separate from Ghostscript
- KRGB support for IJS drivers (not yet completed)
- OpenPrinting Vector interface
- Support files for CUPS
- Enhanced build system
