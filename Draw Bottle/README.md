# 绘制酒瓶模型

[TOC]

-----

## 导入图片素材

1. 调整到`side-x`视图下导入图片(始终保持绘制的曲线在平面内)

2. 视图 -> 图像平面 -> 导入图像

   ![image.png](https://upload-images.jianshu.io/upload_images/12014150-89d31a5bfddecdbc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 调整图片位置, 使得纵轴穿过要绘制的图片的中心

   ![image.png](https://upload-images.jianshu.io/upload_images/12014150-f4410366f3864a3a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

-----

## 沿瓶身边缘绘制CV曲线

1. 创建 -> 曲线工具 -> CV曲线

   ![image.png](https://upload-images.jianshu.io/upload_images/12014150-c5896f92bd0aede8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 沿瓶身一侧绘制CV曲线

3. 在弯曲处尽量用更多的点进行绘制, 可以使得曲线更光滑

### 瓶口处理

起始点要深入到瓶子内部, 只有这样在旋转之后才能更好的呈现瓶子口的形状, 有一种浸入感(不容易穿帮)

![image.png](https://upload-images.jianshu.io/upload_images/12014150-b07dee10b20d0020.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/12014150-47aa92403bcab863.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

-----

### 瓶底处理

结束点一定要靠在纵轴上, 如果提前结束曲线则会出现瓶子底部不封闭的效果[见下图] (也会穿帮)

![image.png](https://upload-images.jianshu.io/upload_images/12014150-ad5a51ed593690c3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/12014150-04f6e8c5c9237fc4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

-----

## 将曲线旋转成3D模型

1. 选择CV曲线 -> 曲面 -> 旋转

   ![image.png](https://upload-images.jianshu.io/upload_images/12014150-8dc62d1830ee9ec4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 曲面 -> 反转方向

   ![image.png](https://upload-images.jianshu.io/upload_images/12014150-97d9afb860e9fe3b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)