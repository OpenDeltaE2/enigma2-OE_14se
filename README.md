The project is an open-source implementation of an Enigma2-based digital video broadcasting (DVB) system, primarily tailored for embedded devices such as set-top boxes. It includes a wide range of components for handling DVB services, user interfaces, multimedia playback, and hardware interactions.

---

## README

### 项目简介

该项目是基于 [Enigma2](https://github.com/OpenPLi/enigma2) 的开源数字视频广播 (DVB) 系统实现，主要用于嵌入式设备如机顶盒。该项目支持多种功能，包括 DVB 服务处理、用户界面管理、多媒体播放控制、硬件交互等。

### 功能特点

- **DVB 支持**：支持多种 DVB 标准，包括 DVB-S（卫星）、DVB-C（有线）、DVB-T（地面）和 ATSC。
- **硬件控制**：提供对音视频输出、HDMI CEC、红外遥控器等硬件的控制功能。
- **EPG 支持**：支持电子节目指南 (EPG) 的自动加载和缓存。
- **用户界面**：提供基于 XML 的皮肤系统，支持多语言和多种分辨率。
- **网络流媒体**：支持通过 HTTP 和 HTTPS 流媒体传输。
- **录制与播放**：支持电视节目的录制和回放，并提供时间平移功能。
- **插件系统**：提供插件扩展机制，支持第三方功能集成。
- **多语言支持**：支持多种语言界面，包括中文、英文、德语、法语等。

### 目录结构

- **data/**：包含皮肤、字体、图标、配置文件和资源文件。
- **lib/**：核心功能实现，包括 DVB 服务、音频/视频解码、硬件控制、网络流处理等。
- **lib/python/**：基于 Python 的组件和插件，用于构建用户界面和实现业务逻辑。
- **doc/**：文档和开发指南。
- **include/**：C++ 头文件。

### 开发文档

开发文档位于 `doc/` 目录，包括：
- **BUTTONGUIDE**：按钮操作指南。
- **DEFAULTS**：默认配置说明。
- **FILEFORMAT**：文件格式说明。
- **NUMERICALTEXTINPUT**：数字文本输入方法。
- **PLUGINS**：插件开发指南。
- **RETURNCODES**：返回码定义。
- **RULES**：开发规范。
- **SKINS**：皮肤开发文档。
- **SOURCES**：源码结构说明。
- **TRANSLATIONS**：多语言支持指南。
- **VIRTUALKEYBOARD**：虚拟键盘使用说明。

### 构建与部署

该项目使用 `autotools` 进行构建管理，支持跨平台编译。主要依赖项包括：
- **Python 2.x**（部分组件）
- **GStreamer**（用于多媒体流处理）
- **libdvb**（DVB 核心库）
- **libbase**（基础库，如定时器、线程、内存管理等）

构建步骤：
1. 运行 `autogen.sh` 生成 `configure` 脚本。
2. 执行 `./configure` 以配置构建环境。
3. 执行 `make` 编译项目。

### 使用

本项目主要用于构建基于 DVB 的机顶盒固件，支持卫星、有线和地面电视信号的接收与播放。用户界面基于 XML 皮肤，支持高度定制化。

### 贡献

欢迎开发者提交补丁和改进。请遵循项目编码规范，并在提交前测试代码。

### 授权协议

本项目使用 GNU General Public License v2.0 或更高版本授权。有关详细信息，请参阅 `LICENSE` 文件。

### 联系方式

- 项目维护者：jackgee2021 (https://gitee.com/jackgee2021)
- 项目主页：[Gitee Enigma2 OpenPLi](https://gitee.com/jackgee2021/enigma2-openpli)

---