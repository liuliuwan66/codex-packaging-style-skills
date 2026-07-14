# Codex Packaging Style Skills

这个仓库包含两个 Codex skill：

- `styleskill`：分析包装设计参考图，输出变量注入框和 Image2 中文风格复刻提示词。
- `styleskill-imagegen`：分析包装设计参考图，跳过提示词正文输出，直接调用图像生成工具出图。

## 安装位置

将对应文件夹复制到 Codex 默认 skill 目录：

```text
~/.codex/skills/
```

## 使用方式

在 Codex 中上传包装设计参考图后，可分别调用：

```text
$styleskill
$styleskill-imagegen
```
