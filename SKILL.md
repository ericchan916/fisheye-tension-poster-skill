---
name: fisheye-tension-poster
description: 鱼眼张力海报：根据一个关键词（中文或英文）生成一张 9:16 霓虹青色天空 + 极端低机位鱼眼 + 巨型酸性黄英文标题 + 普通人英雄时刻 + 90 年代末实验编辑印刷感的写实海报。当用户输入 "@创建图片 KEYWORD：［...］"、或要求"鱼眼海报 / 张力海报 / 霓虹天空海报"时使用。Use when the user asks for a fisheye tension poster, a neon-cyan-sky fisheye editorial poster, or sends "@创建图片 KEYWORD：[...]" — turns one keyword into a single 9:16 photorealistic poster with one ordinary-person hero, a fisheye-magnified prop, and monumental acid-yellow typography.
license: MIT
---

# 鱼眼张力海报 · Fisheye Tension Poster

把一个抽象关键词变成一个真实普通人的巅峰动作，用极低机位鱼眼、巨型酸性黄字体和青色天空拍成一张 9:16 实验编辑海报。
Turn one abstract keyword into a single ordinary-person hero moment, shot with an extreme low fisheye against a cyan sky and monumental acid-yellow type.

## 使用方法 · How to use

输入格式 / Input format:

```
@创建图片 KEYWORD：［反者道之动 弱者道之用］
```

1. 读取 KEYWORD（中文、英文或短语皆可）。不要追问人物、职业、动作、服装或道具。
2. 内部完成下文全部决策（不输出分析）。
3. 将 [prompt.md](prompt.md) 的完整规则 + 你的决策交给图像生成工具，**只输出一张**最终海报。
4. 若当前环境不能生图，则输出下方"可直接粘贴的最终提示词"，已填好 KEYWORD，供用户粘贴到 ChatGPT / 其他图像模型。

完整规则见 [prompt.md](prompt.md)；示例关键词见 [examples/keywords.md](examples/keywords.md)。

## 核心规则 · Core rules

### 输出规格 · Output
- 恰好 1 张写实实验编辑海报，9:16 竖版，恰好 1 位成年人。
- 无拼贴、无分屏、无多版本、无样机框、无品牌 logo、无水印、无 UI。
- 风格：neon cyan sky + extreme fisheye + monumental acid-yellow typography + ordinary-person heroism + late-1990s experimental editorial print。

### 关键词解析 · Keyword interpretation
不要只把关键词印在画面上。把它转化为：性格力量 → 可真实拍摄的人物身份 → 与身份相关的行动 → 推向镜头的代表性道具 → 符合职业逻辑的服装 → 有冲击力的英雄时刻。人物可以来自任何真实普通的职业或生活身份，但必须与关键词有内在关联；用动作体现关键词，而非字面图解。

### 人物 · Character
明确但不刻板的身份；可信的年龄感与身体状态；有力量、有性格，不是超级英雄——像真实普通人被拍出英雄感。身份可从服装、动作、道具读出；性别、年龄、发型、体型、气质由关键词决定。

### 服装 · Wardrobe
由关键词、职业、环境、动作、功能需求和整体配色共同推导；不预设红色或固定服装。保留一个暖色强调（red / coral / vermilion / warm orange / magenta / rust / deep pink），可出现在衣物局部、手套、帽子、袜子、鞋、围裙、护具、道具、包袋、绳索、工具手柄等，占画面 **10–15%**。

### 动作 · Action
与身份相关的巅峰张力瞬间；清晰对角线穿越画面中心；向前/向上/横向动势，像要冲出画面。不用无关的随机夸张姿势，不让职业人物做不合理的运动动作。

### 道具 · Prop
一个与职业或行动直接相关的核心道具；离镜头最近之一，被鱼眼夸张放大；与身体真实连接；推向镜头但不完全遮挡人物；有真实材质、重量和使用痕迹；不是装饰物，不拍成产品广告。

### 镜头 · Camera lock
相机几乎贴地、极低机位、镜头猛烈向上、极近前景道具或最近肢体；强鱼眼曲率与近大远小。最近肢体/道具为正常比例 **2–4 倍**；头部与上身自然缩小；天空向四周弯曲。禁止：眼平视角、普通广角人像、中长焦、无畸变、远距离全身、常规时尚低机位、无动作逻辑地放大鞋子。

### 比例 · Scale
人物占画面 **60–75%**；头部清晰；身体沿对角线穿越中心；人物部分遮挡标题；道具不能遮住整张脸；透视夸张但解剖合理——畸变来自镜头，不来自肢体变异。

### 字体 · Typography
- **主标题**：2–4 个英文单词，ALL CAPS，自然有力，不生硬直译、不空洞口号。fluorescent acid yellow，ultra-heavy grotesk sans serif，极紧字距，2–4 行堆叠，超出画面并在左/右/上边缘裁切，像建筑一样立在人物**后方**，被身体和道具部分遮挡但仍清晰可读。
  - 示例：守护→STAY ON GUARD / HOLD THE LINE；重启→START AGAIN / BACK IN MOTION；专注→STAY SHARP / EYES ON IT；生长→KEEP GROWING / BUILT TO BLOOM；自由→BREAK THE LIMIT / MOVE YOUR WAY。
- **中文辅助文字**（可选）：4–10 个汉字，非逐字翻译，极小字号，放边缘或底部。
- **微型元数据**：3–5 组，每组 1–3 个英文词，可含一个时间数字（如 `ROOT / RISE / 06:40`、`CITY SHIFT / DAY 018`），小号宽字距无衬线，散布边缘；无品牌、网址、二维码、乱码。

