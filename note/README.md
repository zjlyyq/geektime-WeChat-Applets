## icon

**自定义图标实现方式**

1. 使用图片
  - 大量HTTP请求
  - 不方便修改样式
  - 图片放大会变虚
2. 精灵图
3. CSS绘制
  - 工作量大
  - 绘制时，需要统一一个中心点，否则控制位置比较麻烦
  - 不方便控制大小、颜色
4. 矢量字体 👈 `最简单有效`
  - @font-face、 font-family
  - 点阵字体 vs 矢量字体(type 1、trueType、openType)
  - iconfont.cn
  - 小程序推荐 ttf、woff (woff2不兼容低版本iOS)
5. SVG文件
  - image2base64
6. canvas
  - canvas多用于制作动画
  - 用于自定义图标有些大材小用
  - [omijs - 将SVG绘制成图像的 Cax 引擎](https://github.com/Tencent/omi)
  - [dntzhang(张磊) - 微信开放社区](https://developers.weixin.qq.com/community/personal/oCJUsw6rFVEDMczhqQwmnqaWhcl4)

WXSS加载图片及字体允许外域

+ [weui](https://weui.io/)