# opencv_face_COWA
Python基于opencv人脸识别的考勤系统——by：liweijie
使用说明：
1.打开摄像头
2.进行人脸录入（第一次必须输入id和选取一张识别照片）
3进行建模学习
4.进行考勤
5.进行之后的录入后不用再选取当前人员的识别照片
技术背景：
  人脸识别是一种基于人的相貌特征信息进行身份认证的生物特征识别技术，技术的最大特征是
能避免个人信息泄露，并采用非接触的方式进行识别。人脸识别与指纹识别、掌纹识别、视网膜
识别、骨骼识别、心跳识别等都属于人体生物特征识别技术，都是随着光电技术、微计算机技术
、图像处理技术与模式识别等技术的快速发展应运而生的。可以快捷、精准、卫生地进行身份
认定；具有不可复制性，即使做了整容手术，该技术也能从几百项脸部特征中找出“原来的你”
。人脸识别系统在世界上的应用已经相当广泛。在中国就已广泛的应用于公安、安全、海关、
金融、军队、机场、边防口岸、安防等多个重要行业及领域，以及智能门禁、门锁、考勤、手机、
数码相机、智能玩具等民用市场
  人脸识别主要的特点是利用人的脸部特征作为一种身份辨识的方式，通过采集含有人脸的图像或
视频流，自动对图像或视频中的人脸进行检测定位、图像预处理、特征提取和匹配识别过程，达
到识别不同人身份的目的。因此，利用人脸识别技术的这个特点可以在不同场合中实现各种各样
的智能化应用。

opencv介绍：
OpenCV是一个基于Apache2.0许可（开源）发行的跨平台计算机视觉和机器学习软件库，可以
运行在Linux、Windows、Android和Mac OS操作系统上。 [1]  它轻量级而且高效——由一系
列 C 函数和少量 C++ 类构成，同时提供了Python、Ruby、MATLAB等语言的接口，实现了图
像处理和计算机视觉方面的很多通用算法。
OpenCV用C++语言编写，它具有C ++，Python，Java和MATLAB接口，并支持Windows，Li
nux，Android和Mac OS，OpenCV主要倾向于实时视觉应用，并在可用时利用MMX和SSE指
令， 如今也提供对于C#、Ch、Ruby，GO的支持。
OpenCV致力于真实世界的实时应用，通过优化的C代码的编写对其执行速度带来了可观的提升，
并且可以通过购买Intel的IPP高性能多媒体函数库（Integrated Performance Primitives）得到
更快的处理速度。
=================================================================


