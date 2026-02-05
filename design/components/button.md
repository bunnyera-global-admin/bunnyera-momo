
# Button Component — MOMO Design Specification

## 1. Purpose
用于 BunnyEra 全产品线的主要交互按钮，体现 MOMO 的柔和、轻盈、亲和的品牌特性。

## 2. Visual Style
- 圆角：12–16px（柔和）
- 颜色：使用品牌主色（见 colors.json）
- 阴影：轻柔、低对比度
- 边框：可选，透明或浅色
- 字体：使用 BunnyEra Typography 规则

## 3. States
- Default
- Hover（轻微放大 1.02x）
- Active（轻微压下）
- Disabled（降低对比度）
- Loading（MOMO 风格的柔和 loading 动效）

## 4. Motion
- 动画曲线：MOMO Motion Curve（见 momo-motion.md）
- 动画时长：120–180ms
- 交互动效需体现“轻、柔、快”

## 5. Variants
- Primary
- Secondary
- Ghost
- Danger（尽量少用）

## 6. Usage Guidelines
- 用于主要操作
- 不可过度使用
- 避免在同一页面出现多个 Primary

## 7. Brand Restrictions
- 不允许尖锐边角
- 不允许高对比度强烈阴影
- 不允许机械感强的动效
