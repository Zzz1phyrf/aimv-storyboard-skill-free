# AIMV Storyboard Skill

AI 视频 / MV 分镜脚本生成器。

这个 skill 用于把歌词、LRC、歌曲时长或主题设定转成可执行的 MV 分镜方案，输出资产图、故事板、分镜执行表和视频制作清单。

## 内容

- `SKILL.md`：skill 主文件
- `references/storyboard-guide.md`：分镜与镜头语言参考
- `references/prompt-engineering.md`：Prompt 写作参考

## 适用场景

- 给歌曲生成 AIMV / MV 分镜脚本
- 按场景切分画面，而不是一句歌词一张图
- 先锁定角色、场景和道具资产
- 生成 GPT Image 2 多宫格 storyboard sheet
- 输出分镜执行表、关键尾帧和视频制作清单

## 使用方式

把本仓库目录放到支持 skill 的 Agent / Codex skills 目录中，然后在对话中提出类似需求：

```text
帮我根据这首歌生成一个 MV 分镜脚本
```
