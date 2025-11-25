# mysql-checker
**一条命令 docker run --rm 生成 40 项《MySQL 等保 2.0 巡检报告》+ 整改脚本，10 分钟完成月度安检**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)  
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](src/check.py)  

## 🚀 核心功能
- ✅ **40 项等保 2.0 自动检查** - 基于国家标准
- ✅ **HTML 可视化报告** - 风险等级颜色标识  
- ✅ **自动修复脚本** - 一键生成整改 SQL
- ✅ **Docker 容器化** - 开箱即用

## 📦 快速开始
```bash
# 开发中，预计第 3 天可用
docker run --rm ghcr.io/WEIli1215/mysql-checker:latest