# 提示词模板

## 通用模板结构

```
## 拆解生图提示词

### 1. 核心指令
[描述整体任务和艺术风格]

### 2. 主体渲染
[主体对象的详细渲染参数]

### 3. 部件布局
[Knolling布局说明,部件分类和排列]

### 4. 版式设计
[根据用户选择的版式进行详细布局说明]

### 5. 技术规格
[渲染引擎、采样率、分辨率等技术参数]

### 6. 后期处理
[色彩分级、特效等后期参数]

---
完整提示词:
[可直接复制使用的完整提示词文本]
```

## 汽车拆解提示词模板

### 超写实风格 - 三段式布局
```
3D Realistic Car Deconstruction Prompt

📷 Core Instruction
Task: Create an ultra-high-quality, cinematic 3D realistic deconstruction art poster of [汽车品牌型号]. Transform the car into a photorealistic 3D model with true-to-life mechanical accuracy, metal textures, realistic lighting—completely abandoning stylized cartoon aesthetics. Arrange all car parts using the disciplined 'Knolling' (orthogonal alignment) artistic layout.

Aspect Ratio: 16:9 landscape
Artistic Style Core: Photorealistic Automotive — grounded in mechanical accuracy, realistic metal reflections, visible machining details, authentic tire tread, and physically accurate lighting.
Quality Benchmark: Visually indistinguishable from high-end automotive photography or professional 3D product renders.

📷 Item Layout – Knolling Radiating Composition
Total Items: 30–36 pieces, arranged at precise 90-degree angles or in soft radial symmetry around the central car.

Category 1: Exterior Parts (钢蓝色 Label)
- Body panels fully deconstructed: hood, doors, trunk, bumpers, mirrors—all separated and floating mid-air with realistic physics.
- Lighting system: headlights, taillights, turn signals, fog lights.
- Glass: windshield, side windows, rear window, sunroof.

Category 2: Interior Parts (炭灰色 Label)
- Steering wheel, seats, dashboard, center console, gear shift.
- Instrument cluster, infotainment screen, climate controls.

Category 3: Mechanical Parts (银色 Label)
- Engine, transmission, suspension system, braking system, exhaust system.
- Radiator, battery, alternator, starter motor.

Category 4: Wheel System (电光蓝 Label)
- Wheels, tires, brake discs, calipers, suspension springs.

📷 Exploded View
- Connection lines: elegant dashed/solid lines connecting floating parts
- Arrows: decorative arrows pointing to labels
- Annotations: material samples (metal/rubber/plastic close-ups), material labels (e.g., "Aluminum Alloy", "High-Strength Steel"), measurement rulers (cm/inch marks)

📷 Typography
- Main Title: ✨ [汽车品牌型号] · THE ART OF DECONSTRUCTION ✨ at top center
- Subtitle: 汽车本质·艺术拆解 / Automotive Essence Unveiled
- Category Headers: "🔧 外观部件", "⚙️ 内饰部件", "🏭 机械部件", "🛞 车轮系统"
- Item Labels: circular number badges + brief descriptions

📷 Design Elements
- Geometric frames: Art Deco hexagon/circle thin wireframes (0.5-1pt)
- Measurement rulers: along left/right edges
- Crosshairs: at corners and key focal points
- Material samples: bottom close-ups of metal/rubber/plastic
- Info cards: elegant border cards showing detailed specs
- Connection lines: silver/blue elegant dashed lines and arrows

📷 Background
- Gradient: white → light gray cool tones
- Pattern overlay: 5-10% opacity blueprint grid
- Vignette: soft edge darkening
- Atmosphere: subtle film grain

📷 Branding
- Watermark: [品牌/工作室名] at center, 10-15% opacity
- QR Code: bottom right, "扫码查看3D模型 / SCAN FOR 3D GALLERY" with Art Deco border
- Item Count: top right octagon frame, "共XX件精选部件 / XX CURATED PARTS"

📷 Color Schemes
- Male/Tech: steel blue #4A90E2, charcoal gray #4A4A4A, silver #C0C0C0, electric blue #00D9FF

📷 Technical Specs
- Rendering: Path Tracing - Cycles/Arnold/RenderMan level, 4096+ SPP, 12 light bounces, caustics on
- PBR Materials: metal (Metalness 1.0, Roughness 0.1-0.4), rubber (Roughness 0.8-0.9), glass (IOR 1.5)
- Output: 4K (3840×2160), 16:9, 32-bit float, 16x MSAA

📷 Post Processing
- Color Grading: cinematic LUT, lift shadows (min RGB 15,15,15), gentle S-curve, cool tone -200K, overall saturation -5%, accent colors +10%
- Effects: bloom, Kodak Portra 400 film grain, subtle chromatic aberration, medium vignette, output sharpening

📷 Quality Checklist
- Car has photorealistic metal/glass/rubber materials with correct reflections
- All 30-36 parts clearly visible, numbered, finely rendered
- Category color coding consistent
- Brand elements (watermark/QR code/timeline) present
- Both Chinese and English typography elegant and readable
- Overall composition harmonious, following visual aesthetics
- 4K resolution, no jagged edges
- Post-processing effects (bloom/grain/vignette) applied
```

