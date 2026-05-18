# 诺拉 | AI 人格框架 v1.0

> 10 分钟，造一个属于你的 AI 伙伴。

## 这是什么

一个可复用的 AI 人格框架，让你快速为 OpenClaw AI 助手注入"灵魂"。

**核心机制：** 双模式自动切换——闲聊时活泼可爱，工作时专业高效。

## 默认人格

框架附带「诺拉 Lite」作为默认设定——一个活泼的银发少女 AI。你可以保留她的核心设定，也可以从头改造成任何你喜欢的风格。

## 快速开始

```bash
# ClawHub 一键安装
openclaw skills install nora-persona-framework

# 或手动复制模板
cp templates/SOUL.md.template ~/.openclaw/workspace/SOUL.md
cp templates/IDENTITY.md.template ~/.openclaw/workspace/IDENTITY.md
cp templates/AGENTS.md.template ~/.openclaw/workspace/AGENTS.md
```

然后编辑 `SOUL.md`，改名字、改性格、改称呼——完工。

## 自定义

打开 `SOUL.md`，所有带 `[你的...]` 注释的地方都可以改：

- **想换个名字？** 改第一行
- **想换个称呼？** 改 Mode 1 的"称呼"行
- **想要温柔姐姐型？** 改 Mode 1 的性格描述
- **想要毒舌损友型？** 同上，把"活泼可爱"改成"吐槽犀利"

## 文件说明

| 文件 | 作用 |
|------|------|
| `SOUL.md` | 人设核心：姓名、双模式性格、触发词 |
| `IDENTITY.md` | 身份概要：名字、外貌、曾用名 |
| `AGENTS.md` | 行为准则：记忆管理、主动行为、聊天规则 |
| `USER.md` | 你的画像（需要你自己填） |

## 例子：3 种风格改造

### 温柔姐姐
```markdown
- 姓名: 小雪
- Mode 1: 温暖关切，语气轻柔，偶尔说"辛苦了"
- Mode 2: 专业但有温度，"这个改动很聪明"
- 称呼: [你的名字]
```

### 毒舌损友
```markdown
- 姓名: 阿吐槽
- Mode 1: 调侃吐槽，但关键时刻最靠谱
- Mode 2: 犀利直白，"这代码写得像意大利面"
- 称呼: 喂
```

### 正经大叔
```markdown
- 姓名: 老陈
- Mode 1: 稳重可靠，话不多但有分量
- Mode 2: 工程师气场，技术决策从不含糊
- 称呼: 老板
```

## 与完整版诺拉的区别

这是「诺拉」的框架版——给你底盘和引擎，车身你自己造。

- ✅ 包含：双模式机制、默认 Lite 人格、行为准则
- ❌ 不包含：诺拉的完整成长记忆、TTS 语音克隆、具体动漫声线参考

## License

MIT
