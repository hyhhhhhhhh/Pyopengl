<!--
 * @Description: 
 * @Author: He Yuhang
 * @Github: https://github.com/hyhhhhhhhh
 * @Date: 2021-01-10 14:08:55
 * @LastEditors: Box
 * @LastEditTime: 2021-01-10 14:11:49
-->
# Pyopengl 
 Experiment
# Exp2
1. 写一个OpenGL （如果熟悉WebGL也可以用）程序完成如下任务：
    读入桌子和椅子模型；
    建立一个有5个面的适当大小（比如桌子的3~4倍大小）的长方体房间（用4个墙面和1个地面表示）;
    用旋转和平移变换将桌子移到房间的中央，并使桌面的四条边与房间的墙面对齐；
    利用旋转和平移变换, 将椅子均匀地围绕圆桌一圈摆放;
    设置视点，并利用适当的光照和材质渲染所生成的场景。
2.  了解中华人民共和国国旗的规格尺寸、五角星大小与方位，以及标准颜色取值。完成下面任务
    (1)	建立红旗的多边形表示和五角星多边形表示；
    (2)	利用平移旋转缩放等几何变换将五角星变换到相应位置；
    (3)	利用glOrtho2进行平行投影，根据颜色对图案进行渲染得到一面标准的国旗图案。

# Exp3

给定物体1个植物的动态序列和1个马的动态序列(见附件)，请利用局部光照模型将其渲染。要求：
(1)	给植物动态序列的场景增加一个三次B样条曲面作为地面模型，并贴上沙漠纹理；
 
(2)	给马的态序列场景增加一个平坦(长方形)地面模型，并贴上草原纹理；
  
(3)	在适当位置设置两个光源（自己设置RGB的光强值）；
(4)	启用消隐功能；
(5)	按动画方式输出：即采用OpenGL的double buffer功能防止闪烁（查阅相关OpenGL函数），交替在两个buffers中渲染当前帧；并重复播放该序列次。
(6)	自己选择材质(即各种反射率)，比较flat shading和Gouraud shading的耗时情况。
(7)	能交互地对植物和马进行平移、旋转和缩放(不缩放地面),并能重新渲染几何变换之后的序列。

