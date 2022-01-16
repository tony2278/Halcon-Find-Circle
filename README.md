# Halcon-Find-


1 halcon测量硬币真实直径 
   https://www.pianshen.com/article/4758271276/     (网上的例子)

具体步骤
1.halcon进行相机标定
2.对硬币图像进行处理
3. 处理后的图像拟合圆得到像素直径
4.通过相机外参得到硬币真实直径






 *图像点转换成世界坐标点
image_points_to_world_plane ()
 *标定后的图像一个像素代表的实际距离
PixelDist := 0.000508




2 卡尺找圆 (找线)
    Halcon卡尺找圆.hdev
    Halcon卡尺找圆-2500W.hdev   

    计算

    distance_pp  计算两个点的距离
    distance_pl   计算一个点到线的距离


3 halcon例程解析一add_metrology_object_generic的应用-手动画矩形，画圆，画线，画圆弧测量

https://blog.csdn.net/the_future_way/article/details/108634890


    Halcon简单卡尺测量实例
    https://www.sohu.com/a/477753850_121174094


Please don't use this for any production purposes.

Created by Tony2278

