# 全部按 5.1 样式 · 临时测试版

以浅色版 5.1 的 SVG 与配置为样板，全部 21 个徽章统一样式：

- 字体：SF Pro Text Bold，文字已转 SVG 路径。
- 文字与描边：固定 #FFFFFF 白色。
- 底色：#46566E 灰蓝，8% 不透明度；底色叠加页面背景产生变化，文字不自动切换颜色。
- 描边：1.4px，不透明；圆角 6px，高度 22px，保留各徽章原有宽度。
- JSON 的 tagColor、borderColor、textColor 与 tagStyle 均沿用 5.1 的设置。
- 原有匹配规则、分组与顺序不变，不含评级。

## 导入

https://raw.githubusercontent.com/MiaoWaa/EPlayerX-Badges/main/test-unified-51/badges-no-rating.json

停用其他徽章配置，只启用本版。此版为白色文字和描边的单色测试方案，固定文字颜色；正式版与此前各测试目录保持不变。


已按要求将全部 21 个徽章的文字及描边改为 #FFFFFF；底色仍为 #46566E，8% 不透明度。图片 URL 附带版本参数用于刷新缓存，配置导入地址不变。
