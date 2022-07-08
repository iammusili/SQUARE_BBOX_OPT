# SQUARE_BBOX_OPT
Bounding box initialization and optimization for ground target tracking

代码为《无人机对地目标跟踪的初始跟踪框选取和优化》一文的演示代码。
作者：李楚为，张志龙，钟平。
单位：国防科技大学。
说明：
代码中使用了来自以下两篇论文的代码，并对其进行了删减和编译，但结果与原文一致。
【1】Saliency Detection: A Boolean Map Approach. Jianming Zhang, Stan Sclaroff, ICCV, 2013.
【2】Global Contrast based Salient Region Detection. Ming-Ming Cheng, Niloy J. Mitra, Xiaolei Huang, Philip H. S. Torr, Shi-Min Hu. IEEE TPAMI, 2015.


配置要求：
windows 10系统；matlab2014b及以上版本。

有两种测试方式：
1、自动从标注文件读取框：
	直接运行“demo_automatic.m”即可。

2、手动绘制框：
	1) 运行“demo_manual.m”
	2) 拖动左上角正方形框，并调整大小，使其与感兴趣的目标尽可能接近
	3) 按“enter”键，等待运行。


