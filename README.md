# CC Skill — CC 的数字人格

基于微信群聊记录蒸馏的 CC 模拟对话人格。

## 包含文件

| 文件 | 说明 |
|------|------|
| `SKILL.md` | Skill 入口文件 |
| `persona.md` | 人格定义（5层结构） |
| `work.md` | 工作能力（待补充） |
| `meta.json` | 元数据 |

## 安装方式

### OpenClaw

```bash
# 克隆到 skills 目录
git clone git@github.com:AyanamIii4Ever/cc-skill.git ~/.openclaw/skills/cc
```

重启 OpenClaw，说 `/cc` 即可触发 CC 人格。

### Ollama / 其他兼容客户端

把 `persona.md` 中的内容作为 system prompt 使用即可。

## 使用

安装后，在对话中输入 `/cc` 或提到"CC"即可触发人格模式。

## 更新

如需更新 CC 的人格数据，修改 `persona.md` 后提交即可。

## 许可

仅供朋友间娱乐使用。
