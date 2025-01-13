# 主动防御溯源工具 (Active Defense Tracing Tool)

![GitHub stars](https://img.shields.io/github/stars/yourusername/active-defense-trace)
![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)




项目前提，我每天都会收到大量的恶意IP进行分析，那么开发个工具来自动化吧，输入甲方甩过来的恶意IP，一键输出日报，领导领导我完事了

## 📝 项目简介

帮助苦逼溯源人员快速分析和追踪可疑IP与域名。

## ✨ 核心功能

- 🔍 **IP/域名解析**
  - 支持批量IP和域名分析
  - 智能识别输入类型
  - DNS解析与反向解析

- 🌍 **地理位置定位**
  - 集成纯真IP数据库
  - 精确定位IP地理信息
  - 自动更新地址库

- 🔒 **端口扫描**
  - 常用服务端口检测
  - 服务类型识别
  - 网站标题获取

- 📊 **报告生成**
  - 自动生成分析报告
  - 支持多种导出格式
  - 日报模板支持

## 🚀 程序演示

![图片](https://github.com/user-attachments/assets/06d39b31-aba9-4a38-b5ad-d9ccc1cbfd9f)

运行
![图片](https://github.com/user-attachments/assets/8937be96-5616-4707-9b34-33a35117d1e6)



## 🛠️ 程序所应用的技术栈

- Python 3.6+
- PyQt5 - GUI界面框架
- Requests - HTTP请求处理
- BeautifulSoup4 - 网页解析
- QQWry - IP地址库
- DNSPython - DNS解析
- GeoIP2 - IP地理位置服务

## 🎯 使用场景

- 安全事件响应
- 可疑IP/域名分析
- 网络资产梳理
- 安全态势感知
- 日常安全运维

## 📌 注意事项

- 仅限用于主动防御项目，溯源HVV，请勿用于非法用途
- 建议在合法授权下使用
- 扫描前请确认目标授权

## 🤝 参与贡献

欢迎提交 issue 和 PR！

## 📄 开源协议

[MIT License](LICENSE)

---
> 🔔 给个star 支持呗！
