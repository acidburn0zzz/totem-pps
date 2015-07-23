# Introduction #
Steps to install totem-pps from source tarballs.


# Details #
## Firstly, You have to install a few libraries provided by pps.tv. ##
  * Download this tarball, http://download.ppstream.com/linux/release_for_ubuntu.tgz
  * Untar the tarball with command
```
    $tar zvxf release_for_ubuntu.tgz
    $cd release_for_ubuntu
```
  * Copy the config file to your system
```
    $cp ppscdn_config.ini /etc
```
  * Another tarball named libs\_for\_ubuntu.tgz should be in directory release\_for\_ubuntu. Please untar this tarball too.
```
    $tar zvxf libs_for_ubuntu.tgz
```
  * What we need is the libpps**.so**, so copy them to your system library path for example
```
    $cp libs/libpps*so* /usr/lib -a
```

## Secondly, You have to install a gstreamer plugin to play pps:// or tvod:// streams. ##
  * Download libppswrapper-$version.tar.gz and gst-plugins-$version-tar.gz from the home page of [totem-pps](http://code.google.com/p/totem-pps)
  * Install libppswrapper. Before installing it, please ensure gcc and g++ and libc develop packages are installed.
```
    $tar zvxf libppswrapper-$version.tar.gz
    $cd libppswrapper-$version
    $./configure --prefix=/usr
    $make && sudo make install
```
  * Then install the gstreamer plugin. You have to install gstreamer and gst-plugins-base  development packages to compile it.
```
    $tar zvxf gst-plugins-pps-$version.tar.gz
    $cd gst-plugins-pps-$version
    $./configure --prefix=/usr
    $make && sudo make install
```

## Lastly, install the totem plugin. ##
  * Download totem-pps-$version-tar.gz from the home page of [totem-pps](http://code.google.com/p/totem-pps)
  * Install the plugin. Before installing it, please ensure totem, python and **beautifulsoup** are installed on your system.
```
    $tar zvxf totem-pps-$version.tar.gz
    $cd totem-pps-$version
    $./configure --prefix=/usr
    $make && sudo make install
```

# Run the totem-pps #
  * Start the totem
  * Enable totem-pps by check the totem ppstream button in totem's plugin configure dialog(Menu->Edit->Plugins...).
  * Select the ppstream siderbar and enjoy it.