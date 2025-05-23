# 腾讯云DDNS Python脚本（第二版）

## 简介

本仓库提供了一个用于腾讯云DDNS（动态域名解析）的Python脚本文件，支持IPv4和IPv6。该脚本适用于Windows 7、10和11系统，压缩包内包含详细的注释文件和使用教程。只需简单修改配置文件即可实现每600秒刷新一次的DDNS功能。

## 功能特点

- **支持IPv4和IPv6**：该脚本能够同时处理IPv4和IPv6的动态域名解析。
- **自动刷新**：每600秒自动刷新一次，确保域名解析的实时性。
- **适用于Windows系统**：特别针对Windows 7、10和11系统进行了优化。
- **详细教程**：压缩包内附带详细的教程和注释文件，方便用户快速上手。

## 使用前提

1. **公网IP地址**：确保你的家庭网络拥有公网IPv4或IPv6地址。如果没有，请联系你的网络运营商（移动：10086，电信：10000，联通：10010）开通。
2. **闲置主机**：需要一台闲置的Windows主机，用于运行该脚本。
3. **腾讯云账户**：在腾讯云账户中拥有一个域名。
4. **电费和网费**：确保你有足够的资金支付电费和网费。

## 使用步骤

1. **下载并解压**：下载压缩包并解压到你的Windows主机上。
2. **修改配置文件**：打开`config.txt`文件，根据教程中的说明修改配置。
3. **运行脚本**：双击运行脚本文件，脚本将自动开始执行DDNS功能。

## 注意事项

- **IPv6兼容性**：部分旧路由器可能不支持IPv6，请确保你的路由器支持IPv6功能。
- **网络稳定性**：IPv6公网地址可能会导致部分软件访问失常或掉速，建议同时开通IPv4和IPv6以提高网络稳定性。
- **实验数据**：根据实验数据，30M的IPv4在IPv6情况下能跑40M，50M和100M同理。

## 更新说明

- **第二版**：修复了第一版中IPv4无法获取的问题，增强了脚本的稳定性和兼容性。

## 联系我们

如果在使用过程中遇到任何问题，欢迎通过GitHub Issues联系我们。

## 下载链接
[腾讯云DDNSPython脚本第二版](https://pan.quark.cn/s/9e65a4dfa892) 

(备用: [备用下载](https://pan.baidu.com/s/1Wi5BGNltfuUzpklLhsGDrw?pwd=1234))
