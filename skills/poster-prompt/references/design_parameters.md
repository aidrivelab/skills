# 设计参数

## 渲染规格

### 超写实渲染参数
```json
{
  "photorealistic_rendering": {
    "engine": "路径追踪(Path Tracing) - Cycles/Arnold/RenderMan级别",
    "sampling": "4096+ SPP",
    "light_bounces": 12,
    "caustics": "开启",
    "resolution": "4K (3840×2160)",
    "aspect_ratio": "16:9",
    "bit_depth": "32-bit浮点",
    "antialiasing": "16x MSAA"
  }
}
```

### 皮克斯风格渲染参数
```json
{
  "pixar_rendering": {
    "engine": "RenderMan RIS",
    "sampling": "2048+ SPP",
    "light_bounces": 8,
    "subsurface_scattering": "三层SSS",
    "resolution": "4K (3840×2160)",
    "aspect_ratio": "16:9"
  }
}
```

## PBR材质参数

### 皮肤材质
```json
{
  "skin": {
    "subsurface_scattering": "三层SSS(0.5mm/1.5mm/3.0mm)",
    "specular": "双层高光",
    "fresnel": "菲涅尔效应",
    "details": "可见毛孔,自然红晕,光泽嘴唇,湿润泪膜"
  }
}
```

### 毛发材质
```json
{
  "hair": {
    "count": "100000+发丝",
    "shader": "各向异性着色器+Marschner模型",
    "highlights": "主副双高光",
    "features": "成簇感,碎发,颜色渐变"
  }
}
```

### 织物材质
```json
{
  "fabric": {
    "texture": "微观级织物纹理",
    "normal_map": "微观编织法线贴图",
    "details": "物理模拟褶皱,张力点,缝合线细节"
  }
}
```

### 金属材质
```json
{
  "metal": {
    "metalness": 1.0,
    "roughness": "0.1-0.4",
    "reflection": "清晰反射"
  }
}
```

### 玻璃材质
```json
{
  "glass": {
    "ior": 1.5,
    "diamond_ior": 2.42,
    "dispersion": "色散"
  }
}
```

### 皮革材质
```json
{
  "leather": {
    "roughness": "0.6-0.7",
    "bump_map": "颗粒凹凸贴图"
  }
}
```

## 后期处理参数

### 色彩分级
```json
{
  "color_grading": {
    "lut": "电影感LUT",
    "shadows": "提高暗部,最低RGB 15,15,15",
    "curve": "温和S型曲线增强对比度",
    "temperature": "暖色+200K / 冷色-200K",
    "saturation": "整体-5%,重点色彩+10%"
  }
}
```

### 特效
```json
{
  "effects": {
    "bloom": "高光区域柔和光晕",
    "film_grain": "柯达Portra 400胶片质感",
    "chromatic_aberration": "边缘极细微色散",
    "vignette": "中等强度暗角",
    "sharpening": "输出时适度锐化"
  }
}
```

## 布光参数

### 三点布光
```json
{
  "three_point_lighting": {
    "key_light": "主光源,45度角",
    "fill_light": "辅助光,柔化阴影",
    "back_light": "轮廓光,分离主体与背景"
  }
}
```

### HDRI环境光
```json
{
  "hdri_lighting": {
    "environment": "HDRI环境贴图",
    "intensity": "适中",
    "rotation": "根据场景调整"
  }
}
```

## 版式尺寸参数

### 三段式布局尺寸
```json
{
  "three_section_dimensions": {
    "top": {
      "height": "33%",
      "title_position": "顶部中央",
      "title_font": "中文方正宋刻本秀楷/英文Playfair Display",
      "title_effect": "金箔效果,新艺术风格装饰框"
    },
    "middle": {
      "height": "50%",
      "content_alignment": "中心对齐",
      "item_spacing": "均匀分布"
    },
    "bottom": {
      "height": "17%",
      "signature_position": "底部中央或右下角",
      "watermark_opacity": "10-15%",
      "qr_position": "右下角"
    }
  }
}
```

## 标注和注释参数

### 部件编号
```json
{
  "item_numbering": {
    "style": "圆形数字徽章",
    "range": "01-36",
    "position": "部件附近",
    "font": "思源黑体"
  }
}
```

### 连接线
```json
{
  "connection_lines": {
    "style": "优雅虚线/实线",
    "color": "金色/银色",
    "arrows": "装饰性箭头指向标签"
  }
}
```

### 材质样本
```json
{
  "material_samples": {
    "style": "织物/皮革微距特写方块",
    "labels": "如'100%真丝'、'意大利小牛皮'",
    "position": "底部或侧边"
  }
}
```

### 测量标尺
```json
{
  "measurement_rulers": {
    "units": "cm/inch标记",
    "position": "沿左右边缘"
  }
}
```
