---
layout: plugin

id: AutostartPrint
title: AutostartPrint
description: Autostart a print job after conneting.
author: Olli
license: AGPLv3

date: 2019-09-23

homepage: https://github.com/OllisGit/OctoPrint-AutostartPrint
source: https://github.com/OllisGit/OctoPrint-AutostartPrint
archive: https://github.com/OllisGit/OctoPrint-AutostartPrint/releases/latest/download/master.zip

# Set this to true if your plugin uses the dependency_links setup parameter to include
# library versions not yet published on PyPi. SHOULD ONLY BE USED IF THERE IS NO OTHER OPTION!
#follow_dependency_links: false

tags:
- printer

screenshots:
- url: https://github.com/OllisGit/Octoprint-AutostartPrint/raw/master/screenshots/plugin-settings.png
  alt: Plugin Settings
  caption: Plugin Settings
- url: https://github.com/OllisGit/Octoprint-AutostartPrint/raw/master/screenshots/countdown-dialog.png
  alt: Countdown Dialog
  caption: Countdown Dialog
  

---

The Plugin starts a print job after the Printer is connected (e.g. after powering up). It selects the newest uploaded file for print.

For implementation details please visit the [homepage]({{ page.homepage | absolute_url }}).
