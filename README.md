# 搜建筑导航站

> 建筑规范一站式查询与分类导航平台

[![GitHub](https://img.shields.io/badge/GitHub-qiushanyueyue-blue)](https://github.com/qiushanyueyue/soujianzhu)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 🌟 功能特点

- **🔍 规范搜索** - 一键搜索建筑规范，快速跳转搜建筑网站
- **📂 分类导航** - 按类型整理规范（通用规范、抗震规范、地基基础等）
- **📋 规范目录库** - 预置141条常用建筑规范，自动加载无需手动导入
- **✅ 批量添加** - 支持勾选多个规范，一键添加到指定分类
- **📥 模板下载** - 提供标准Excel模板，按格式填写后批量导入
- **🎨 现代界面** - 响应式设计，玻璃态效果，支持折叠分类

## 🚀 快速开始

### 在线访问

访问 [sjz.108923.xyz](https://sjz.108923.xyz) 直接使用

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/qiushanyueyue/soujianzhu.git

# 进入目录
cd soujianzhu

# 直接打开 index.html 即可使用
open index.html
```

## 📖 使用指南

### 搜索规范
1. 在搜索框输入规范关键词
2. 点击搜索按钮或按回车
3. 自动跳转到搜建筑搜索结果页

### 添加规范到分类
1. 点击右上角「规范目录查看添加」按钮
2. 在弹窗中搜索或浏览规范列表
3. 勾选需要的规范
4. 点击「添加到分类」选择目标分类
5. 规范自动添加到主页对应分类

### 上传自定义规范
1. 点击「下载模板」获取Excel模板
2. 按模板格式填写规范数据
3. 点击「上传Excel」导入数据

## 🛠️ 技术栈

- **React** - 用户界面
- **Tailwind CSS** - 样式框架
- **SheetJS (XLSX)** - Excel文件处理
- **Font Awesome** - 图标库

## 📁 项目结构

```
soujianzhu/
├── index.html          # 主页面（单文件应用）
├── README.md           # 项目说明
├── package.json        # 项目配置
└── 规范目录库.xlsx      # 规范数据源
```

## 📝 更新日志

### v1.0.0 (2026-01-19)
- ✨ 初始版本发布
- 🎉 预置141条建筑规范数据
- 📥 支持Excel模板下载和上传
- ✅ 批量勾选添加到分类功能
- 🔍 规范搜索过滤功能

## 📄 许可证

MIT License © 2026

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

Made with ❤️ for architects and engineers