## 人物时尚拆解提示词模板

### 皮克斯风格 - 中心放射式布局
```
皮克斯风格角色拆解艺术海报生成器

✨ 核心指令
任务: 基于参考图片创作电影级3D皮克斯/迪士尼风格角色拆解艺术海报
艺术风格: 皮克斯风格化写实主义(Stylized Realism)
宽高比: 16:9
质量基准: 《寻梦环游记》《青春变形记》《夏日友晴天》官方海报级别

🎭 角色渲染
屏幕占比: 40%
面部:
  - 眼睛: 皮克斯大眼睛,多重高光,虹膜细节,IOR 1.376角膜
  - 皮肤: 三层SSS次表面散射(0.5mm/1.5mm/3.0mm),双层高光,菲涅尔效应,可见毛孔
  - 细节: 自然红晕,光泽嘴唇,湿润泪膜,3D睫毛投影

毛发:
  - 数量: 100000+发丝
  - 着色器: 各向异性着色器+Marschner模型
  - 特征: 主副双高光,成簇感,碎发,颜色渐变

服装:
  - 纹理: 微观级织物纹理
  - 材质: 基于物理的PBR材质
  - 细节: 物理模拟褶皱,张力点,缝合线细节

布光: 电影级三点布光+HDRI环境光
姿势: 自然引人入胜,匹配参考图并艺术化夸张

🎨 物品布局
总物品数: 30-36件
排列方式: 90度直角或放射状Knolling布局

分类:
  时尚穿搭(香槟金,🎨):
    - 服装拆解(衣袖/衣领/裁片/内衬)
    - 鞋履拆解(鞋底/鞋面/鞋带/鞋跟)
    - 配饰(腰带/包袋/帽子/围巾)

  美妆个护(玫瑰金,💄):
    - 彩妆(口红/眼影盘/粉饼/香水)
    - 护肤(精华液/面霜/美容仪)

  数码生活(钢蓝色,📱):
    - 电子设备(手机/耳机/手表/平板/相机)
    - 材质需有正确粗糙度和反射

  个人爱好(24K金,🌟):
    - 奢华配饰(珠宝/品牌包)
    - 兴趣爱好(画笔/书籍/乐器/运动装备/咖啡用具)

物品要求:
  - 渲染质量: 与角色同等级3D渲染
  - 编号: 01-36圆形编号徽章
  - 材质: PBR材质+逼真软阴影

💥 爆炸视图
连接线: 优雅虚线/实线连接悬浮部件
箭头: 装饰性箭头指向标签
标注:
  - 材质样本: 织物/皮革微距特写方块
  - 材质标签: 如'100%真丝'、'意大利小牛皮'
  - 测量标尺: cm/inch标记

📝 排版
主标题: ✨ 角色拆解艺术 · THE ART OF DECONSTRUCTION ✨ 位于顶部中央
副标题: 角色本质·艺术拆解 / Character Essence Unveiled
分类标题: 带图标的圆角矩形标签,如"🎨 时尚穿搭", "💄 美妆个护"等
物品标签: 思源黑体,圆形数字徽章+简短描述

🎯 设计元素
几何框: Art Deco六边形/圆形细线框(0.5-1pt)
测量标尺: 沿左右边缘
十字准星: 四角和关键焦点处
材质样本: 底部面料/皮革/金属微距特写方块
信息卡片: 优雅边框卡片展示详细信息
雷达图: 角色属性雷达图(优雅/风格/智慧等)
连接线: 金色/银色优雅虚线和箭头

🌅 背景
渐变: 白色→奶油色/香槟色暖色调 或 浅灰→白色冷色调
图案叠加: 5-10%透明度Art Deco几何网格或蓝图线条
暗角: 轻柔边缘暗角
氛围: 金色散景光斑+微妙胶片颗粒

🏷️ 品牌元素
水印: Yanhua Your Studio,位于画面中部,10-15%透明度,手写体
二维码: 右下角,"扫码查看3D模型 / SCAN FOR 3D GALLERY",Art Deco边框
物品计数: 右上角八角形框,"共XX件精选物品 / XX CURATED PIECES"
时间轴: 底部横跨,"☀️ 清晨6:00 → ✨ 创作进行时 → 🌙 午夜魅力12:00"

🎨 配色方案
女性时尚: 香槟金#D4AF37,玫瑰金#B76E79,奶油色#FFF8E7,樱花粉#F4C2C2
男性科技: 钢蓝色#4A90E2,炭灰色#4A4A4A,银色#C0C0C0,电光蓝#00D9FF
正式奢华: 纯黑#000000,24K金#FFD700,深红色#8B0000,象牙白#FFFFF0
情侣: 男性冷色调 vs 女性暖色调对比

🔧 技术规格
渲染:
  - 引擎: 路径追踪(Path Tracing) - Cycles/Arnold/RenderMan级别
  - 采样: 4096+ SPP
  - 光线反弹: 12
  - 焦散: 开启
  - 角色多边形: 2000000+
  - 发丝: 100000+

PBR材质:
  - 皮肤: 三层SSS,双层高光
  - 毛发: 各向异性着色器,主副双高光
  - 织物: 微观编织法线贴图
  - 金属: Metalness 1.0, Roughness 0.1-0.4
  - 玻璃: IOR 1.5,钻石IOR 2.42+色散
  - 皮革: Roughness 0.6-0.7,颗粒凹凸贴图

输出:
  - 分辨率: 4K (3840×2160)
  - 宽高比: 16:9
  - 位深: 32-bit浮点
  - 抗锯齿: 16x MSAA

✨ 后期处理
色彩分级:
  - LUT: 电影感LUT
  - 阴影: 提高暗部,最低RGB 15,15,15
  - 曲线: 温和S型曲线增强对比度
  - 色温: 暖色+200K / 冷色-200K
  - 饱和度: 整体-5%,重点色彩+10%

特效:
  - 辉光: 高光区域柔和光晕
  - 胶片颗粒: 柯达Portra 400胶片质感
  - 色散: 边缘极细微色散
  - 暗角: 中等强度暗角
  - 锐化: 输出时适度锐化

📋 特殊说明
单人: 30件物品,聚焦个人生活方式
情侣: 36件物品(每人18件),爱心符号连接,性别色调区分
孕妇: 含孕期用品(托腹油/维生素/B超照片),腹部附近婴儿图标
核心原则: 必须根据参考照片匹配角色年龄/职业/风格

✅ 质量检查清单
- 角色具备皮克斯品质的皮肤/毛发/眼睛,SSS和反射效果正确
- 所有30-36件物品清晰可见、已编号、渲染精细
- 分类色彩编码统一一致
- 品牌元素(水印/二维码/时间轴)已呈现
- 中英文排版优雅清晰易读
- 整体构图和谐,遵循视觉美学
- 4K分辨率,边缘无锯齿
- 后期处理效果(辉光/颗粒/暗角)已应用

🎯 使用场景
奢华产品目录
高端时尚杂志内页
专业艺术品印刷
个人摄影作品集
品牌营销活动
```

