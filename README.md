# Robot-Navigation-with-RUST
移植 RUST 导航代码到Dora-rs 机器人开发套件
## 项目描述

这个项目基于 开源Dora-rs 和配套的机器人硬件。 Dora-rs 是基于 RUST所打造的开源机器人应用框架，旨在简化基于 AI 的机器人应用程序创建流程。它具备出色的性能表现，提供低延迟、可组合以及分布式的数据流功能，能将应用程序建模为有向图（也就是管道）的形式，利用零拷贝 Apache Arrow 消息实现快速的数据传输，且支持 Python、C、C++ 以及 ROS2 等多语言，方便开发者参与开发，还拥有热重载等实用功能，为机器人开发领域带来了高效且极具创新性的新选择. Dora-rs 也将在开源鸿蒙版本中提供机器人相关功能。

ArceOS 是由国家智能网联汽车创新中心和清华大学联合开发，采用 Rust 语言编写的RTOS系统，旨在为智能网联汽车等领域提供安全、高性能、可靠内核解决方案的实验性模块化操作系统，ArceOS已经支持 Dora-rs. 
我们的目标是移植 RustRobotics 代码移植到到 Dora-rs，运行在ArceOS RTOS上, 结合免费提供的 Dora-kit 四轮机器人， 借助已有的激光雷达， IMU 等传感器提高ArceOS RTOS 下机器人的室内导航能力。

RustRobotics是一个RUST 编写的机器人导航的框架。 我们的目标是移植 RustRobotics 代码移植到到 Dora-rs，运行在ArceOS RTOS上, 此项目将提供 Dora-kit 四轮机器人， 借助已有的激光雷达， IMU 等传感器提高ArceOS RTOS 下机器人的室内导航能力。

## 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求


## 项目导师

- 丁心民
- email bding@dora-rs.org

## 赛题分类
未归类的应用（如机器人、无人机等）

## 难度
中等

## 特征
- 理解ArceOS的代码实现和 Dora-rs 代码实现
- RustRobotics 部分代码移植到到 Dora-rs 框架
- 
## 文档
https://dora-rs.ai/
https://github.com/arceos-org/arceos

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

不要求一定完成。选择本项目的同学也可提出自己的新想法，得到导师任何支持后亦可加入预期目标或进阶特性。
