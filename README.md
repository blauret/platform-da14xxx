# Dialog Smartbond: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-ststm32.svg?branch=develop)](https://travis-ci.org/platformio/platform-ststm32)
[![Build status](https://ci.appveyor.com/api/projects/status/y5dayom6bltenoeh/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-ststm32/branch/develop)

The Dialog Smartbond family of 32-bit Flash MCUs based on the ARM Cortex-M processor is designed to offer new degrees of freedom to MCU users who wish to build conected device. It offers a 32-bit product range that combines very high performance, real-time capabilities, digital signal processing, and low-power, low-voltage operation, while maintaining full integration and ease of development.

* [Home](https://github.com/blauret/platform-da14xxx) (home page in PlatformIO Platform Registry)
* [Documentation](https://github.com/blauret/platform-da14xxx/wiki) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = da14xxx
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/blauret/platform-da14xxx
board = ...
...
```

# Configuration

Please navigate to [documentation](https://github.com/blauret/platform-da14xxx/wiki).
