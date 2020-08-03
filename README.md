# MIT 6.837 Computer Graphics（2019 Fall)
这是2019年秋学期《MIT6.837——计算机图形学》课程的6个小作业。  
- 在各个作业中本人挑选了Extra Credit中的部分easy和少部分medium的知识点进行实现，并提供了对应的作业笔记，可作为参考。由于该项目是学习使用，故代码中存在了较多的注释，还请读者见谅，亦可作为参考。  
- 每个作业包括了对应的源代码，作业指导文件，作业笔记以及效果图。
- 由于文件实在是太大了，无法整个文件夹(工程文件）直接上传，所以只上传了必要的源代码，请在原框架上build好之后修改源文件进行测试。由于有部分新增代码，cmakeList也做了对应修改，build的时候记得进行替换。
- 饮水思源，本作业的相关资料都源自于仓库<https://github.com/longnguyen1997/comp_graphics>，读者可以先对其进行参考。
- 另外，assn4的框架代码没有上传，源仓库里面也没有，可行的一个办法是直接使用他提交的作业文件，并自行删去作业要求实现的部分，再自己完成。
## 项目结构
- **assn_fram**： 项目的框架，读者应该先在这个文件上面构建工程并完成作业。
- **assn0**： OpenGL网格查看器，主要实现简单的obj文件解析，以及基本的着色模型，插值计算等。
- **assn1**： 曲线和曲面，需要实现3阶贝塞尔和B样条曲线，以及曲面和通用圆柱体的绘制。  
(注意，作业1曲线的绘制存在问题，虽然在少数控制点的情况下表现正确，但是使用该方法生成的曲线去绘制曲面时产生了不正确的结果，这一点似乎源仓库里的曲线绘制方法也会如此。但由于各种原因该问题本人并没有解决，读者可以自行研究。)
- **assn2**： 动画和骨骼蒙皮，需要实现层级建模和SSD骨骼子空间变形算法。
- **assn3**： 物理模拟，需要实现质点-弹簧系统，以及基于质点-弹簧系统模拟的布料系统。
- **assn4**： 光线追踪，需要实现光线投射、光线追踪算法。
- **assn5**： 实时阴影，需要实现阴影贴图技术以实现实时阴影效果。

