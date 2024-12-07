# Webdriver Manager Mirrored for Python

This is a forked version of webdriver_manager, with the main improvement being the replacement of foreign software sources in the original repository, making it more suitable for users in mainland China.

## Key Features

- Fully compatible with all features of the original webdriver_manager
- Replaced download sources for Chrome, Firefox, and other browser drivers with domestic mirrors
- No need for VPN or proxy to use normally
- Supports Selenium 4.x and below versions

## Supported Browser Drivers

- ChromeDriver
- GeckoDriver (Firefox)
- OperaDriver

## Installation

```bash
pip install webdriver-manager-mirrored
```

## Major Changes

Compared to the original version, the main modifications are as follows:

- Replaced ChromeDriver download source with Taobao mirror
- Replaced GeckoDriver download source with domestic mirror
- Other driver download sources also use domestic mirrors when possible
- Removed dependency on GitHub API

## Contributing

Issues and Pull Requests are welcome to help improve this project.

## License

This project uses the same open source license as the original webdriver_manager. 
