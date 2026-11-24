# pb_omni_pid_pursuit_controller｜个人适配记录

本仓库是对上游全向机器人 PID Pure Pursuit 控制器的个人 Fork，用于维护 ROS 2 Jazzy 导航仿真适配过程中涉及的控制器修改。

## 仓库用途

该控制器面向全向移动机器人，结合路径前视点（Lookahead Point）与 PID 控制，实现路径跟踪；同时提供速度、转向及曲率相关参数。

## 当前状态

- 目标环境：Ubuntu 24.04、ROS 2 Jazzy
- 用途：个人哨兵机器人导航仿真适配
- 状态：适配与验证中，不代表所有功能已完成或经过实车验证

## 上游项目

- 上游仓库：[SMBU-PolarBear-Robotics-Team/pb_omni_pid_pursuit_controller](https://github.com/SMBU-PolarBear-Robotics-Team/pb_omni_pid_pursuit_controller)
- [查看上游原始 README](https://github.com/SMBU-PolarBear-Robotics-Team/pb_omni_pid_pursuit_controller/blob/main/README.md)

本仓库是个人维护的 Fork，不代表上游团队的官方项目。原始代码及其许可证、版权声明仍以各自文件中的说明为准。
