# daily-photo-playground

一个将日常摄影照片重构为 3:4 竖版高饱和情绪作品页的 Codex skill。

它强调“暖白外部页面 + 重构版心”的两级结构，并保留：

- 保留真实摄影质感、放大切出的人物
- 简化但可识别的场景插画（海、沙滩、树、街道等 2–5 个代表性元素）
- 1 个完整可读的小型原照片窗口
- 0–3 个来自原图的辅助几何元素
- 进入中央构图、克制有层级的文字排版
- 连续留白与点线面关系

## 文件

- `SKILL.md`：skill 主说明与工作流程
- `references/composition-specification.md`：四层结构、空间比例与质量检查规范
- `agents/openai.yaml`：Codex 显示信息与默认提示词

## 使用

将此目录作为 `daily-photo-playground` skill 使用，并通过 `$daily-photo-playground` 调用。
