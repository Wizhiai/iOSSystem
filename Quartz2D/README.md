## Quartz2D

> Quartz 的坐标系零点默认就是左下角

1. [iOS 2D绘图 (Quartz2D)之阴影和渐变(shadow，Gradient)](https://www.cnblogs.com/huanying2000/p/6230467.html)

	* 一个轴向渐变(也称为线性渐变)沿着两个端点连接的轴线渐变。所有位于垂直于轴线的的某条线上的点都具有相同的颜色值。

		![](https://images2015.cnblogs.com/blog/1072407/201612/1072407-20161229100808601-690057632.png)
		
	* 一个径向渐变也是沿着两个端点连接的轴线渐变，不过路径通常由两个圆来定义。

		![](https://images2015.cnblogs.com/blog/1072407/201612/1072407-20161229100914570-1608521298.png)
		
		如果一个圆是另一个的一部分或者完全在另一个的外面，则Quartz创建了圆锥和一个圆柱。径向渐变的一个通常用法就是创建一个`球体阴影`。
		
		![](https://images2015.cnblogs.com/blog/1072407/201612/1072407-20161229100936976-753162241.png)