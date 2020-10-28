### 前言
由于网上大部分自定义相机的实现，都是耦合性比较强的，不方便今后的复用，所以我自己实现了一套自定义相机，方便以后的扩展。自定义相机分为以下3个部分。
*  相机的预览布局SurfaceView ，方便用户实时预览。写成自定义控件，方便今后的复用。
*  相机的自动聚焦以及点触聚焦，拍照需要聚焦，要不然拍出的图片很可能是模糊的。写成自定义控件，方便今后的复用。
*  相机的自定义布局，这部分随着需求的迭代变换，前面的2大块不需要改动。
![Venn Diagram 11.png](https://user-gold-cdn.xitu.io/2019/3/13/1697534bb2087301?w=1123&h=794&f=png&s=59022)

### Demo 预览

![Screenshot_2019-03-13-10-57-23-754_com.focustech..png](https://user-gold-cdn.xitu.io/2019/3/13/1697507ed0a25dca?w=500&h=1000&f=png&s=819922)

### 欢迎加入我的QQ群

#### QQ号：264587303
