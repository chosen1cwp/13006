# 软件工程实践考试 - PlantUML 图仓库

本仓库用于管理 [北京自考 - 202504 学期 - 实践考试《软件工程》](https://www.example.com)（课程编码：13006）中绘制的 **PlantUML 图**，包括用例图、活动图、类图、时序图等 UML 模型。

---

## 📌 项目说明

- **课程名称**：软件工程（实践考试）
- **课程编码**：13006
- **学期**：202504
- **图示工具**：PlantUML
- **目标**：通过可视化 UML 模型，辅助完成干洗店洗衣管理系统等相关软件设计任务

---

## 🧩 环境依赖

推荐使用 [IntelliJ IDEA](https://www.jetbrains.com/idea/) 或 [Android Studio](https://developer.android.com/studio) 搭配插件进行编辑和预览。

### 必装插件：

1. [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)
2. Graphviz（用于生成图像）
   - macOS 安装：`brew install graphviz`
   - Windows 安装：[Graphviz 官网下载](https://graphviz.org/download/)

---

## 🛠 使用方法

### 在 IDEA 中打开仓库：

1. 打开 IntelliJ IDEA，`File -> Open` 选择本项目文件夹。
2. 确保插件已安装并启用。
3. 打开 `.puml` 文件，即可实时预览图形。

### 生成图片（可选）：

如果需要批量导出 PNG 图片，可使用命令行方式：

```bash
java -jar plantuml.jar *.puml

