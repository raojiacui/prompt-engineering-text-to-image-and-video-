# 🎬 AI 视频提示词创作指南

> 这里复刻网上各大热门 AI 视频的提示词创作脚本，跟着我的创作脚本走，你也能早日学会创造出 AI 视频神作！

本仓库收录了我在 AI 文生视频领域的创作探索，涵盖多种风格与主题的提示词工程实践。

---

## 📂 仓库内容概览

### 热门系列

| 系列 | 文件 | 简介 |
|------|------|------|
| 🏚️ **反乌托邦宿舍** | `反乌托邦宿舍系列AI视频提示词.md` | 3000层垂直宿舍系列，社会阶级分化主题，7个镜头 |
| 💭 **AI梦核视频** | `AI梦核视频提示词.md` | 意识流、梦核感原创视频提示词 |
| 🍜 **无限美食空间** | `无限美食空间系列提示词.md` | 美食+超现实空间创意系列 |
| 🫧 **魔法食物球** | `魔法食物球视频提示词.md` | 球体入水变美食的魔法转变系列 |
| ✨ **超现实画册** | `超现实创意画册视频提示词.md` | 画册中物体冲破二维束缚的创意 |
| ⛺ **胶囊帐篷** | `capsule-tent-video-prompts.md` | 胶囊展开为高科技帐篷的创意 |
| 💇 **头发狂想ASMR** | `头发狂想ASMR提示词.md` | 8镜头发超现实转变，ASMR视觉体验 |
| 🏹 **ARROW** | `ARROW_Video_Prompts.md` | 独立创意视频提示词 |
| 🏯 **东方玄幻** | `东方玄幻系列AI视频提示词.md` | 东方玄幻风格视频提示词 |

### 教程文档

| 文件 | 用途 |
|------|------|
| `video-editing-guide.md` | 视频剪辑综合指南 |
| `剪辑教程.md` | 基础剪辑教程 |
| `梦核视频拼接教程.md` | 梦核风格视频拼接教程 |
| `Remotion视频拼接文档.md` | Remotion 框架拼接教程 |

---

## 🔥 精选系列详解

### 反乌托邦宿舍系列

基于 **如果你...了，请选择你的...** 系列创意，探讨3000层垂直宿舍中的社会寓言：

```
1. 3000层宿舍啃食混凝土 - 学生疯狂啃食混凝土墙面
2. 宿舍与办公室的交叉剪辑 - 蓝领宿舍 vs 金领办公室
3. 外卖员被困楼梯间 - 狭仄胶囊空间中的挣扎
```

### AI梦核视频系列

参考 **DiDi_OK** 的 **如果世界真的是程序，你会继续当个NPC吗** 系列风格，探索意识流与梦核感：

- 现实与梦境边界的模糊表达
- 日常物品的超现实转变
- 时间与空间的错位感

---

## 📝 提示词模板

每个提示词都遵循统一的专业结构：

### 1. 动态叙事脚本

```markdown
Final Prompt (EN): |
  [事件全貌]: A continuous shot showing [主体] performing [复杂的物理动作序列].

  [时空演变]:
  - Start: [起始画面描述]
  - Action: [中间发生的物理变化]
  - End: [结束画面描述]

  Camera Movement: [运镜方式]
  Physics/Details: [物理细节描述]
  Visual Bible: [Lighting, Color, Texture 定义]
```

### 2. 生成参数

```markdown
Parameters:
  aspect_ratio: 16:9
  duration_s: [时长]
  physics_simulation: [物理模拟关键词]
  consistency_guard: [风格约束关键词]
  negative: [需要避免的问题]
```

---

## 🚀 使用方法

1. **克隆仓库**
   ```bash
   git clone https://github.com/raojiacui/video-prompts.git
   ```

2. **选择感兴趣的系列**，参考其中的提示词结构

3. **替换关键元素**，创作自己的视频提示词

4. **搭配 AI 视频生成工具使用**
   - Sora 2
   - Veo 3.1
   - Kling
   - 可灵

5. **使用 Remotion 拼接**（见 `Remotion视频拼接文档.md`）

---

## 💡 创作心得

- **物理真实性**：重视 physics_simulation 描述，让AI理解真实的物理规律
- **镜头语言**：明确的 Camera Movement 指导能大幅提升生成质量
- **风格一致性**：Visual Bible 部分确保跨镜头风格统一
- **Negative Prompt**：明确避免的问题同样重要

---

## 📚 相关项目

- [nano-video](https://github.com/raojiacui/nano-video) - AI 视频生成 SaaS 平台
- [remotion-video-edit](https://github.com/raojiacui/remotion-video-edit) - Remotion 视频编辑项目

---

> 本仓库仅供学习交流，提示词灵感来源于各大平台热门 AI 视频创作。
