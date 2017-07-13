# Clipped
Search and paste from your clipboard history.

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.davidmhewitt.clipped)

![Clipped Screenshot](https://github.com/davidmhewitt/clipped/raw/master/data/com.github.davidmhewitt.clipped.screenshot.png)

## Building, Testing, and Installation

You'll need the following dependencies to build:
* cmake
* libgtk-3-dev
* valac
* libsqlite3-dev


## How To Build

    git clone https://github.com/davidmhewitt/clipped
    cd clipped
    mkdir build && cd build 
    cmake -DCMAKE_INSTALL_PREFIX=/usr ..
    make
    sudo make install
