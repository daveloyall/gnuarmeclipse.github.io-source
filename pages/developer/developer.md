---
layout: page
permalink: /developer/
title: GNU ARM Eclipse Developer page
author: Liviu Ionescu

date: 2015-09-10 18:31:00 +0300

---

## Under the hood

### Runtime preferences

* [How Eclipse runtime preferences and defaults work]({{ site.baseurl }}/developer/eclipse/runtime-preferences)
* [ilg.gnuarmeclipse.managedbuild.cross]({{ site.baseurl }}/developer/preferences/ilg.gnuarmeclipse.managedbuild.cross) persistent values & toolchain ids
* [ilg.gnuarmeclipse.debug.gdbjtag.jlink]({{ site.baseurl }}/developer/preferences/ilg.gnuarmeclipse.debug.gdbjtag.jlink) persistent values (workspace)
* [ilg.gnuarmeclipse.debug.gdbjtag.openocd]({{ site.baseurl }}/developer/preferences/ilg.gnuarmeclipse.debug.gdbjtag.openocd) persistent values (workspace)
* [ilg.gnuarmeclipse.debug.gdbjtag.qemu]({{ site.baseurl }}/developer/preferences/ilg.gnuarmeclipse.debug.gdbjtag.qemu) persistent values (workspace)

### Debugging options

* [How Eclipse debugging options work]({{ site.baseurl }}/developer/eclipse/debugging-options)
* [Platform tracing facility](https://wiki.eclipse.org/FAQ_How_do_I_use_the_platform_debug_tracing_facility)

### GNU ARM Eclipse extension points

The GNU ARM Eclipse plug-ins define several custom extension points, to facilitate the integration with third-party plug-ins.

* [ilg.gnuarmeclipse.debug.core.cprojectExtra]({{ site.baseurl }}/developer/extension/ilg.gnuarmeclipse.debug.core.cprojectextra) (C Project Extra Data Manager)
* [ilg.gnuarmeclipse.debug.core.svdPath]({{ site.baseurl }}/developer/extension/ilg.gnuarmeclipse.debug.core.svdpath) (SVD Path Manager)

## Miscellaneous

* [Eclipse Development Tips & Tricks]({{ site.baseurl }}/developer/eclipse/tips-tricks)
* [PAD file]({{ site.baseurl }}/developer/pad-file)

## How to build

How to build the plug-ins from sources and publish them.

* [Prerequisites]({{ site.baseurl }}/developer/build-prerequisites)
* [How to build]({{ site.baseurl }}/developer/build-procedure)
* [How to publish]({{ site.baseurl }}/developer/publish-procedure)
* [Development environment]({{ site.baseurl }}/developer/development-environment)
* [Change log]({{ site.baseurl }}/developer/change-log) ([2014]({{ site.baseurl }}/developer/change-log/2014)) ([2013]({{ site.baseurl }}/developer/change-log/2013)) ([v0.5.x]({{ site.baseurl }}/developer/change-log/v05x))

## Hardware

* [J-Link and STM32 boards]({{ site.baseurl }}/developer/j-link-stm32-boards) (how to build a cable to connect the J-Link to STM32 DISCOVERY and NUCLEO boards)

## References

### Eclipse

*   [Eclipse.org Wiki](http://wiki.eclipse.org/Main_Page)
*   [Eclipse User Interface Guidelines](http://wiki.eclipse.org/User_Interface_Guidelines)
*   [SWT Widgets](http://www.eclipse.org/swt/widgets/)
*   [Eclipse Luna documentation](http://help.eclipse.org/luna/index.jsp)
*   [Introduction to Programming with DSF](http://help.eclipse.org/luna/topic/org.eclipse.cdt.doc.isv/guide/dsf/intro/dsf_programming_intro.html)
*   [CDT DSF debug](http://wiki.eclipse.org/CDT/cdt-debug-dsf-gdb-extensibility)

### Other

*   [ARM CMSIS](http://www.keil.com/pack/doc/cmsis/General/html/index.html)
*   [ARM Connected Community: ARM & Keil Tools](http://community.arm.com/groups/tools/blog)
*   [Google Groups: CMSIS](https://groups.google.com/forum/#!forum/cmsis)
*   [Forge site support \#6343 Project description not propagated to all tools](https://sourceforge.net/p/forge/site-support/6343/)

### Installers

*   [NSIS](http://nsis.sourceforge.net/Main_Page)
*   [Single Package](http://blogs.msdn.com/b/windows_installer_team/archive/2009/09/02/authoring-a-single-package-for-per-user-or-per-machine-installation-context-in-windows-7.aspx)


### References to GNU ARM Eclipse

- [Getting Started With STM32 Nucleo Development](http://www.amazon.com/Getting-Started-STM32-Nucleo-Development-ebook/dp/B00WBU4BPW)

### Sites for articles

* [ARMConnected Community](https://community.arm.com/welcome) - login, Create a new Blog Post, A place's blog, Software Development Tools, copy/paste markup from site, H2, update links, enter tags
* [Element14](http://www.element14.com/community/groups/open-source-software) - login, the Open Source Software; Write a blog post, copy/paste from ARM, load images, enter tags
* [EmbDev](https://embdev.net/user/login) - New Topic to [Forum: ARM programming with GCC/GNU tools](https://embdev.net/forum/arm-gcc); no pictures; underline headers (no BBCs)
* [EEVblog](http://www.eevblog.com/forum/login/) - [Microcontrollers & FPGAs](http://www.eevblog.com/forum/microcontrollers/); New topic, BBC codes (bold titles, image links to web article), Notify
* [Arduino](http://stm32duino.com/viewforum.php?f=41) - New Topic, copy/paste content from EEVblog; disable signature, enable notifications
* [STM32 MCUs Community](https://community.st.com/community/stm32-community) - Sign in to forum, New Discussion, copy/paste HTML from Arduino (a real mess)

BBC codes:
- `[img width=30]http:⁄⁄wiki.simplemachines.org/smf/images/1/19/Button_media.png[/img]`
- `[url=http://simplemachines.org]text or more BB Code[/url]`

## Releases

* [releases]({{ site.baseurl }}/developer/releases)
