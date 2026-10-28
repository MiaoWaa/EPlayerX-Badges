# 全白文字与描边 · 10% 底色测试版

当前全部 21 个徽章使用 B 字体（SF Pro Text Bold 转路径）。

- 文字：#FFFFFF，不透明；每个文字 path 均明确设置 fill。
- 描边：#FFFFFF，1.4px，不透明。
- 底色：#46566E，10% 不透明度。
- 圆角 6px、高度 22px，保留各徽章宽度。
- JSON 匹配规则、分组、顺序不变，配置原生颜色保持透明，由 SVG 显示。

## 导入

https://raw.githubusercontent.com/MiaoWaa/EPlayerX-Badges/main/test-unified-51/badges-no-rating.json

本次配置改为引用全新路径 icons-white-10/，帮助避开旧图缓存。原来的 8% 图片仍保留于 icons/ 供对比。先停用其他徽章配置，仅启用此测试版，再刷新或重新导入。当前为固定白色文字与描边，不会自动切换主题。正式配置、深色彩色测试版与浅色彩色测试版均保持不变。
