# 3DGS-Real-Scene-Recon

Real-world 3D Gaussian Splatting reconstruction demos

\# 3DGS Real Scene Reconstruction



> 基于手机视频与 RealSense D435i 的多源真实场景 3DGS 重建实践。

> 覆盖学院楼层、商场、车辆周围等多尺度场景，用于人形机器人仿真环境部署。

## 📹 Reconstruction Demos



\### Scene 1: Hall 1F (Large-scale Indoor)

| Preview | Method |

|---------|--------|

| !\[hall\_1f](previews/hall\_1f.gif) | Hierarchical3DGS |



\### Scene 2: Mall Scene (Complex Texture)

| Preview | Method |

|---------|--------|

| !\[mall](previews/mall.gif) | Hierarchical3DGS |



\### Scene 3: Vehicle Surround

| Preview | Method |

|---------|--------|

| !\[vehicle](previews/vehicle.gif) | Traditional 3DGS |



\## 🔧 Data Pipeline

\- \*\*采集\*\*: Phone video (4K) + RealSense D435i RGB-D stream

\- \*\*标定\*\*: Intrinsic calibration + World-to-pixel projection

\- \*\*对齐\*\*: RGB-D temporal-spatial alignment

\- \*\*重建\*\*: COLMAP init → 3DGS training / SLAM tracking



\## 📊 Tech Stack

RealSense D435i | OpenCV | COLMAP | PyTorch | Hierarchical3DGS | MemGS | LEGO-SLAM | ROS/ROS2 | Ubuntu

