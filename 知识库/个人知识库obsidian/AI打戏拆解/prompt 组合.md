## Prompt 模板库

### 核心原则

> **Prompt不是写作文，而是填表格。每个模块填一个关键词，组合起来就是完整的Prompt。**

---

### 一、Prompt 结构模板

```
[动作描述]，[镜头描述]，[特效描述]，[风格描述]，[画质描述]

示例：
A warrior slashes with a golden sword, slow motion, close-up on the blade,
golden energy trail following the sword, shockwave at impact,
dark void background with golden particles floating,
cinematic lighting, 8k, photorealistic, epic atmosphere
```

---

### 二、各模块词库

#### 2.1 动作动词库

| 动作  | 英文关键词                                    |
| --- | ---------------------------------------- |
| 挥剑  | slash, swing, cleave, cut                |
| 格挡  | block, parry, deflect                    |
| 突刺  | thrust, stab, pierce                     |
| 上挑  | uppercut, upward slash                   |
| 下劈  | overhead strike, downward slash          |
| 横斩  | horizontal slash, side sweep             |
| 翻滚  | roll, dodge, evade                       |
| 腾空  | leap, jump, aerial, airborne             |
| 瞬移  | teleport, blink, dash                    |
| 蓄力  | charge, gather energy, power up          |
| 连招  | combo, consecutive strikes, flurry       |
| 终结技 | finishing move, final blow, fatal strike |

#### 2.2 镜头描述库

|镜头|英文关键词|
|---|---|
|特写|close-up, extreme close-up|
|中景|medium shot, mid shot|
|全景|wide shot, full shot|
|远景|long shot, establishing shot|
|慢动作|slow motion, time dilation|
|跟随|tracking shot, follow cam|
|环绕|orbit, 360 rotation,环绕 shot|
|俯拍|top-down, bird's eye view, high angle|
|仰拍|low angle, up shot, worm's eye view|
|晃动|shaky cam, handheld, impact shake|
|推近|push in, dolly in, zoom in|
|拉远|pull out, dolly out, zoom out|
|定格|freeze frame, stop motion|

#### 2.3 特效描述库

| 特效   | 英文关键词                                        |
| ---- | -------------------------------------------- |
| 光效   | glowing, luminous, radiant, golden light     |
| 粒子   | particles, sparks, embers, dust motes        |
| 冲击波  | shockwave, blast wave, ripple, explosion     |
| 碎片   | debris, shards, fragments, splinters         |
| 拖尾   | trail, afterimage, motion blur, light trail  |
| 火焰   | fire, flame, blaze, inferno                  |
| 冰霜   | ice, frost, crystal, frozen                  |
| 雷电   | lightning, thunder, electricity, arc         |
| 烟雾   | smoke, mist, fog, haze                       |
| 能量残留 | energy residue, lingering light, fading glow |

#### 2.4 风格控制词库

|风格|英文关键词|
|---|---|
|**暗黑深空**|dark void, deep space, starry abyss, cosmic darkness, infinite darkness|
|**金色能量**|golden energy, amber light, metallic sheen, radiant gold, molten gold|
|**赛博仙侠**|cyber wuxia, neon xianxia, futuristic martial arts, ancient future|
|**水墨**|ink wash, brush stroke, ink splash, sumi-e, calligraphy|
|**法阵**|magic circle, rune, geometric pattern, glowing sigil, rotating runes|
|**符箓**|talisman, seal, burning paper, calligraphy charm|
|**蝴蝶**|butterfly, glowing wings, fluttering, luminous scales|
|**暗器**|shuriken, throwing dart, spinning blade, metal projectile|
|**机关**|gear, clockwork, mechanical parts, chain, cogwheel|
|**植物**|vine, flower, petal, thorn, blooming, withering|
|**星辰**|star, nebula, galaxy, constellation, cosmic dust|
|**雷电**|lightning, thunder, electric arc, crackling electricity|
|**冰霜**|ice, frost, crystal, frozen, snowflake|
|**时空**|space distortion, time rift, dimension tear, reality warp|
|**音律**|sound wave, musical note, resonance, vibration|
|**毒**|poison, venom, toxic mist, corrosive liquid|
|**圣光**|holy light, divine radiance, sacred beam, angelic glow|
|**暗黑**|dark blood, black mist, shadow, demonic energy|
|**幻影**|afterimage, phantom, clone, illusion, mirror image|

#### 2.5 画质描述库

|画质|英文关键词|
|---|---|
|电影级|cinematic, filmic, movie quality|
|高分辨率|8k, 4k, high resolution, ultra HD|
|写实|photorealistic, realistic, lifelike|
|艺术感|artistic, stylized, painterly|
|史诗感|epic, grand, majestic|
|氛围感|atmospheric, moody, ambient|

---

### 三、负面词库

#### 3.1 通用负面词

```
ugly, deformed, blurry, low quality, extra limbs, bad anatomy,
watermark, text, signature, logo, distorted, disfigured,
poorly drawn, mutation, mutilated, out of frame, cropped,
jpeg artifacts, worst quality, normal quality, lowres,
monochrome, grayscale, bad proportions, duplicate, morbid,
gross, missing limbs, floating limbs, disconnected limbs,
malformed hands, missing fingers, extra fingers, fused fingers,
bad hands, missing arms, extra arms, fused arms
```

#### 3.2 打戏专用负面词

```
static pose, no motion, stiff, floating, no impact,
slow motion only, no energy effect, no particles,
no sparks, no shockwave, no trail, no glow, no debris,
no dust, no wind, no cloth movement, no hair movement,
no facial expression, blank expression, no reaction,
no recoil, no hit reaction, no screen shake,
no camera movement, static camera, flat lighting,
no contrast, no shadow, no depth, no atmosphere
```

#### 3.3 风格专用负面词

```
bright, sunny, daytime, colorful, pastel, cartoon, anime style,
2D, flat, no depth, no atmosphere, no glow, no neon,
no cyberpunk, no sci-fi, no fantasy, no wuxia, no martial arts,
no sword, no weapon, no energy, no magic, no aura, no halo,
no light beam, no sparkle, no glitter, no shine, no reflection,
no metallic, no gold, no amber, no dark, no void, no space,
no starry, no abyss, no cosmic, no ethereal, no mystical,
no ancient, no futuristic, no hybrid, no fusion
```

---

### 四、Prompt 组合示例

#### 4.1 按情绪+风格组合

|场景|情绪|风格|完整Prompt|
|---|---|---|---|
|剑客月下最后一战|悲壮|水墨|A warrior performs a final slash, slow motion, wide shot, ink splash effect at impact, golden ink trail following the sword, dark void background with floating ink particles, cinematic lighting, 8k, photorealistic, epic atmosphere|
|火系战士复仇|愤怒|火焰|A warrior unleashes a fiery combo, close-up on the blazing sword, flame explosion at each hit, shockwave with fire ring, dark background with embers flying, handheld camera shake on impact, cinematic lighting, 8k, photorealistic|
|刺客暗杀|优雅|暗器|An assassin throws a shuriken, slow motion, close-up on the spinning blade, metal reflection, golden trail following the projectile, dark void background, silent except for the wind sound, cinematic lighting, 8k, photorealistic|
|道士驱魔|焦灼|符箓|A taoist priest summons burning talismans, medium shot, talismans circling around, each talisman explodes on impact, golden fire particles, dark background with smoke, fast camera switching, cinematic lighting, 8k, photorealistic|

#### 4.2 通用模板（可直接复制修改）

```
[A warrior/assassin/mage] [performs action], [camera description],
[effect description], [style description], [quality description],
negative prompt: [negative words]
```
