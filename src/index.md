---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 简历,赵飞宇
description: Cogito, ergo sum.
# 简历标题
resume_title: 赵飞宇的主页
# 应聘者姓名
name: 赵飞宇
avatar: /img/avatar.jpg
# 联系方式
contact:
  - icon: fas fa-globe-asia
    text: https://unimendacity.github.io
    url: https://unimendacity.github.io/
  # 邮箱
  - icon: fas fa-envelope
    text: sdtczfy@163.com
    url:
  # 电话号码
  - icon: fas fa-phone-alt
    text: (+86) 166 2091 2450
    url: tel:+8616620912450
  - icon: fab fa-github
    text: Gitbub主页
    url: https://github.com/Unimendacity
# PDF下载链接
# download:
#   title: 下载
#   icon: fas fa-download fa-fw
#   url: https://github.com/xaoxuu/resume-docs
---


## <i class="fas fa-user-graduate"></i> 教育

**山东大学** 2014 - 2018 | 本科
能源与动力工程专业

**熊本大学** 2016 - 2019 | 本科
机械系统工程专业（双学位项目）

**东京大学** 2016 - 2019 | 本科
智能机械情报学专业 JSK-Lab

## <i class="fas fa-user-tie"></i> 工作

#### 深圳鹏行智能研究有限公司
2021.11 - 2023.03 | 机械臂抓取操作工程师

• 负责物体3D位置检测与6D位姿估计相关算法的设计与开发
• 负责视觉抓取的深度学习模型在C++环境下的流程打通
• 负责视觉抓取的深度学习模型实机部署与效果优化

## <i class="fas fa-award"></i> 项目


### 闭环场景机械臂抓取感知算法开发

#### 2022.03 - 2023.03

产品形态为带有机械臂的四足机器人，目标为家庭场景下智能操作与抓取功能的实现

• 实现家庭场景常见用品的抓取功能闭环，达到86%的抓取成功率
• 完成PointNetGPD算法的C++工程代码的开发
• 完成PointNetGPD算法模型神经网络部署与效果优化
• 将抓取点估计算法运行速度从秒级优化到毫秒级
• 完成视觉抓取算法输入点云的直通滤波、平面分割和降采样等预处理

### 目标物体6D位姿估计算法开发

#### 2022.03 - 2023.07

• 完成目标物体6D位姿估计算法流程与方案设计
• 基于LineMod算法完成C++工程代码开发
• 使用YOLO算法提供目标物体的ROI以优化LineMod算法效果
• 使用grabcut算法实现前后景分割以优化LineMod算法效果
• 减少6D位姿估计算法误匹配现象，将检测成功率提升至65%

### 目标物体3D位置检测算法开发

#### 2021.11 - 2022.03

• 基于YOLOv3算法实现RGB图像中目标物体的目标检测
• 根据相机投影原理通过目标检测结果在深度图像对应的深度得到目标物体的３D位置信息
• 完成ROS环境下3D目标检测算法的开发、优化以及工程化适配
• 实现实时（15FPS）3D目标检测对机械臂视觉伺服功能的支撑

### 商店环境下双臂移动机器人关于环境中认知行为控制的研究

#### 2019.09 - 2021.09

此项目是与日本产总研合作的面向便利店的AI与机器人系统开发，项目中使用日本丰田HSR以及THK的家庭支援机器人

• 构建便利店环境下的商品的目标检测系统：搭建商店环境下商品的Mask R-CNN算法的数据集，将Mask
R-CNN算法对RGB图像的实例分割结果投影至点云，然后对相关点云进行主成分分析、聚类等处理，最终获
得各商品的目标检测结果与3D位置
• 针对不同label的商品设计相应的符合形封闭原则的抓取方式，并对不同的原子动作设计相应的双臂协同方式
• 使用Euslisp语言实现原子动作集和SMACH任务状态机，使双臂机器人SEED-Noid能够自主完成商品的摆放、
整理、打包以及使用胶带封装纸箱等任务

### 双臂机器人在便利店环境对错误放置的商品进行识别与整理相关研究

#### 2019.09 - 2020.09

• 设计并实现双臂机器人SEED-Noid在商店环境下自主识别错误放置的商品并将其摆放至合适位置的相关算法
• 通过对比目标检测系统输出的包围相邻同类商品的Cluster Box实现错误摆放商品的检测
• 使用Euslisp语言实现SMACH任务状态机以完成多种类商品混杂状态下的任务规划与跳转条件设计

## <i class="fas fa-wrench"></i> 技能


- 编程语言: 熟悉C++, Python, Euslisp
- 技能: ROS, Pytorch, TensorRT
- 其他: Docker, Git, Linux
- 语言: 英语（商务级别），日语（商务级别）
