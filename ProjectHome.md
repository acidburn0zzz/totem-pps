This project provides a set of plugins for gstreamer and totem (gst-plugins-pps and totem-pps) for linux users.  The gst-plugins-pps enables gstreamer powered media player to play ppstream streamings such as the url which has a prefix "tvod://" or "pps://" . And totem-pps adds a kan.pps.tv play list to totem. With both plugins installed, you can browser and play videos from kan.pps.tv with totem.

# Install guides #
[Install plugins from source.](http://code.google.com/p/totem-pps/wiki/HowToInstall)

[How to get the lastest sources.](http://code.google.com/p/totem-pps/wiki/GetLastestDevelopmentSource)

[How to install totem-pps on ubuntu.](http://code.google.com/p/totem-pps/wiki/InstallGuideForUbuntu)

# Useful scripts #
[a browser script to let you play ppsream videos on http://kan.pps.tv](http://userscripts.org/scripts/source/59991.user.js)

# Releases #
  * Feb 6 2010, the 0.0.20rc1 released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.5.tar.gz)

> Changes:
    1. go to previous, first and specificed page in file list works now.
    1. the recent list reworked too.

  * Jan 22 2010, the 5th unstable version of 0.0.19 serials is released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.4.tar.gz)

> Changes:
    1. be compatible with old pygtk
    1. support movies which have a large amout of files.

  * Dec 31 2009, the fourth unstable version of 0.0.19 serials is released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.3.tar.gz)

> Changes:
    1. fixed the issue: goto previous page is broken
    1. fixed the issue: a offset by one bug in search result paging
    1. fixed the issue: movies in favorite list can't be played

  * Dec 27 2009, the third unstable version of 0.0.19 serials is released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.2.tar.gz)

> Changes:
    1. rework the recent/favorites list(they were broken for previous releases)
    1. hide the add/remove favorites button if the active list is the categories list
    1. code cleanup and add tooltip for some widgets

> Known issues:
    1. goto previous page is broken [Fix](http://cgit.freedesktop.org/~jinghua/totem-pps/patch/?id=96e973b1efd50fcec6e78e66f2baa19b9af30816)
    1. a offset by one bug in search result paging [Fix](http://cgit.freedesktop.org/~jinghua/totem-pps/patch/?id=41c845b3bfe9d8c10cf12ef2796b735d89ca7be7)

  * Dec 26 2009, the second unstable version of 0.0.19 serials is released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.1.tar.gz)

> Changes:
    1. search functionality is implemented
    1. the plugin doesn't download all pages in a movie category any more

  * Dec 24 2009, the first unstable version of totem-pps 0.0.19 is released. [Download](http://totem-pps.googlecode.com/files/totem-pps-0.0.19.tar.gz)

> NOTE: Please install BeautifulSoup before enabling the totem ppstream plugin.