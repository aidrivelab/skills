# Midjourney 提示词模板 / Midjourney Prompt Template

## 模型特点

- 英文为主，理解复杂艺术描述
- 支持详细构图和风格参数
- 提示词顺序影响权重

## 提示词结构

```
[主体描述] + [构图/布局] + [风格/材质] + [光照] + [色彩] + [参数]
```

## 模板示例：拆解海报

### 机械键盘拆解

```
Mechanical keyboard decomposition poster, exploded view showing keycaps, switches, PCB board, case, and stabilizers arranged in a clean grid layout, tech industrial style, blueprint aesthetic with grid lines and measurement marks, dark blue gradient background with cyan neon accents, studio lighting, 3:4 aspect ratio --ar 3:4 --v 6 --style raw
```

### 时尚穿搭拆解

```
Fashion outfit decomposition poster, exploded view showing tops, pants, shoes, bag and accessories arranged in elegant layout, fashion magazine style, minimalist white background with golden accents, professional studio lighting, 3:4 aspect ratio --ar 3:4 --v 6 --style raw
```

## 常用参数

| 参数 | 说明 | 示例 |
|------|------|------|
| --ar | 宽高比 | --ar 3:4 |
| --v | 模型版本 | --v 6 |
| --style | 风格 | --style raw |
| --s | 风格强度 | --s 250 |
| --iw | 图像权重 | --iw 0.5 |

## 拆解海报必备关键词

### 构图

- `exploded view` / `decomposition layout` / `exploded diagram`
- `clean grid` / `organized arrangement` / `scientific layout`
- `top-down view` / `front view`

### 风格

- `blueprint aesthetic` / `technical drawing` / `schematic style`
- `minimalist` / `modern` / `professional`
- `magazine style` / `commercial photography`

### 背景

- `gradient background` / `solid color background`
- `dark theme` / `light theme`
- `studio lighting` / `soft lighting`

## 输出格式

直接输出英文提示词，无需额外说明。
