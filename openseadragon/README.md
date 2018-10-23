###### 项目介绍：H5页面，实现长按按钮图片（清明上河图）自动播放 . . .
> [openseadragon](https://github.com/openseadragon/openseadragon "openseadragon") 基于Web的开源查看器，用于高分辨率可缩放图像，以纯JavaScript实现，适用于桌面和移动设备。

### 技术背景

图片大部分都是压缩过的，大部分为JPEG PNG BMP其中BMP格式是点阵形式，当图片翻译到内存之后无论压没压缩过都会变成BMP格式放进内存，在这个过程中，图片数据会几倍的增大，就比如JPEG，一张1M大小的JPEG格式的图片，翻译到内存可能就会变成7倍左右，也就是7M会放在电脑内存里面，如果显示一张100M的JPEG图片，放进内存的话可能就会成为1G，好了如果是1G的图片呢，你的电脑内存还够用吗，再如果在手机端显示呢？ **最后找到两个js库来实现项目需求 [Leaflet](https://github.com/Leaflet/Leaflet) 和 [openseadragon](https://github.com/openseadragon/openseadragon)**

> 实现代码详见 openseadragon_demo.html ，[教程详见](blog.emper.cn/20181018/openseadragon.html)