**English** | [简体中文](../README.md) | [Türkçe](../tr/README.md)

# Device Faker 📱

<img src="../assets/icon.svg" width="96" alt="logo">

A device model spoofing module based on Zygisk that can configure different device models for different applications.

[![Version](https://img.shields.io/github/v/release/Seyud/device_faker_release?logo=github)](https://github.com/Seyud/device_faker_release/releases/latest)
[![GitHub Downloads](https://img.shields.io/github/downloads/Seyud/device_faker_release/total?logo=github&logoColor=green)](https://github.com/Seyud/device_faker_release/releases)
[![Language](https://img.shields.io/badge/language-Rust-orange?logo=rust&logoColor=orange)](https://www.rust-lang.org/)
[![Telegram](https://img.shields.io/badge/group-Telegram-2CA5E0?logo=telegram&logoColor=87CEEB)](https://t.me/device_faker)

## Official Website 🌐

[![Website](https://img.shields.io/badge/website-visit-2ea44f?style=for-the-badge&logo=google-chrome&logoColor=white)](https://seyud.github.io/device_faker/en/)

## Features ✨

- 🎯 **Precise Control**: Configure device information individually for each application, only takes effect on configured apps
- 📁 **Template Management**: Multiple device templates, easily apply to multiple package names
- 🔄 **Real-time Effect**: After modifying configuration, just restart the application, no need to restart the system
- 🛡️ **Safe and Reliable**: Based on Zygisk framework, modular design
- 📝 **Simple Configuration**: Using TOML format configuration files, easy to edit
- 🎭 **Unified Execution Flow**: No mode selection needed, automatically schedules JNI field spoofing, COW property spoofing and companion services
- 🔒 **COW Property Engine**: mmap copy-on-write property spoofing, per-process isolation with zero residency
- 🌐 **WebUI Management**: Provides graphical interface for convenient configuration management

## WebUI Features 🖥️

Device Faker provides a modern web management interface.

- 📋 **Template Management**: Create, edit and delete device templates, batch apply to multiple package names
- 📱 **Application Management**: Intuitive view of installed applications and their configuration status, supports multi-user apps display
- 🖋️ **Configuration Editing**: Graphical interface for editing application configuration, supporting template application and custom configuration
- 🌍 **Multilingual**: 简体中文, English, Türkçe

## Configuration Guide ⚙️

For detailed configuration instructions, please refer to the [Configuration Documentation](CONFIG.md).

The configuration file is located at `/data/adb/device_faker/config/config.toml` and uses TOML format. After modifying the configuration, just restart the corresponding application to take effect, no need to restart the system.

## Documentation 📚

- [Configuration Guide](CONFIG.md) - App / template options, property spoofing mechanism and priority
- [Changelog](CHANGELOG.md) - Release history
- [Official Website](https://seyud.github.io/device_faker/en/) - Usage guides and FAQ

## Template Configuration Contribution 🎁

Thanks to community contributions! You can also participate! Device Faker configuration repository:

- 📦 [device_faker_config](https://github.com/Seyud/device_faker_config) - Contribute device template configurations

Contribute device configurations to help more users get better device spoofing results!

## Acknowledgments 🙏

This project references the following excellent projects during development:

- [zygisk-dump-dex](https://github.com/ri-char/zygisk-dump-dex) - Provides prototype reference for Rust Zygisk module development
- [zygisk-api-rs](https://github.com/rmnscnce/zygisk-api-rs) - Provides Rust dependency support for Zygisk API
- [MiPushZygisk](https://github.com/wushidia/MiPushZygisk) - Provides reference for Zygisk device spoofing solutions

Thanks to the developers of these projects! 💖

---

**📱 Let devices not be limited by application model restrictions!** 🚀

> 💝 If this module helps you, please give it a ⭐ Star for support
