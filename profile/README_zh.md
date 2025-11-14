[English](./README.md) | **中文**

# 欢迎关注本末机器人
![direct-drive-logo](https://directdrive.com/public/uploads/images/20220221/4830a265658b4afeeccf7deda5bc044d.png)



本末科技成立于 2020 年，致力于使用直接驱动电机替代各类机械中的减速机构，让原本结构复杂、噪声较大的传统机器人焕发新生。

本末机器人成立于 2022 年，主要聚焦移动机器人，采用模块化设计方法进行机器人研发，例如[双轮足](https://www.bilibili.com/video/BV1tM4y1Z7VY?spm_id_from=player_end_recommend_autoplay&vd_source=8ab3473c3214c5120c93d5ac5fbba539)和[四轮足](https://www.bilibili.com/video/BV1Pn4y1R7eg/?spm_id_from=333.337.search-card.all.click)机器人。

[![Website](https://img.shields.io/badge/Official Website-0052CC?style=flat&logo=google-chrome)](https://directdrive.com/) [![Shop](https://img.shields.io/badge/%20Shop-8A2BE2?style=flat&logo=shopee)](https://shop.directdrive.com/) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://space.bilibili.com/2110984062) [![Bilibili](https://img.shields.io/badge/Bilibili-DDT-00A1D6?-style=flat&logo=bilibili&logoColor=white&labelColor=FB7299)](https://space.bilibili.com/2110984062?spm_id_from=333.337.0.0) [![Bilibili](https://img.shields.io/badge/Bilibili-DDT Robotics Team-00A1D6?-style=flat&logo=bilibili&logoColor=white&labelColor=FB7299)](https://space.bilibili.com/3546755798928026?spm_id_from=333.337.0.0)

### 开发手册

#### D-Infinite

[D-Infinite手册 - 中文版](https://d1-development-manual-cn.readthedocs.io/en/latest/index.html)

#### TITA

[TITA 手册 - 中文版](https://tita-development-manual-uc.readthedocs.io/zh-cn/latest/ )
[TITA 手册 - 英文版](https://tita-ubuntu-manual-english.readthedocs.io/en/latest/)
[TITA 扩展板开源硬件](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620)

> *注：自 2024 年 9 月起，TITA所有系统均已切换至 Ubuntu。若想使用 Yocto 版本，请参考[此处](https://tita-development-manual-ye.readthedocs.io/en/latest/ )。*

### 更新信息

| 日期       | 更新摘要                                                     |
| ---------- | ------------------------------------------------------------ |
| 2024-11-04 | 在 TITA 的 Orin NX 上新增用于关节控制的 ros2_control 接口    |
| 2024-12-02 | 新增 DIABLO ROS2 MATLAB 控制示例                             |
| 2024-12-04 | 新增 TITA ROS2 MATLAB 控制示例                               |
| 2025-02-10 | [新增 Airbot 机械臂控制示例](https://github.com/DDTRobot/airbot_on_tita) |
| 2025-02-26 | [新增扩展板硬件开源](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620) |
| 2025-03-09 | [新增官方 TITA 强化学习示例（基于 Isaac Gym 与 Webots 2023b）](https://github.com/DDTRobot/tita_rl) |
| 2025-03-14 | [新增官方 TITA CANFD 读取示例](https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main) |
| 2025-03-28 | [新增 webots2023b + ros2_control 的 Docker 环境](https://github.com/DDTRobot/webots2023b_ros2_docker) |
| 2025-04-07 | 修复 [tita_rl_sim2sim2real](https://github.com/DDTRobot/tita_rl_sim2sim2real) 与 [webots_ros2_docker](https://github.com/DDTRobot/webots2023b_ros2_docker) 的 Docker 支持问题 |
| 2025-04-14 | 更新 [diablo 仿真环境](https://github.com/DDTRobot/diablo-sim-env) 中的 Docker 链接 |
| 2025-11-04 | 更新 [TITATIT 四足轮机器人](https://github.com/DDTRobot/quadruped-wheel-titatit-rl) 的强化学习训练 |

### 🍿 官方维护的代码仓库

<table>
  <tr>
    <th>机器人</th>
  	<th>类型</th>
    <th>项目名称</th>
  	<th>描述</th>
    <th>Stars</th>
  </tr>
  <tr>
    <td rowspan='13'>TITA</td>
  	<td rowspan='4'>Simulation</td>
    <td><a href="https://github.com/DDTRobot/tita-sim-env">TITA 基础仿真环境</a></td>
  	<td>基于 Webots 的 TITA 基础仿真环境，提供 Windows 和 Linux 可执行示例</td>
  	<td><a href="https://github.com/DDTRobot/tita-sim-env"><img src="https://img.shields.io/github/stars/ddtrobot/tita-sim-env.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/TITA_ROS2_Control_Sim">TITA ROS2 Control 仿真</a></td>
    <td>TITA 的 ROS2 Control 仿真环境，支持 Webots 和 Gazebo。</td>
  	<td><a href="https://github.com/DDTRobot/TITA_ROS2_Control_Sim"><img src="https://img.shields.io/github/stars/ddtrobot/tita_ros2_control_sim.svg?cacheSeconds=7200" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA_Description">TITA URDF 描述（ROS2 Control 仿真）</a></td>
  	<td>TITA 的 URDF 描述文件，主要用于 ROS2 control 仿真。</td>
    <td><a href="https://github.com/DDTRobot/TITA_Description"><img src="https://img.shields.io/github/stars/ddtrobot/tita_description.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/tita_rl">TITA RL</a></td>
    <td>官方维护的 TITA 强化学习环境，同时支持 TITATIT 四足模式的环境</td>
    <td><a href="https://github.com/DDTRobot/tita_rl"><img src="https://img.shields.io/github/stars/ddtrobot/tita_rl.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>注：TITA 可通过 ROS2 control 接口或 USB2CAN 直接控制电机扭矩。如果需要帮助，请提 Issue 或联系我们的 FAE。</h5></small></blockquote></td>
  </tr>
  <tr>
  	<td rowspan='7'>Tools</td>
    <td><a href="https://github.com/DDTRobot/TITA-SDK-ROS2">TITA ROS2 SDK 示例</a></td>
  	<td>运行在真实 TITA 机器人上的 ROS2 SDK 快速上手示例，仅支持 Ubuntu。</td>
    <td><a href="https://github.com/DDTRobot/TITA-SDK-ROS2"><img src="https://img.shields.io/github/stars/DDTRobot/TITA-SDK-ROS2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita_hardware_ros2_control">TITA ROS2 Control 底层硬件接口</a></td>
    <td>TITA 的 ROS2 Control 底层接口，部署在 TITA 内部的 Orin NX 上。</td>
    <td><a href="https://github.com/DDTRobot/tita_hardware_ros2_control"><img src="https://img.shields.io/github/stars/ddtrobot/tita_hardware_ros2_control.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA-RC-Pairing">TITA 遥控器配对脚本</a></td>
    <td>用于更新 TITA 遥控器配对信息的脚本，安装在 TITA 主板上。</td>
    <td><a href="https://github.com/DDTRobot/TITA-RC-Pairing"><img src="https://img.shields.io/github/stars/DDTRobot/TITA-RC-Pairing.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA-OTA">TITA OTA 脚本</a></td>
    <td>用于更新 TITA MCU 板的固件，安装在 TITA 主板上。</td>
    <td><a href="https://github.com/DDTRobot/TITA-OTA"><img src="https://img.shields.io/github/stars/DDTRobot/tita-ota.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/airbot_on_tita">Airbot 机械臂在 TITA 上的控制</a></td>
    <td>在 TITA 上控制 Airbot 机械臂的 ROS 节点。</td>
    <td><a href="https://github.com/DDTRobot/airbot_on_tita"><img src="https://img.shields.io/github/stars/DDTRobot/airbot_on_tita.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/airbot_joy">使用手柄控制 TITA 上的机械臂</a></td>
    <td>在 TITA 上使用遥控手柄控制 Airbot 机械臂的 ROS 节点。</td>
<td>
  <a href="https://github.com/DDTRobot/airbot_joy"><img src="https://img.shields.io/github/stars/ddtrobot/airbot_joy.svg?cacheSeconds=3600" alt="GitHub stars"></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main">TITA CANFD 接口</a></td>
    <td>直接读取 TITA 的 CANFD 信息，可选择在 PC 或 TITA 内部的 Orin Nx 上运行。</td>
    <td><a href="https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main"><img src="https://img.shields.io/github/stars/ddtrobot/tita_can_inerface.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>注：TITA 可通过 ROS2 control 接口或 USB2CAN 直接控制电机扭矩。如果需要帮助，请提 Issue 或联系我们的 FAE。</h5></small></blockquote></td>
  </tr>
  <tr>   
	<td rowspan='4'>DIABLO</td>
    <td rowspan='1'>Simulation</td>
	<td><a href="https://github.com/DDTRobot/diablo-sim-env">DIABLO 基础仿真环境</a></td>
    <td>基于 Webots 的 DIABLO 仿真环境，包含如何通过 Docker 或系统安装 Webots 的示例</td>
    <td><a href="https://github.com/DDTRobot/diablo-sim-env"><img src="https://img.shields.io/github/stars/ddtrobot/diablo-sim-env.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
  	<td rowspan='2'>Tools</td>
	<td><a href="https://github.com/DDTRobot/diablo_ros2">DIABLO ROS2 SDK</a></td>
    <td>运行在真实 DIABLO 机器人上的 ROS2 SDK</td>
    <td><a href="https://github.com/DDTRobot/diablo_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_ros2?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>  
  <tr>   
	<td><a href="https://github.com/DDTRobot/diablo_sdk">DIABLO ROS1 SDK</a></td>
    <td>运行在真实 DIABLO 机器人上的 ROS1 SDK</td>
    <td><a href="https://github.com/DDTRobot/diablo_sdk"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_sdk?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>注：如果你想通过关节接口控制 DIABLO，请联系我们的 FAE。</h5></small></blockquote></td>
  </tr>
  <tr>   
	<td rowspan='2'>MOTOR</td>
  	<td rowspan='2'>Tools</td>
	<td><a href="https://github.com/DDTRobot/p10-ros2-node">在 TITA 上控制 P10 电机</a></td>
    <td>用于控制单个 P10 电机的 ROS2 节点，P10 是 Direct Drive Technology 自研的 QDD 电机</td>
    <td><a href="https://github.com/DDTRobot/p10-ros2-node"><img src="https://img.shields.io/github/stars/ddtrobot/p10-ros2-node.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
	<td><a href="https://github.com/DDTRobot/motor-driver-examples">Direct Drive 电机驱动示例</a></td>
    <td>M0602C 和 M1502D 的驱动示例</td>
    <td><a href="https://github.com/DDTRobot/motor-driver-examples"><img src="https://img.shields.io/github/stars/ddtrobot/motor-driver-examples.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
</table>


### 🧙 推荐的开发者仓库

<table>
  <tr>
    <th>机器人</th>
    <th>项目名称</th>
  	<th>描述</th>
    <th>Stars</th>
  <tr>
    <td rowspan='4'>TITA</td>
    <td><a href="https://github.com/DDTRobot/tita_matlab_ros2">TITA ROS2 MATLAB 示例</a></td>
  	<td>TITA 的 MATLAB 控制示例，使用 TITA 的上层API进行控制，基于 ROS2</td>
  	<td><a href="https://github.com/DDTRobot/tita_matlab_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/tita_matlab_ros2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/TITA_ISAACGYM_DRL">TITA 行走强化学习</a></td>
  	<td>基于 Isaacgym 的 TITA 行走强化学习示例，<a href="https://www.bilibili.com/video/BV1FfBAYyEnx/?spm_id_from=333.337.search-card.all.click&vd_source=8ab3473c3214c5120c93d5ac5fbba539">点击查看视频</a></td>
  	<td><a href="https://github.com/DDTRobot/TITA_ISAACGYM_DRL"><img src="https://img.shields.io/github/stars/ddtrobot/TITA_ISAACGYM_DRL.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita-app">TITA App</a></td>
  	<td>用于在 Android 手机上控制 TITA 的 APK 应用</td>
  	<td><a href="https://github.com/DDTRobot/tita-app"><img src="https://img.shields.io/github/stars/ddtrobot/tita-app.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita_uwb_follower">TITA UWB 跟随</a></td>
  	<td>基于 UWB 的 TITA 跟随功能示例，让机器人可以跟随 UWB 标签运动</td>
  	<td><a href="https://github.com/DDTRobot/tita_uwb_follower"><img src="https://img.shields.io/github/stars/ddtrobot/tita_uwb_follower.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td rowspan='4'>DIABLO</td>
    <td><a href="https://github.com/DDTRobot/autonomy_stack_diablo_setup">基于 DIABLO 的 CMU 导航方案</a></td>
  	<td>由 CMU 张继 开发的 DIABLO 导航示例：<a href="https://www.bilibili.com/video/BV1Ws421T7TJ/?spm_id_from=333.1387.homepage.video_card.click">点击查看视频</a></td>
  	<td><a href="https://github.com/DDTRobot/autonomy_stack_diablo_setup"><img src="https://img.shields.io/github/stars/ddtrobot/autonomy_stack_diablo_setup.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/DIABLO_People_Tracking">行人跟踪</a></td>
  	<td>由 刘诗阳 开发的 DIABLO 行人跟踪示例：<a href="https://www.bilibili.com/video/BV1BZtWebEWF/?spm_id_from=333.337.search-card.all.click">点击查看视频</a></td>
  	<td><a href="https://github.com/DDTRobot/DIABLO_People_Tracking"><img src="https://img.shields.io/github/stars/ddtrobot/DIABLO_People_Tracking.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/Col_DIABLO_Issac_RL">DIABLO 强化学习示例</a></td>
  	<td>基于 Isaac Gym 的 DIABLO 强化学习训练示例，由 刘思扬 开发：<a href="https://www.bilibili.com/video/BV1WES1YwE1f/?spm_id_from=333.337.search-card.all.click">点击查看视频</a></td>
  	<td><a href="https://github.com/DDTRobot/Col_DIABLO_Issac_RL"><img src="https://img.shields.io/github/stars/ddtrobot/Col_DIABLO_Issac_RL.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/diablo_matlab_ros2">DIABLO ROS2 MATLAB 示例</a></td>
  	<td>基于 ROS2 的 DIABLO MATLAB 控制示例，使用上层API控制 DIABLO</td>
  	<td><a href="https://github.com/DDTRobot/diablo_matlab_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_matlab_ros2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
  	<td colspan='4'><blockquote><small><h4>● 注：以上开发者仓库并非官方维护。
● 在这些仓库提交的 Issue 会同步给相关开发者，欢迎反馈。</h4></small></blockquote></td>
  </tr>
</table>



---

[English](./README.md) | **中文**