# Nano Banana Pro 2 提示词编写规则指南

## 一、提示词结构（推荐顺序）

Nano Banana Pro 2 对 **结构化提示词** 的理解最好，推荐按照下面顺序写：

```
主体 → 风格 → 细节 → 构图 → 光线 → 色彩 → 材质 → 背景 → 质量参数 → 比例
```

完整示例：

```
A West Highland White Terrier,
flat vector illustration,
small triangular nose, fluffy fur, short muzzle,
center composition,
soft studio lighting,
white and light pastel color palette,
smooth matte texture,
clean pastel background,
ultra clean design,
3:4 aspect ratio
```

---

# 二、核心提示词模块

## 1 主体（Subject）

必须 **最先明确主体**。

规则：

* 先说 **是什么**
* 再说 **品种 / 类型**
* 再说 **状态 / 动作**

结构：

```
主体 + 类型 + 动作
```

示例：

```
a West Highland White Terrier standing
a cute corgi sitting
a retro handheld game console
a futuristic cyberpunk city
```

避免：

❌

```
cute dog
beautiful animal
```

太模糊。

---

# 2 风格（Style）

Nano Banana 对 **风格关键词非常敏感**。

建议放在主体后。

示例：

```
flat illustration
vector illustration
3D render
pixel art
anime style
minimalist design
isometric illustration
watercolor painting
```

示例：

```
flat vector illustration
```

---

# 3 形态细节（Shape / Anatomy）

这是 **控制生成准确度的关键部分**。

写法：

```
尺寸 + 形状 + 特征
```

例如：

```
small triangular nose
short rounded muzzle
large round eyes
fluffy fur
thick tail
```

控制比例：

```
short muzzle
tiny nose
wide face
long ears
```

例子：

```
small triangular nose,
short muzzle,
fluffy white fur
```

---

# 4 构图（Composition）

控制 **画面布局**。

常用词：

```
center composition
symmetrical composition
close-up portrait
full body view
top-down view
isometric view
minimal composition
```

示例：

```
center composition
```

---

# 5 光线（Lighting）

光线影响 **质感和氛围**。

常见：

```
soft studio lighting
natural daylight
cinematic lighting
rim lighting
dramatic lighting
soft shadow
```

示例：

```
soft studio lighting
```

---

# 6 色彩（Color）

建议写 **配色策略**，而不是单个颜色。

示例：

```
pastel color palette
warm color palette
monochrome palette
black and gold color scheme
high contrast colors
neon cyberpunk colors
```

例子：

```
light pastel color palette
```

---

# 7 材质（Material / Texture）

对质感控制很强。

常见：

```
smooth matte texture
glossy plastic
metallic surface
paper texture
grainy film texture
ceramic material
```

例子：

```
smooth matte texture
```

---

# 8 背景（Background）

建议 **简单明确**。

示例：

```
clean background
solid pastel background
gradient background
studio background
transparent background
minimal background
```

例子：

```
clean pastel background
```

---

# 9 质量词（Quality Tags）

用于提高 **细节质量**。

常见：

```
high detail
ultra clean design
sharp edges
professional illustration
high resolution
studio quality
```

示例：

```
ultra clean design
```

---

# 10 比例（Aspect Ratio）

Nano Banana 对比例比较敏感。

常用：

```
1:1
3:4
4:5
9:16
16:9
```

例子：

```
3:4 aspect ratio
```

---

# 三、完整模板（推荐）

你可以直接用这个模板：

```
[主体],
[风格],
[形态细节],
[构图],
[光线],
[色彩],
[材质],
[背景],
[质量],
[比例]
```

示例：

```
A West Highland White Terrier,
flat vector illustration,
small triangular nose, short rounded muzzle, fluffy white fur,
center composition,
soft studio lighting,
light pastel color palette,
smooth matte texture,
clean pastel background,
ultra clean design,
3:4 aspect ratio
```

---

# 四、进阶控制技巧

## 1 负面约束（避免错误）

可以加入 **避免词**：

```
no text
no watermark
no logo
no blur
no distortion
```

例子：

```
no text, no watermark
```

---

## 2 强化权重

通过 **重复或强调**：

```
very small nose
extremely fluffy fur
super clean background
```

---

## 3 精准比例控制

例如：

```
very small triangular nose
short compact muzzle
large round eyes
```

用于 **控制脸型比例**。

---

# 五、常见错误

### 错误 1：关键词堆砌

❌

```
cute dog beautiful animal nice illustration high quality
```

太模糊。

---

### 错误 2：顺序混乱

❌

```
soft lighting dog vector illustration cute fluffy
```

---

### 错误 3：过多风格

❌

```
anime watercolor pixel art oil painting
```

风格冲突。

---

# 六、Nano Banana Pro 2 最佳提示词长度

建议：

```
10 — 20 行关键词
```

太短 → 信息不足
太长 → 可能冲突

---

# 七、终极万能模板（推荐保存）

```
[主体 + 类型 + 动作],
[艺术风格],
[关键形态细节],
[构图方式],
[光线类型],
[色彩方案],
[材质质感],
[背景描述],
[质量标签],
[比例]
```

---

如果你愿意，我还能给你做一版 **「Nano Banana Pro 2 专用高级提示词模板」**，比如：

* **动物插画模板**
* **产品设计模板**
* **LOGO设计模板**
* **电商海报模板**

那一版会 **非常适合你做设计用**，生成稳定度会高很多。