### 配色 · Palette
| 角色 | 占比 | 颜色 |
|---|---|---|
| 天空主色场 Field | 55–65% | saturated cyan / turquoise / electric teal |
| 字体 Type | 20–30% | fluorescent acid yellow / lemon / hi-vis yellow-green, matte |
| 暖色强调 Accent | 10–15% | red / coral / vermilion / magenta / warm orange / rust |
| 中性色 Neutrals | 其余 | off-white, charcoal, skin tones, worn gray, faded black, muted metal |

禁止彩虹配色，禁止同时堆大量紫/绿/橙/粉/蓝。

### 环境 · 光线 · 印刷
- 环境：大面积干净青色天空；只留极少身份线索（屋顶边缘、天台、球场地面、脚手架、街道标线、海边栏杆、工厂墙角等），不抢戏。
- 光线：硬直射阳光、锐利图形化阴影、强对比、清晰皮肤与面料纹理、亮边高光、天空略过曝。
- 印刷：细腻胶片颗粒、轻微网点、柔化印刷边缘、轻微油墨扩散、哑光纸、克制的套色偏移、轻微表面磨损、平涂大色块。

### 构图锁定 · Composition lock
人物、道具、字体必须相互重叠；标题在人物后方。禁止"左人右字"排版、禁止人物缩小居中、禁止标题挡住整个人。冲击力来自透视、比例和排版，而不是堆元素。

### 禁止项 · Negative constraints
多人/人群/重复人物/背景路人；眼平视角、常规站姿、长焦、平透视、远景全身；T 台模特、网红脸、超级英雄服、无理由披风、预设红衣、固定服装模板、随机职业、无关动作、无关装饰道具；密集城市背景、复杂场景、彩虹/彩虹渐变；花哨字体、手写标题、优雅衬线、细字体、小标题、不可读标题、过多文字；logo、水印、二维码、网址、UI；拼贴、分屏、3D 渲染、矢量插画、CGI 塑料皮肤、重度模糊、极端运动模糊；畸形手、多指、肢体融合、不可能姿势、生成错误导致的脸部扭曲；随机汉字、英文拼写错误。

### 执行规则 · Execution rule
自动完成：语义解析 → 人物身份 → 背景 → 年龄气质 → 服装材质 → 暖色位置 → 巅峰动作 → 前景道具 → 英文标题 → 中文辅助 → 微型元数据 → 场景线索 → 鱼眼透视 → 字体遮挡关系 → 最终布局。只锁视觉系统，不锁具体人物；不同关键词必须产生明显不同的人物、动作、服装和道具。**不提问、不展示分析、不给多个候选，直接输出一张海报。**

## 可直接粘贴的最终提示词 · Ready-to-paste prompt template

```
@创建图片
KEYWORD：［{{KEYWORD}}］

Create exactly ONE photorealistic 9:16 vertical experimental editorial poster with exactly one adult person. Style: neon cyan sky + extreme fisheye perspective + monumental acid-yellow typography + ordinary-person heroism + late-1990s experimental editorial print.

Interpret the KEYWORD (meaning, emotional intensity, cultural context) and embody it through ONE real, ordinary, specific person — occupation/life role, believable age and physique — caught at the peak moment of a real action tied to that role, body on a strong diagonal through the frame center, surging toward the lens. One core prop directly tied to the role, real weight and wear, physically connected to the body, thrust toward the camera and fisheye-magnified 2–4x, never hiding the whole face. Wardrobe derived from role, environment, action and function; one warm accent (red/coral/vermilion/warm orange/magenta/rust/deep pink) placed naturally on clothing detail, gloves, shoes, tools or prop, ~10–15% of frame.

Camera: ultra-wide fisheye almost touching the ground, extreme low angle pointing sharply up, very close to the nearest limb/prop; strong curvature, sky bending outward; person fills 60–75% of frame; head small but clearly readable; anatomy correct — distortion from perspective only.

Typography: a natural 2–4 word ALL CAPS English headline distilled from the keyword (not a literal translation, not a slogan), fluorescent acid yellow, ultra-heavy grotesk sans, very tight tracking, stacked 2–4 lines, oversized and cropped at the left/right/top edges, standing like architecture BEHIND the person, partly blocked by body and prop yet clearly readable. Optional tiny Chinese subline of 4–10 characters (not a literal translation) at an edge. 3–5 tiny wide-tracked English metadata beats (1–3 words each, may include one time number, e.g. "ROOT / RISE / 06:40") scattered at the edges.

Palette: 55–65% saturated cyan/turquoise/electric teal sky; 20–30% matte acid yellow type; 10–15% single warm accent; neutrals off-white, charcoal, skin, worn gray, faded black, muted metal. Minimal environment cue that proves the role (rooftop edge, scaffold, court floor, street marking, seaside railing…). Hard directional sunlight, sharp graphic shadows, crisp textures, slightly overexposed sky. Print finish: fine film grain, subtle halftone, soft print edges, minor ink spread, matte paper, restrained misregistration, faint wear.

Composition: person, prop and title must overlap; no "person left, text right" layout; no small centered person; title never in front covering the person.

Negative: no multiple people, crowd, duplicates or pedestrians; no eye-level, standing pose, telephoto, flat perspective or distant full body; no runway model, influencer face, superhero costume, unjustified cape, predetermined red outfit, fixed wardrobe, random occupation, unrelated action or decorative prop; no dense city or complex scenery; no rainbow palette or gradient; no ornate, handwritten, serif, thin, small or unreadable headline; no excessive text; no logo, watermark, QR code, website or UI; no collage, split screen, 3D render, vector illustration, CGI plastic skin, heavy or extreme motion blur; no deformed hands, extra fingers, fused limbs, impossible pose or distorted face; no random Chinese characters; no misspelled English.

Do not ask questions. Do not show analysis or alternatives. Output the single finished poster only.
```
