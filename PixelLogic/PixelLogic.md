# Pixel Art

## chapter1 Line Art 线条艺术

### Jaggle

![image-20220512123039348](PixelLogic.assets/image-20220512123039348.png)

### 线Line

#### No outline 无边框线

![image-20220512221018010](PixelLogic.assets/image-20220512221018010.png)

#### Black inline 内部也有边框线

![image-20220512221100388](PixelLogic.assets/image-20220512221100388.png)

#### Black contour 外轮廓线

![image-20220512221133390](PixelLogic.assets/image-20220512221133390.png)

#### Coloured 彩色边框线

![image-20220512221203811](PixelLogic.assets/image-20220512221203811.png)

#### Selective outline 随光源渲染的边框线

![image-20220512221509851](PixelLogic.assets/image-20220512221509851.png)

#### 总结

![image-20220512221548676](PixelLogic.assets/image-20220512221548676.png)

## chapter 2  Anti-Aliased 反锯齿

![image-20220512222339981](PixelLogic.assets/image-20220512222339981.png)

![image-20220512223623102](PixelLogic.assets/image-20220512223623102.png)

### 什么时候用反锯齿

反锯齿常常用于平滑那些不可避免的抖动

Clarity清晰化

Detail细节化

高对比High contrast

线条粗细权重 Line weight

![image-20220512223917104](PixelLogic.assets/image-20220512223917104.png)

### 如何加反锯齿

应该是线条长度的一半，少好过多。

谨慎地使用反锯齿，少用不同的阴影，以免混淆像素艺术的边界。

![image-20220512224056280](PixelLogic.assets/image-20220512224056280.png)

### 45°的反锯齿

不常见，但是在nes一些游戏中出现过

这样就有不同的凹凸曲线的区别

![image-20220515020414731](PixelLogic.assets/image-20220515020414731.png)

### 抖动也可以通过反锯齿来进行处理

![image-20220515020703560](PixelLogic.assets/image-20220515020703560.png)

### 线重

通过颜色深浅，表示线的薄厚。

![image-20220515020849562](PixelLogic.assets/image-20220515020849562.png)

### 没必要反复反锯齿

![image-20220515021652644](PixelLogic.assets/image-20220515021652644.png)

### 绑定是不好的

![image-20220515021812791](PixelLogic.assets/image-20220515021812791.png)

![image-20220515021853218](PixelLogic.assets/image-20220515021853218.png)

![image-20220515022118067](PixelLogic.assets/image-20220515022118067.png)

### 如何修正band？

1. 从角落移出或增加一两个像素
2. 使用反锯齿

![image-20220515021939207](PixelLogic.assets/image-20220515021939207.png)

## chapter3 colour 颜色

像素画也是电子艺术，所以他的颜色以sliders滑块来控制变量。

### 色彩定义

#### 1、The 3 Colour sliders

##### Hue 色度

##### Saturation 饱和度

##### Value 灰度值



![image-20220515022623590](PixelLogic.assets/image-20220515022623590.png)

#### 2 、RGB

### 使用调色板

### colour Ramps渐变色带

不建议在调色盘将渐变色搞混

![image-20220515023404645](PixelLogic.assets/image-20220515023404645.png)

### Hue shifting 色调偏移

#### 1、regular hue shift

![image-20220515151926461](PixelLogic.assets/image-20220515151926461.png)

黄色是色环中最亮的颜色，而紫色是最暗的，所以很多人都将色环从黄到紫

![image-20220515152046020](PixelLogic.assets/image-20220515152046020.png)

#### 2、Multiplay layers 合并颜色

![image-20220515152226672](PixelLogic.assets/image-20220515152226672.png)

### Saturation shifting 饱和度偏移

![image-20220515152848304](PixelLogic.assets/image-20220515152848304.png)

### Black tones

黑并不是单纯的黑，实际上可以在黑区加一个暗色，或是将黑区本身变成暗灰色

![image-20220515153241224](PixelLogic.assets/image-20220515153241224.png)

### 使用灰色

灰调可以“隐藏”他的存在，特别是在能用的颜色比较有限的情况下。



![image-20220515160433808](PixelLogic.assets/image-20220515160433808.png)

### 总结

![image-20220515161731174](PixelLogic.assets/image-20220515161731174.png)

## chapter4 Readability 可读性

![image-20220515164348897](PixelLogic.assets/image-20220515164348897.png)

### Readability means Clarity(清晰)

#### Size matters...

![image-20220515164637834](PixelLogic.assets/image-20220515164637834.png)

#### but pixels matter more!

![image-20220515164744619](PixelLogic.assets/image-20220515164744619.png)

改变极小部分的像素也会让整个图片改变。

less is more。

