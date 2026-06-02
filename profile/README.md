**English** | [中文](./README_zh.md)

# Welcome to Direct Drive Technology Robotics Team

![direct-drive-logo](https://directdrive.com/public/uploads/images/20220221/4830a265658b4afeeccf7deda5bc044d.png)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

Direct Drive Technology was founded in 2020, committed to using direct drive motors to replace the reduction gear in any machine, making the original delicate and noisy traditional robot reborn.

Direct Drive Technology Robotics Team was setup since 2022, mainly focus on mobile robots such as [bipedal-wheel robot](https://www.bilibili.com/video/BV1tM4y1Z7VY?spm_id_from=player_end_recommend_autoplay&vd_source=8ab3473c3214c5120c93d5ac5fbba539) and [quadruped-wheel robot](https://www.bilibili.com/video/BV1Pn4y1R7eg/?spm_id_from=333.337.search-card.all.click). We also use the [modularized designing method](https://www.bilibili.com/video/BV1gf42117yt/?spm_id_from=333.337.search-card.all.click&vd_source=8ab3473c3214c5120c93d5ac5fbba539) to design our robot.

[![Website](https://img.shields.io/badge/Official%20Website-0052CC?style=flat&logo=google-chrome)](https://directdrive.com/) [![Shop](https://img.shields.io/badge/%20Shop-8A2BE2?style=flat&logo=shopee)](https://shop.directdrive.com/) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@directdrivetech4558) [![Bilibili](https://img.shields.io/badge/Bilibili-DDT-00A1D6?style=flat&logo=bilibili&logoColor=white&labelColor=FB7299)](https://space.bilibili.com/2110984062?spm_id_from=333.337.0.0) [![Bilibili](https://img.shields.io/badge/Bilibili-DDT%20Robotics%20Team-00A1D6?style=flat&logo=bilibili&logoColor=white&labelColor=FB7299)](https://space.bilibili.com/3546755798928026?spm_id_from=333.337.0.0)

### Manual

#### D-Infinite

[D-Infinite Manual - Chinese version](https://d1-development-manual-cn.readthedocs.io/zh-cn/latest/)

[D-Infinite Manual - English version](https://y1.readthedocs.io/en/latest/)

#### TITA

[TITA Manual - Chinese version](https://tita-development-manual-uc.readthedocs.io/zh-cn/latest/ )

[TITA Manual - English version](https://tita-ubuntu-manual-english.readthedocs.io/en/latest/)

[TITA Extension Board Opensource](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620)

> *Note: Since Sept. 2024, All TITA is switched to Ubuntu version. If you are with the Yocto version, refer [here](https://tita-development-manual-ye.readthedocs.io/en/latest/ )

### Update Info


| Date       | Brief info                                                                                                                                                                                 |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 2024-11-04 | Add ros2 control interface for joint control in the orin nx of TITA                                                                                                                        |
| 2024-12-02 | Add DIABLO ROS2 MATLAB Control example                                                                                                                                                     |
| 2024-12-04 | Add TITA ROS2 MATLAB Control example                                                                                                                                                       |
| 2025-02-10 | [Add Airbot robotics arm control samples](https://github.com/DDTRobot/airbot_on_tita)                                                                                                      |
| 2025-02-26 | [Add Extension Board hardware opensource](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620)                                                                          |
| 2025-03-09 | [Add official TITA Reinforcement Learning Sample based on Isaacgym and Webots 2023b](https://github.com/DDTRobot/tita_rl)                                                                  |
| 2025-03-14 | [Add official TITA CANFD reading examples](https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main)                                                                                        |
| 2025-03-28 | [Add a webots2023b + ros2 control docker](https://github.com/DDTRobot/webots2023b_ros2_docker)                                                                                             |
| 2025-04-07 | Fix docker support bugs in[tita_rl_sim2sim2real](https://github.com/DDTRobot/tita_rl_sim2sim2real) <br/> and the [webots_ros2_docker](https://github.com/DDTRobot/webots2023b_ros2_docker) |
| 2025-04-14 | Update docker link in[diablo simulation environment](https://github.com/DDTRobot/diablo-sim-env)                                                                                           |
| 2025-11-04 | Update RL training of[titatit-quadruped-wheeled robot](https://github.com/DDTRobot/quadruped-wheel-titatit-rl)                                                                             |
| 2025-11-20 | Update the link for[D-INFINITE ROS2-based sim2sim/sim2real](https://github.com/DDTRobot/ddt_ros2_control/)                                                                                 |
| 2025-12-01 | Update the link for[D-INFINITE RL Isaac Gym](https://github.com/DDTRobot/ddt_rl_isaacgym)                                                                                                  |
| 2026-05-20 | [Add D1 ROS2 SDK Demo](https://github.com/DDTRobot/D1-ROS2-SDK-Demo) and [D1 airbot-play Control Demo](https://github.com/DDTRobot/airbot-environment-deployment)                          |
| 2026-06-02 | [Add D-INFINITE IsaacLab RL training](https://github.com/DDTRobot/DDT_Lab/tree/np3o)                                                                                                      |

### 🍿 Officially Maintained Repositories

<table>
  <tr>
    <th>Robot</th>
  	<th>Type</th>
    <th>Title</th>
  	<th>Description</th>
    <th>Stars</th>
  </tr>
  <tr>
    <td rowspan='6'>D‑INFINITE</td>
  	<td rowspan='3'>Simulation</td>
    <td><a href="https://github.com/DDTRobot/ddt_rl_isaacgym">D1 rl isaacgym</a></td>
    <td>Isaac Gym Environments for Legged Robots.</td>
    <td><a href="https://github.com/DDTRobot/ddt_rl_isaacgym"><img src="https://img.shields.io/github/stars/ddtrobot/ddt_rl_isaacgym.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/DDT_Lab/tree/np3o">D1 rl isaaclab</a></td>
    <td>Isaac Lab Environments for Legged Robots.</td>
    <td><a href="https://github.com/DDTRobot/DDT_Lab/tree/np3o"><img src="https://img.shields.io/github/stars/DDTRobot/DDT_Lab.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/ddt_ros2_control/">D1 sim2sim/sim2real</a></td>
    <td>A ROS2 workspace containing hardware/simulation bridges and hybrid controllers capable of FSM logic and ONNX RL inference.</td>
    <td><a href="https://github.com/DDTRobot/ddt_ros2_control"><img src="https://img.shields.io/github/stars/ddtrobot/ddt_ros2_control.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td rowspan='2'>Tools</td>
    <td><a href="https://github.com/DDTRobot/D1-ROS2-SDK-Demo">D1 ROS2 SDK Demo</a></td>
    <td>A quick start demo that runs on D1 ROS2 SDK in a real D1 Robot. Only supported on Ubuntu.</td>
    <td><a href="https://github.com/DDTRobot/D1-ROS2-SDK-Demo"><img src="https://img.shields.io/github/stars/DDTRobot/D1-ROS2-SDK-Demo?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/airbot-environment-deployment">D1 airbot-play Control Demo</a></td>
    <td>Environment deployment and control demo for the Airbot arm on D1.</td>
    <td><a href="https://github.com/DDTRobot/airbot-environment-deployment"><img src="https://img.shields.io/github/stars/DDTRobot/airbot-environment-deployment.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td colspan="4"><blockquote><small><h5>To access the latest D1 ROS2 release(.deb), please click <a href="https://github.com/DDTRobot/d1_ros2_release/releases">here</h5></small></blockquote></td>
  </tr>
  <tr>
    <td rowspan='13' class="robot-col">TITA</td>
  	<td rowspan='4'>Simulation</td>
    <td><a href="https://github.com/DDTRobot/tita-sim-env">TITA basic simulation environment</a></td>
  	<td>tita basic simulation environment based on webots, with windows and linux executable samples</td>
  	<td><a href="https://github.com/DDTRobot/tita-sim-env"><img src="https://img.shields.io/github/stars/ddtrobot/tita-sim-env.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/TITA_ROS2_Control_Sim">TITA ROS2 Control Sim</a></td>
    <td>TITA ROS2 Control simulation environment. Webots and Gazebo Supported.</td>
  	<td><a href="https://github.com/DDTRobot/TITA_ROS2_Control_Sim"><img src="https://img.shields.io/github/stars/ddtrobot/tita_ros2_control_sim.svg?cacheSeconds=7200" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA_Description">TITA URDF Description for ROS2 Control Sim</a></td>
  	<td>TITA URDF Description, mainly used by ros2 control sim.</td>
    <td><a href="https://github.com/DDTRobot/TITA_Description"><img src="https://img.shields.io/github/stars/ddtrobot/tita_description.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/tita_rl">TITA RL</a></td>
    <td>Officially support TITA reinforcement learning environment, as well as the TITATIT-Quadruped mode environment</td>
    <td><a href="https://github.com/DDTRobot/tita_rl"><img src="https://img.shields.io/github/stars/ddtrobot/tita_rl.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>Note: TITA can directly control the motor's torque through the ROS2 control interface, or USB2CAN. If help is needed leave an issue or contact our FAE.</h5></small></blockquote></td>
  </tr>
  <tr>
  	<td rowspan='7'>Tools</td>
    <td><a href="https://github.com/DDTRobot/TITA-SDK-ROS2">TITA ROS2 SDK Demo</a></td>
  	<td>A quick start demo that run on TITA ROS2 SDK in real TITA Robot. Only supported in Ubuntu!!</td>
    <td><a href="https://github.com/DDTRobot/TITA-SDK-ROS2"><img src="https://img.shields.io/github/stars/DDTRobot/TITA-SDK-ROS2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita_hardware_ros2_control">TITA ROS2 Control Low level Interface</a></td>
    <td>TITA ROS2 Control Low level interface. Deployed on the Orin NX in TITA. </td>
    <td><a href="https://github.com/DDTRobot/tita_hardware_ros2_control"><img src="https://img.shields.io/github/stars/ddtrobot/tita_hardware_ros2_control.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA-RC-Pairing">TITA Remote Control Pairing Script</a></td>
    <td>Script for Updating the TITA Remote Control pairing. Install on TITA's main board </td>
    <td><a href="https://github.com/DDTRobot/TITA-RC-Pairing"><img src="https://img.shields.io/github/stars/DDTRobot/TITA-RC-Pairing.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA-OTA">TITA OTA Script</a></td>
    <td>Script for updating TITA's MCU board. Install on TITA's main board</td>
    <td><a href="https://github.com/DDTRobot/TITA-OTA"><img src="https://img.shields.io/github/stars/DDTRobot/tita-ota.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/airbot_on_tita">Airbot robotics arm control on TITA</a></td>
    <td>ROS node for controlling the Airbot arm on TITA</td>
    <td><a href="https://github.com/DDTRobot/airbot_on_tita"><img src="https://img.shields.io/github/stars/DDTRobot/airbot_on_tita.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/airbot_joy">Use joystick to control the arm on TITA</a></td>
    <td>ROS node for controlling the Airbot arm with TITA's joystick</td>
<td>
  <a href="https://github.com/DDTRobot/airbot_joy"><img src="https://img.shields.io/github/stars/ddtrobot/airbot_joy.svg?cacheSeconds=3600" alt="GitHub stars"></a></td>
  </tr>
  <tr>   
    <td><a href="https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main">TITA CANFD Interface</a></td>
    <td>Directly read the CANFD information from TITA. You can choose either your PC or TITA's inner Orin Nx</td>
    <td><a href="https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main"><img src="https://img.shields.io/github/stars/ddtrobot/tita_can_inerface.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>Note : TITA can directly control the motor's torque through the ros2 control interface, or USB2CAN. If help is needed leave issue or contact our FAE.</h5></small></blockquote></td>
  </tr>
  <tr>   
	<td rowspan='4' class="robot-col">DIABLO</td>
    <td rowspan='1'>Simulation</td>
	<td><a href="https://github.com/DDTRobot/diablo-sim-env">DIABLO basic simulation environment</a></td>
    <td>DIABLO simulation environment based on webots, including how to install webots by docker or on system</td>
    <td><a href="https://github.com/DDTRobot/diablo-sim-env"><img src="https://img.shields.io/github/stars/ddtrobot/diablo-sim-env.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
  	<td rowspan='2'>Tools</td>
	<td><a href="https://github.com/DDTRobot/diablo_ros2">DIABLO ROS2 SDK</a></td>
    <td>DIABLO ROS2 SDK to run on a real DIABLO robot</td>
    <td><a href="https://github.com/DDTRobot/diablo_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_ros2?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>  
  <tr>   
	<td><a href="https://github.com/DDTRobot/diablo_sdk">DIABLO ROS1 SDK</a></td>
    <td>DIABLO ROS1 SDK to run on a real DIABLO robot</td>
    <td><a href="https://github.com/DDTRobot/diablo_sdk"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_sdk?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
      <td colspan="4"><blockquote><small><h5>Note : If you would like to control the DIABLO via its joint interface, please contact our FAE.</h5></small></blockquote></td>
  </tr>
  <tr>   
	<td rowspan='2' class="robot-col">MOTOR</td>
  	<td rowspan='2'>Tools</td>
	<td><a href="https://github.com/DDTRobot/p10-ros2-node">ROS2 Control the P10 motor</a></td>
    <td>A ROS2 node to control a single P10 motor, which is a QDD motor developed by Direct Drive Technology</td>
    <td><a href="https://github.com/DDTRobot/p10-ros2-node"><img src="https://img.shields.io/github/stars/ddtrobot/p10-ros2-node.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>   
	<td><a href="https://github.com/DDTRobot/motor-driver-examples">Direct Drive motor control examples</a></td>
    <td>Driver examples for M0602C and M1502D</td>
    <td><a href="https://github.com/DDTRobot/motor-driver-examples"><img src="https://img.shields.io/github/stars/ddtrobot/motor-driver-examples.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
</table>

### 🧙 Recommended Developer's Repository

<table>
  <tr>
    <th>Robot</th>
    <th>Title</th>
  	<th>Description</th>
    <th>Stars</th>
  <tr>
    <td rowspan='4' class="robot-col">TITA</td>
    <td><a href="https://github.com/DDTRobot/tita_matlab_ros2">TITA ROS2 MATLAB Sample</a></td>
  	<td>TITA's MATLAB Control sample, using high level api of TITA to control, based on ROS2</td>
  	<td><a href="https://github.com/DDTRobot/tita_matlab_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/tita_matlab_ros2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/TITA_ISAACGYM_DRL">TITA Walking Reinforcement Learning</a></td>
  	<td>TITA example on walking based on Isaacgym: <a href="https://www.bilibili.com/video/BV1FfBAYyEnx/?spm_id_from=333.337.search-card.all.click&vd_source=8ab3473c3214c5120c93d5ac5fbba539">View the video</a></td>
  	<td><a href="https://github.com/DDTRobot/TITA_ISAACGYM_DRL"><img src="https://img.shields.io/github/stars/ddtrobot/TITA_ISAACGYM_DRL.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita-app">TITA app</a></td>
  	<td>A TITA apk used on Android, allows to control TITA on your Android smartphone</td>
  	<td><a href="https://github.com/DDTRobot/tita-app"><img src="https://img.shields.io/github/stars/ddtrobot/tita-app.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/tita_uwb_follower">TITA UWB follower</a></td>
  	<td>A TITA follower using UWB, which can let the robot follows the tag</td>
  	<td><a href="https://github.com/DDTRobot/tita_uwb_follower"><img src="https://img.shields.io/github/stars/ddtrobot/tita_uwb_follower.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td rowspan='4' class="robot-col">DIABLO</td>
    <td><a href="https://github.com/DDTRobot/autonomy_stack_diablo_setup">CMU Navigation based on DIABLO</a></td>
  	<td>A navigation example on DIABLO, based on CMU Ji Zhang's work: <a href="https://www.bilibili.com/video/BV1Ws421T7TJ/?spm_id_from=333.1387.homepage.video_card.click">View the video</a></td>
  	<td><a href="https://github.com/DDTRobot/autonomy_stack_diablo_setup"><img src="https://img.shields.io/github/stars/ddtrobot/autonomy_stack_diablo_setup.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/DIABLO_People_Tracking">People Tracking</a></td>
  	<td>A people tracking function on DIABLO, base on Shiyang Liu's work: <a href="https://www.bilibili.com/video/BV1BZtWebEWF/?spm_id_from=333.337.search-card.all.click">View the video</a></td>
  	<td><a href="https://github.com/DDTRobot/DIABLO_People_Tracking"><img src="https://img.shields.io/github/stars/ddtrobot/DIABLO_People_Tracking.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/Col_DIABLO_Issac_RL">DIABLO RL-sample</a></td>
  	<td>DIABLO RL training sample on ISSAC Gym, based on Siyang Liu's work: <a href="https://www.bilibili.com/video/BV1WES1YwE1f/?spm_id_from=333.337.search-card.all.click">View the video</a></td>
  	<td><a href="https://github.com/DDTRobot/Col_DIABLO_Issac_RL"><img src="https://img.shields.io/github/stars/ddtrobot/Col_DIABLO_Issac_RL.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/DDTRobot/diablo_matlab_ros2">DIABLO ROS2 MATLAB Sample</a></td>
  	<td>MATLAB Control sample, using high level api of DIABLO to control, based on ROS2</td>
  	<td><a href="https://github.com/DDTRobot/diablo_matlab_ros2"><img src="https://img.shields.io/github/stars/ddtrobot/diablo_matlab_ros2.svg?cacheSeconds=3600" alt="GitHub stars" ></a></td>
  </tr>
  <tr>
  	<td colspan='4'><blockquote><small><h4>● Note : The developer's repository is not officialy maintained.<br>● Your issues uploaded to the developer's repository will be synchronized to the developers, which is welcomed.</h4></small></blockquote></td>
  </tr>
</table>

> * **English** | [中文](./README_zh.md)
