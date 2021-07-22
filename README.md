English | [简体中文](./readme-zh-CN.md)

# MugglePayForWHMCS8
> MugglePay is a one-stop payment solution for merchants with an online payment need.

![logo-whmcs.png](https://i.loli.net/2021/07/11/BZxGuml4HwEVpOz.png)

# Integration guide
## Requirements
* WHMCS v8.2.0 (8.2.0-release.1) or above

## Integration instructions 
1. Download the latest release [here](https://github.com/hoythan/MugglePayForWHMCS8/releases/).
1. Copy modules folder to <whmcs_dir>
1. Open WHMCS Admin area
1. Navigate to Setup -> Payments -> Payment Gateways
1. Activate MugglePay in All Payment Gateways
1. Register your MugglePay merchant accounts with your invitation code and get your API key at [Merchants Portal](https://merchants.mugglepay.com/user/register?ref=MP9237F1193789). You will find your API Auth Token (API key) for authentication. [MORE](https://merchants.mugglepay.com/user/register?ref=MP9237F1193789)
1. Set you API key in Manage Existing Gateways

![image.png](https://i.loli.net/2021/07/11/J5Z6RXQCib3qSnm.png)
![image.png](https://i.loli.net/2021/07/19/RAE4xvd9m8lP6wa.png)

# Changelog
## 1.0.2 ##
1. Cancel automatic payment redirection, it is now an optional configuration item
## 1.0.1 ##
1. Allow custom payment methods
2. Add JS URLSearchParams polyfill
## 1.0.0 ##
1. First Version