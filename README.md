# 鱼眼张力海报 Skill / Fisheye Tension Poster Skill

输入一个关键词，生成一张 **9:16 霓虹青色天空 + 极端鱼眼 + 巨型酸性黄字体 + 普通人英雄时刻 + 90 年代末实验编辑印刷感** 的写实海报。

## 它能做什么

- 理解关键词（中文、英文、成语、短句都行），自动把它变成一位真实普通人：职业、年龄气质、服装、巅峰动作、前景道具
- 极低机位鱼眼镜头，前景道具/肢体放大 2–4 倍，人物占画面 60–75%
- 2–4 词英文大写主标题，像建筑一样立在人物身后并在边缘裁切；可选 4–10 字中文小字；3–5 组微型元数据
- 严格三段配色 + 硬光 + 细腻印刷质感
- 不追问、不展示分析，只出一张图

## 安装

**作为 Agent Skill（Claude Code / Cursor / Codex 等）**：把整个文件夹复制到对应的 skills 目录，例如：

```bash
git clone https://github.com/ericchan916/fisheye-tension-poster-skill.git
cp -r fisheye-tension-poster-skill ~/.claude/skills/fisheye-tension-poster
# 或 ~/.cursor/skills/、~/.codex/skills/ 等
```

**在 ChatGPT / 其他图像模型中使用**：打开 [`prompt.md`](prompt.md)，全文复制粘贴，把 KEYWORD 换成你的关键词即可。

## 使用示例

```
@创建图片 KEYWORD：［反者道之动 弱者道之用］
@创建图片 KEYWORD：［守护］
@创建图片 KEYWORD：［KEEP GOING］
```

更多关键词与建议标题见 [`examples/keywords.md`](examples/keywords.md)。

## 配色

| 角色 | 占比 | 颜色 |
|---|---|---|
| 天空主色场 | 55–65% | 饱和青 / 松石绿 / 电光蓝绿 |
| 字体 | 20–30% | 荧光酸性黄 / 柠檬黄 / 高可视黄绿（哑光） |
| 暖色强调 | 10–15% | 红 / 珊瑚 / 朱红 / 洋红 / 暖橙 / 铁锈红 |
| 中性色 | 其余 | 米白、炭灰、自然肤色、旧灰、褪色黑、哑光金属 |

## 文件结构

```
SKILL.md              # Agent skill 定义（含可直接粘贴的提示词模板）
prompt.md             # 完整独立提示词
examples/keywords.md  # 示例关键词与建议标题
LICENSE
```

## English

**Fisheye Tension Poster** turns a single keyword into one photorealistic 9:16 editorial poster: an ordinary person at the peak of a real action, shot from an extreme low fisheye angle against a neon cyan sky, with a monumental acid-yellow ALL CAPS headline standing behind them like architecture, finished with late-1990s print texture. Drop the folder into your agent's skills directory, or paste `prompt.md` into ChatGPT or any image model.

## License

MIT © 2026 Joy Robinson — 见 [LICENSE](LICENSE)。生成图片的使用请同时遵守你所用图像模型的服务条款。
