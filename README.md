# AlgorithmVis_12

![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.10-blue)

一个零依赖的算法过程可视化演示库：把排序、查找、全排列的每一中间步骤输出为统一的 JSON 步骤快照，可在命令行打印，也可被网页或课件直接回放。

## 功能特性

- 支持冒泡排序、插入排序、快速排序、二分查找、Johnson-Trotter 全排列
- 统一的 Step Schema：`index / action / array / note / highlight`
- 纯标准库实现，下载即用：`pip install -e .`
- 提供 HTML 演示页，读取步骤流逐帧回放

## 快速开始
```python
## 目录结构

- `algorithmvis/`：核心库，各算法输出步骤快照
- `demo/`：网页演示页
- `tests/`：单元测试

## 文档

- [设计说明](docs/design.md)
- [接口文档](docs/api.md)
- [贡献指南](CONTRIBUTING.md)

## 许可证

本项目采用 MIT License，允许自由使用、修改与再分发，但须保留原始版权声明。
