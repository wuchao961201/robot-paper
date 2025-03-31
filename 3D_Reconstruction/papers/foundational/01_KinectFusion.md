# KinectFusion: Real-time 3D Reconstruction and Interaction Using a Moving Depth Camera

## 论文信息
- **标题**: KinectFusion: Real-time 3D Reconstruction and Interaction Using a Moving Depth Camera
- **作者**: Richard A. Newcombe, Shahram Izadi, Otmar Hilliges, David Molyneaux, David Kim, Andrew J. Davison, Pushmeet Kohli, Jamie Shotton, Steve Hodges, Andrew Fitzgibbon
- **发表年份**: 2011
- **发表会议**: ACM Symposium on User Interface Software and Technology (UIST)
- **链接**: https://www.microsoft.com/en-us/research/publication/kinectfusion-real-time-3d-reconstruction-and-interaction-using-a-moving-depth-camera/

## 摘要
KinectFusion系统实现了利用消费级深度相机（Microsoft Kinect）进行实时3D重建和交互的技术。该系统能够通过移动的深度相机跟踪相机位姿，同时构建高质量的三维表面模型。系统无需使用其他传感器，完全依靠深度数据进行定位和建图，同时利用GPU加速实现了实时性能。通过截断有符号距离函数(TSDF)表示法，KinectFusion能够整合来自不同视角的深度数据，逐步改进重建质量。该系统也支持实时手势交互和物理模拟，为各种应用场景提供了基础。

## 核心贡献
1. 首次实现基于普通深度相机的实时密集重建系统
2. 提出了一种高效的相机跟踪和重建融合算法
3. 利用GPU实现了计算加速，使系统在普通PC上可实时运行
4. 演示了多种基于重建模型的交互方式

## 关联机器人应用
这项工作为机器人3D环境感知提供了革命性方法，尤其适用于：
- 室内移动机器人的环境映射与导航
- 机械臂的物体识别与抓取
- 人机协作场景的交互界面

## 影响
KinectFusion是基于深度相机的实时3D重建领域的开创性工作，奠定了之后众多系统的基础，如ElasticFusion、BundleFusion等。同时，它也极大推动了RGBD相机在机器人领域的应用，成为3D重建与SLAM研究的重要里程碑。 