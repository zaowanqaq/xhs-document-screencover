# 知识文档屏拍封面｜Xiaohongshu Document Screencover

把真实的知识文档整理成适合小红书阅读的封面：**用文档的目录、正文和表格展示内容，再用少量标题点出价值**。

适合飞书文档、Notion、知识库和工作手册，也适合把电商、运营、AI 工具等资料做成有信息量的图文。Skill 关注内容依据、真实页面、视觉层次和交付核验；不保证流量或转化。

## 效果示例

<table>
<tr><td align="center" width="50%"><b>封面试稿</b><br/><sub>AI 生成的模拟屏拍，基于自建文档；不是实拍照片。</sub></td><td align="center" width="50%"><b>文档页面示例</b><br/><sub>另一份自建飞书文档的真实截图，用于展示内容层次。</sub></td></tr>
<tr><td><img src="assets/example-ai-screencover.png" alt="AI 模拟的知识文档屏拍风封面试稿" width="100%"/></td><td><img src="assets/example-document-screenshot.png" alt="包含电商任务与选品说明的真实文档截图" width="100%"/></td></tr>
</table>

两张图片来自不同文档，展示的是同一种方法，并非同一页面的前后对比。生成图可能重绘或改写文字，发布前需核对；参考素材须有使用权并处理个人信息。

## 它做什么

- **先读资料**：根据指定范围核对来源，找出真实、具体的工作问题和可用信息。
- **整理文档**：使用真实的飞书、Notion 或其他文档，组织目录、正文、清单和必要说明。
- **制作画面**：保留可读内容与页面结构，适度使用黄色重点和简短标题，按需要制作屏拍感试稿。
- **检查交付**：区分真实截图与 AI 模拟，检查图片文字、来源及隐私；按用户授权保存到指定位置。

## 安装到 Codex

让 Codex 使用 `$skill-installer` 安装此仓库根目录的 Skill：

```text
使用 $skill-installer 安装 https://github.com/zaowanqaq/xhs-document-screencover，
仓库中的 Skill 路径为 .，安装名称为 xhs-document-screencover。
```

也可以在已安装 Codex 的环境中运行：

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo zaowanqaq/xhs-document-screencover \
  --path . --name xhs-document-screencover
```

如果系统中的 Codex 主目录不是 `~/.codex`，请将脚本路径替换为实际目录。安装后开始新的对话，再使用该 Skill。

## 使用示例

```text
使用 $xhs-document-screencover：
先读我提供的电商资料，整理一份飞书文档，展示 5 个具体工作场景及需要准备的数据。
再基于真实文档制作一张小红书知识类封面，保留目录和正文，浅黄色标记重点。
请区分真实截图和 AI 生成的模拟屏拍，并核对图片中的文字。
```

还可以用于「运营复盘清单」「Notion 知识库介绍」「AI 工具教程」等主题。对于没有侧栏的原始文档，保留真实结构，不凭空添加目录。

## 工作边界

- 不把 AI 合成屏幕冒充真实截图、真实拍摄或实际使用成果。
- 不凭文件名编造功能、结果、用户评价或数据；资料未读完时说明覆盖范围。
- 不默认发布笔记、发送消息、修改分享权限或上传第三方素材。
- 屏拍、截图和内容使用方式以你对素材的授权及目标平台规则为准。

## 文件

- [`SKILL.md`](SKILL.md)：完整的 Skill 指令。
- [`agents/openai.yaml`](agents/openai.yaml)：Codex 界面信息。
- [`assets/`](assets/)：经检查的示例图片。