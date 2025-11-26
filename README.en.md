The project is an open-source implementation of an Enigma2-based Digital Video Broadcasting (DVB) system, primarily tailored for embedded devices such as set-top boxes. It includes a wide range of components for handling DVB services, user interfaces, multimedia playback, and hardware interactions.

---

## README

### Project Overview

This project is an open-source implementation of a Digital Video Broadcasting (DVB) system based on [Enigma2](https://github.com/OpenPLi/enigma2), primarily designed for embedded devices such as set-top boxes. It supports a wide range of functionalities, including DVB service handling, user interface management, multimedia playback control, and hardware interaction.

### Features

- **DVB Support**: Supports multiple DVB standards, including DVB-S (satellite), DVB-C (cable), DVB-T (terrestrial), and ATSC.
- **Hardware Control**: Provides control over audio/video outputs, HDMI CEC, infrared remote controls, and other hardware components.
- **EPG Support**: Supports automatic loading and caching of Electronic Program Guide (EPG) data.
- **User Interface**: Features an XML-based skin system supporting multiple languages and resolutions.
- **Network Streaming**: Supports media streaming via HTTP and HTTPS.
- **Recording and Playback**: Enables recording and playback of TV programs with timeshift functionality.
- **Plugin System**: Offers an extensible plugin architecture for integrating third-party functionalities.
- **Multilingual Support**: Supports multiple interface languages, including Chinese, English, German, French, and others.

### Directory Structure

- **data/**: Contains skins, fonts, icons, configuration files, and resource assets.
- **lib/**: Core functionality implementations, including DVB services, audio/video decoding, hardware control, and network stream handling.
- **lib/python/**: Python-based components and plugins for building the user interface and implementing business logic.
- **doc/**: Documentation and development guides.
- **include/**: C++ header files.

### Development Documentation

Development documentation is located in the `doc/` directory and includes:
- **BUTTONGUIDE**: Button operation guide.
- **DEFAULTS**: Default configuration explanations.
- **FILEFORMAT**: File format specifications.
- **NUMERICALTEXTINPUT**: Numerical text input methods.
- **PLUGINS**: Plugin development guide.
- **RETURNCODES**: Return code definitions.
- **RULES**: Development guidelines.
- **SKINS**: Skin development documentation.
- **SOURCES**: Source code structure overview.
- **TRANSLATIONS**: Multilingual support guide.
- **VIRTUALKEYBOARD**: Virtual keyboard usage instructions.

### Build and Deployment

This project uses `autotools` for build management and supports cross-platform compilation. Key dependencies include:
- **Python 2.x** (for certain components)
- **GStreamer** (for multimedia stream processing)
- **libdvb** (core DVB library)
- **libbase** (basic library for timers, threads, memory management, etc.)

Build steps:
1. Run `autogen.sh` to generate the `configure` script.
2. Execute `./configure` to configure the build environment.
3. Run `make` to compile the project.

### Usage

This project is primarily used to build DVB-based set-top box firmware, supporting reception and playback of satellite, cable, and terrestrial TV signals. The user interface is based on an XML skin system, allowing high customization.

### Contributions

Contributions, patches, and improvements are welcome. Please adhere to the project’s coding standards and test your code before submission.

### License

This project is licensed under the GNU General Public License v2.0 or later. For details, refer to the `LICENSE` file.

### Contact

- Project Maintainer: jackgee2021 (https://gitee.com/jackgee2021)
- Project Homepage: [Gitee Enigma2 OpenPLi](https://gitee.com/jackgee2021/enigma2-openpli)