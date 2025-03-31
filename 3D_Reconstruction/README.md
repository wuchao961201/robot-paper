# 3D重建技术论文集

本文件夹包含与3D重建技术（机器人应用）相关的资料和论文。

## 文件夹结构

- `技术综述.md` - 全面的3D重建技术综述，涵盖基本原理、发展历程、应用领域等
- `paper/` - 包含重要论文的摘要信息和PDF文件
  - `pdf/` - 包含已下载的论文PDF文件

## 已下载论文

以下论文已成功下载并存储在 `paper/pdf/` 目录中：

### 经典3D重建方法
1. **KinectFusion**: "KinectFusion: Real-time 3D Reconstruction and Interaction Using a Moving Depth Camera" (2011)
   - 文件: `01_KinectFusion.pdf`

2. **ORB-SLAM**: "ORB-SLAM: A Versatile and Accurate Monocular SLAM System" (2015)
   - 文件: `02_ORB_SLAM.pdf`

3. **NeRF**: "NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis" (2020)
   - 文件: `03_NeRF.pdf`

4. **ElasticFusion**: "Real-Time Dense Visual SLAM with Scale Awareness for Robotic Navigation" (2015)
   - 文件: `04_ElasticFusion.pdf`

5. **DeepLabV3**: "Rethinking Atrous Convolution for Semantic Image Segmentation" (2017)
   - 文件: `05_DeepLabV3.pdf`

6. **NeuralRecon**: "NeuralRecon: Real-time Coherent 3D Reconstruction Using Neural Implicit Representation" (2021)
   - 文件: `06_NeuralRecon.pdf`

### 最新3D高斯散射点 (3D Gaussian Splatting) 技术
7. **3D Gaussian Splatting**: "3D Gaussian Splatting for Real-Time Radiance Field Rendering" (2023)
   - 文件: `07_3D_Gaussian_Splatting.pdf`

8. **COLMAP-Free 3D Gaussian Splatting**: "COLMAP-Free 3D Gaussian Splatting" (2023)
   - 文件: `07_COLMAP_Free_3D_Gaussian_Splatting.pdf`

9. **Splat-Nav**: "Splat-Nav: Safe Real-Time Robot Navigation in Gaussian Splatting Maps" (2024)
   - 文件: `08_Splat_Nav.pdf`

10. **ActiveGS**: "ActiveGS: Active Scene Reconstruction using Gaussian Splatting" (2024)
    - 文件: `09_ActiveGS.pdf`

## 研究方向

这些论文涵盖了3D重建技术在机器人应用中的多个重要方向：

1. 基于深度相机的实时重建 (KinectFusion)
2. 基于特征的单目SLAM系统 (ORB-SLAM)
3. 神经隐式场景表示 (NeRF)
4. 稠密视觉SLAM (ElasticFusion)
5. 语义分割与3D重建结合 (DeepLabV3)
6. 神经网络端到端3D重建 (NeuralRecon)
7. 基于3D高斯散射点的场景表示与渲染 (3D Gaussian Splatting)
8. 无需COLMAP的高斯场景重建 (COLMAP-Free 3D Gaussian Splatting)
9. 基于高斯散射点的机器人导航 (Splat-Nav)
10. 主动场景重建与高斯散射点 (ActiveGS)

## 最新技术趋势

### 3D高斯散射点技术 (2023-2024)

3D高斯散射点 (3D Gaussian Splatting, 3DGS) 技术是最近兴起的一种场景表示和渲染方法，使用显式的3D高斯基元表示场景。与之前流行的神经辐射场 (NeRF) 相比，3DGS具有以下优势：

- **实时渲染**：渲染速度提升100倍以上，达到实时级别（数十到数百FPS）
- **高质量重建**：保持甚至提升了渲染质量
- **快速训练**：从小时级缩短到分钟级
- **显式表示**：便于编辑和操作

这些特性使3DGS特别适合机器人应用场景，如导航、主动场景重建和多机器人协作等。目前的研究正在探索将3DGS与语义理解、动态场景处理、多传感器融合等技术结合，进一步提升其在机器人领域的应用潜力。 