# PDF 转 Word 工具 🔄

![GitHub release](https://img.shields.io/badge/版本-v1.2.0-green)

一款本地运行的 PDF 转 Word 文档工具，专注处理文本型 PDF 文件转换


## 🎯 功能特性

- 快速转换文本型 PDF 文件
- 保留原始排版格式（表格/列表/标题）
- 自动识别文档编码
- 批量转换支持（最多同时处理50个文件）
- 转换进度实时显示
- 失败文件自动隔离

⚠️ **重要限制**  
不支持图片型/扫描版 PDF 转换（会触发错误提示）

## 🛠️ 技术栈

- Python 3.11
- pdfplumber（PDF解析）
- python-docx（Word生成）
- PyQt5（GUI界面）
- PyInstaller（打包工具）

## 📦 安装指南

### 直接使用
1. 下载最新版 [pdf_to_word_tool.exe](https://github.com/yourusername/pdf_to_word_tool/releases)
2. 双击运行（无需安装依赖）
