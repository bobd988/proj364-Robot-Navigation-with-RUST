# Robot-Navigation-with-RUST
利用基于RUST的开源机器人中间件 Dora-rs 开发机器人导航代码，开阔视野和设计能力。标准化线上和线下平台使开发者聚焦算法的迭代。

## 项目描述

这个项目基于 开源Dora-rs 和配套的机器人硬件。 Dora-rs 是基于 RUST所打造的开源机器人应用框架，旨在简化基于 AI 的机器人应用程序创建流程。它具备出色的性能表现，提供低延迟、可组合以及分布式的数据流功能，能将应用程序建模为有向图（也就是管道）的形式，利用零拷贝 Apache Arrow 消息实现快速的数据传输，且支持 Python、C、C++ 以及 ROS2 等多语言，方便开发者参与开发，还拥有热重载等实用功能，为机器人开发领域带来了高效且极具创新性的新选择. Dora-rs 也是开源鸿蒙版发行版的一部分提供OHOS的机器人能力。

预赛使用低成本 1:10 小车， 配备 2D 激光雷达、IMU 与摄像头开展线下竞赛，并结合 Carla 仿真线上比赛，安排多轮初赛，兼顾实操与模拟优化。决赛采用车规级无人车3D激光雷达/IMU/RTK 进行线下比拼，考验选手高阶技术应用能力. 选手由浅入深参与比赛，学习内容多元。编程上支持 RUST、C、python 等，适配不同编程习惯，还能接触到常规教程少见的硬件在环知识，丰富知识技能储备. 比赛聚焦领域知识创新，避免选手耗费大量精力学习 ROS 框架，助力选手专注核心技术，提升在机器人领域的创新与竞争能力。

Carla 线上仿真和线下赛道包括城市沙盘，比赛任务要求自动驾驶小车遵循交通规则，如在路口等待信号灯、避让行人、在不同道路条件下（如主干道、小巷）行驶，还可能涉及完成指定地点的货物投递或模拟城市巡逻任务。目前参考实现已经提供的代码覆盖场景包括：  
- 行人横穿道路识别及响应
- 限速标志识别及响应
- 交通信号灯识别及响应
- 邻车道目标车切入
- 限车时间目标车切出
- 避障续行—施工路段标志
- 避障续行—行人
- 避障续行—链桶障碍物
- 直道跟驰
- 循迹算法—S弯

## 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

- 丁心民, 黄浴，岑汝平
- email bding@dora-rs.org

## 赛题分类
未归类的应用（如机器人、无人机等）

## 难度
中等

## 特征
- 理解 基于 Dora-rs 的 autoware 开源代码实现  
- 理解 dora-drive, 一个循序渐进的教程，让初学者能够使用一个简单的入门套件从头开始编写自己的自动驾驶汽车程序
- 基于参考场景代码，增加新的场景代码，或者优化已有的导航算法，通过仿真和线下车辆进行开发验证。
- 学习基于 Rerun 的机器人调试器
- 学习基于Carla 硬件在环调试
  
## 代码和文档
- https://dora-rs.ai/
- https://github.com/dora-rs/autoware.universe
- https://github.com/dora-rs/dora-drives

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

不要求一定完成。选择本项目的同学也可提出自己的新想法，得到导师任何支持后亦可加入预期目标或进阶特性。
