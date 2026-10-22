# 机内 · 拆开看一台电脑

[打开交互展厅](https://232yhzhang.github.io/jinnei-laptop-exhibit/)

滚动拆解笔记本，拖拽旋转，点击查看 CPU、GPU、内存、SSD 等零件。协作演示会依次聚焦相关硬件，并显示表面流动高光。

## 运行与发布

这是单文件静态网页，模型、摄影棚 HDRI 与字体已嵌入 `index.html`。通过 HTTP 静态服务器预览；Three.js 0.170.0 和 GSAP 3.12.5 从 jsDelivr 加载，需要网络连接。浏览器需支持 WebGL 2。

GitHub Pages 从 `main` 分支根目录发布，`.nojekyll` 用于直接托管静态文件。更新 `index.html` 后推送即可重新部署。

## 来源与许可

- 外观模型：© 2024 Framework Computer Inc，[官方 CAD](https://github.com/FrameworkComputer/Framework-Laptop-16)，[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。已转换、打开屏幕并重制材质。
- 摄影棚光照：[studio_small_09，Sergej Majboroda / Poly Haven](https://polyhaven.com/a/studio_small_09)，CC0。
- 嵌入字体：Noto Serif SC 子集，SIL Open Font License；许可文本保留于 HTML 中。
- 内部采用可更换内存与 SSD 的高性能 Windows 笔记本通用结构。CPU/GPU 分离仅便于观察，不代表该外观型号的真实内部。