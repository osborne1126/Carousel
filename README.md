## 轮播的实现原理:
- 通过控制轮播框体的left值（前提条件需要绝对定位）来动态滚动图片。
- 通过一个视窗容器来控制当前显示的画面。
- 无限轮播的侧重点在于通过在拷贝第一和最后一张的轮播元素，在滚动到最后一张或最前一张的拷贝元素时，再定位至原元素的left值，达到视觉上的无限轮播。
### 你来实现，会抽象出哪些函数(or接口):
- 3个函数，分别是playNext()(轮播下一张),playPrev()(轮播前一张),autoPlay()(自动轮播)

#### 左右滚动无限循环轮播: [预览](https://osborne1126.github.io/Carousel/carousel.html)

#### 渐变轮播: [预览]( https://osborne1126.github.io/Carousel/fade_carousel.html)

#### 无缝轮播: [预览]( https://osborne1126.github.io/Carousel/index.html)