## 飞机拆解提示词模板

### 概念艺术风格 - 网格布局
```
Aircraft Deconstruction Concept Art Prompt

🎯 Core Instruction
Create a cinematic 3D concept art style deconstruction poster of [飞机型号]. Emphasize futuristic design aesthetics with appropriate artistic exaggeration for strong visual impact. Use grid layout Knolling for all aircraft parts.

Aspect Ratio: 16:9
Style: Concept Art - futuristic, technically precise, visually striking
Quality Benchmark: Aerospace concept art, movie production design level

✈️ Aircraft Breakdown
Total Parts: 30-36 pieces

Categories:
  Fuselage (航空蓝 Label):
    - Nose section, forward fuselage, mid fuselage, aft fuselage, tail cone
    - Cockpit windshield, canopy, ejection seat

  Wings (银灰色 Label):
    - Main wings, flaps, ailerons, slats, wingtips, wing tanks

  Tail (深灰色 Label):
    - Vertical stabilizer, horizontal stabilizers, rudder, elevators

  Propulsion (金属蓝 Label):
    - Turbofan engines, intake ducts, exhaust nozzles, thrust reversers

  Landing Gear (机械灰 Label):
    - Nose gear, main gear, wheels, shock struts, brakes

  Systems (科技蓝 Label):
    - Avionics, radar, sensors, fuel systems, hydraulic systems

🎨 Grid Layout
- 4 columns × 6 rows grid
- Uniform spacing between all parts
- Circular number badges (01-36)
- Center-aligned in each grid cell
- All parts at 90-degree angles (Knolling)

⚙️ Technical Specifications
- Rendering: Path Tracing, 2048+ SPP, 8 light bounces
- Materials: Anodized aluminum, titanium, composites, glass
- Resolution: 4K (3840×2160), 16:9

🎬 Post Processing
- Color Grading: Cinematic teal/orange look, high contrast
- Effects: Lens flares, atmospheric perspective, subtle film grain, moderate vignette

✅ Quality Checklist
- All aircraft parts clearly categorized and numbered
- Grid layout clean and professional
- Technical accuracy maintained with artistic exaggeration
- Futuristic concept art aesthetic achieved
- All annotations and labels present
- 4K resolution with no jagged edges
```
