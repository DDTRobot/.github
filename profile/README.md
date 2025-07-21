## Welcome to Direct Drive Technology Robotics Team
![direct-drive-logo](https://directdrive.com/public/uploads/images/20220221/4830a265658b4afeeccf7deda5bc044d.png)
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
Direct Drive Technology was found in 2020, committed to using direct drive motors to replace the reduction gear in any machine,making the original delicate and noisy traditonal robot reborn.

Direct Drive Technology Robotics Team was setup since 2022, mainly focus on mobile robots such as [bipedal-wheel robot](https://www.bilibili.com/video/BV1tM4y1Z7VY?spm_id_from=player_end_recommend_autoplay&vd_source=8ab3473c3214c5120c93d5ac5fbba539) and [quadruped-wheel robot](https://www.bilibili.com/video/BV1Pn4y1R7eg/?spm_id_from=333.337.search-card.all.click). We also use the [modualized designing method](https://www.bilibili.com/video/BV1gf42117yt/?spm_id_from=333.337.search-card.all.click&vd_source=8ab3473c3214c5120c93d5ac5fbba539) to design our robot.



[Official Website of Direct Drive Technology](https://directdrive.com/)

[Direct Drive Shop](https://shop.directdrive.com/)

[Youtube for DDT](https://www.youtube.com/@directdrivetech4558)

[BILIBILI video website of the DDT](https://space.bilibili.com/2110984062?spm_id_from=333.337.0.0)

[BILIBILI video website of the DDT Robotics Team](https://space.bilibili.com/3546755798928026?spm_id_from=333.337.0.0)

### Manual

[TITA Manual - Chinese version](https://tita-development-manual-uc.readthedocs.io/zh-cn/latest/ )

[TITA Manual - English version](https://tita-ubuntu-manual-english.readthedocs.io/en/latest/)

[TITA Extension Board Opensource](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620)


> *Note: Since Sept. 2024, All TITA is switched to Ubuntu version. If you are with the Yocto version, refer [here](https://tita-development-manual-ye.readthedocs.io/en/latest/ ) 


### Update Info
| Date        | Brief info   |
| --------   | -----  | 
|20241104| Add ros2 control interface for joint control in the orin nx of TITA|
|20241202|Add DIABLO ROS2 MATLAB Control example|
|20241204|Add TITA ROS2 MATLAB Control example|
|20250210|[Add Airbot robotics arm control samples](https://github.com/DDTRobot/airbot_on_tita)|
|20250226|[Add Extension Board hardware opensource](https://oshwhub.com/jiqiren01/tita-kuo-zhan-jie-kou-kai-yuan-2024-0620)|
|20250309|[Add official TITA Reinforcement Learning Sample based on Isaacgym and Webots 2023b](https://github.com/DDTRobot/tita_rl)|
|20250314|[Add official TITA CANFD reading examples](https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main)|
|20250328|[Add a webots2023b + ros2 control docker](https://github.com/DDTRobot/webots2023b_ros2_docker)|
|20250407|Fix docker support bugs in [tita_rl_sim2sim2real](https://github.com/DDTRobot/tita_rl_sim2sim2real) <br> and the [webots_ros2_docker](https://github.com/DDTRobot/webots2023b_ros2_docker)|
|20250414|Update docker link in [diablo simulation environment](https://github.com/DDTRobot/diablo-sim-env)|

### 🍿 Officially Maintained Repositories

#### TITA
##### Simulation
| Title        | Descroption   |
| --------   |:----- | 
| [TITA basic simulation environment](https://github.com/DDTRobot/tita-sim-env) | tita basic simulation environment based on webots, with windows and linux executable samples. ![Github stars](https://img.shields.io/github/stars/DDTRobot/tita-sim-env.svg)| 
| [TITA ROS2 SDK Demo](https://github.com/DDTRobot/TITA-SDK-ROS2)                 |      A quick start demo that run on TITA ROS2 SDK in real TITA Robot. Only supported in Ubuntu!!               ![Github stars](https://img.shields.io/github/stars/DDTRobot/TITA-SDK-ROS2.svg)|
|[TITA ROS2 Control Sim](https://github.com/DDTRobot/TITA_ROS2_Control_Sim) | TITA ROS2 Control simulation environment. Webots and Gazebo Supported. ![Github stars](https://img.shields.io/github/stars/DDTRobot/TITA_ROS2_Control_Sim.svg)|
|[TITA URDF Description for ROS2 Control Sim](https://github.com/DDTRobot/TITA_Description) |TITA URDF Description, mainly used by ros2 control sim. ![Github stars](https://img.shields.io/github/stars/DDTRobot/TITA_Description.svg) |
|**[TITA RL](https://github.com/DDTRobot/tita_rl)**|**Officially support TITA reinforcement learning environment, as well as the TITATIT-Quadruped mode environment**  ![Github stars](https://img.shields.io/github/stars/DDTRobot/tita_rl.svg)|
> Note : TITA can directly control the motor's torque through the ros2 control interface, or USB2CAN. If help is needed leave issue or contact our FAE.

##### Tools
| Title        | Descroption   |
| --------   |:----- | 
|[TITA ROS2 Control Low level Interface](https://github.com/DDTRobot/tita_hardware_ros2_control)| TITA ROS2 Control Low level interface. Deployed on the Orin NX in TITA. ![Github stars](https://img.shields.io/github/stars/DDTRobot/tita_hardware_ros2_control.svg)|
|[TITA Remote Control Pairing Script](https://github.com/DDTRobot/TITA-RC-Pairing)|Script for Updating the TITA Remote Control pairing. Install on TITA's main board|
|[TITA OTA Script](https://github.com/DDTRobot/TITA-OTA)| Script for updating TITA's MCU board. Install on TITA's main board|
|[Airbot robotics arm control on TITA](https://github.com/DDTRobot/airbot_on_tita)| ROS node for controlling the Airbot arm on TITA. ![Github stars](https://img.shields.io/github/stars/DDTRobot/airbot_on_tita.svg)|
|[Use joystick to control the arm on TITA](https://github.com/DDTRobot/airbot_joy)|ROS node for controlling the Airbot arm with TITA's joystick.  ![Github stars](https://img.shields.io/github/stars/DDTRobot/airbot_joy.svg)|
|[TITA CANFD Interface](https://github.com/DDTRobot/TITA_CAN_Inerface/tree/main)|**Directly read the CANFD information from TITA. You can choose either your PC or TITA's inner Orin Nx** ![Github stars](https://img.shields.io/github/stars/DDTRobot/TITA_CAN_Inerface.svg)|
> Note : TITA can directly control the motor's torque through the ros2 control interface, or USB2CAN. If help is needed leave issue or contact our FAE.
#### DIABLO
| Title        | Descroption   |
| --------   |:----- | 
| [DIABLO basic simulation environment](https://github.com/DDTRobot/diablo-sim-env)        |    DIABLO simulation environment based on webots, including how to install webots by docker or on system   | 
| [DIABLO ROS2 SDK](https://github.com/DDTRobot/diablo_ros2)        |    DIABLO ROS2 SDK to run on a real DIABLO robot    |
|[DIABLO ROS1 SDK](https://github.com/DDTRobot/diablo_sdk)| DIABLO ROS1 SDK to run the real DIABLO robot |

>* Note : If you would like to control the DIABLO via its joint interface, please contact our FAE.

#### Motors
| Title        | Descroption   |
| --------   | :------ | 
|[Control the P10 motor on TITA](https://github.com/DDTRobot/p10-ros2-node)| A ROS2 node to control a single P10 moto, which is a QDD motor developed by Direct Drive Technology|
| [Direct Drive motor control examples](https://github.com/DDTRobot/motor-driver-examples)  | Driver examples for M0602C and M1502D  |

### 🧙 Recommended Developer's Repository
| Title        | Descroption   |
| --------   | :-----  | 
|      [CMU Navigation based on DIABLO](https://github.com/DDTRobot/autonomy_stack_diablo_setup)  |    A navigation example on DIABLO, based on CMU Ji Zhang's work : [View the video](https://www.bilibili.com/video/BV1Ws421T7TJ/?spm_id_from=333.1387.homepage.video_card.click)     |
|[People Tracking](https://github.com/DDTRobot/DIABLO_People_Tracking)| A people tracking function on DIABLO, base on Shiyang Liu's work : [View the video](https://www.bilibili.com/video/BV1BZtWebEWF/?spm_id_from=333.337.search-card.all.click) |
|[DIABLO RL-sample](https://github.com/DDTRobot/Col_DIABLO_Issac_RL) | DIABLO RL training sample on ISSAC Gym, based on Siyang Liu's work : [view the video](https://www.bilibili.com/video/BV1WES1YwE1f/?spm_id_from=333.337.search-card.all.click)  |
|[DIABLO ROS2 MATLAB Sample](https://github.com/DDTRobot/diablo_matlab_ros2)|MATLAB Control sample, using high level api of DIABLO to control, based on ROS2|
|[TITA ROS2 MATLAB Sample](https://github.com/DDTRobot/tita_matlab_ros2)|TITA's MATLAB Control sample, using high level api of TITA to control, based on ROS2 |
|[TITA Walking Reinforcement Learning](https://github.com/DDTRobot/TITA_ISAACGYM_DRL)|TITA example on walking based on Isaacgym, [view the video](https://www.bilibili.com/video/BV1FfBAYyEnx/?spm_id_from=333.337.search-card.all.click&vd_source=8ab3473c3214c5120c93d5ac5fbba539)|
|[TITA app](https://github.com/DDTRobot/tita-app)|A TITA apk used on Android, allows to control TITA on your Android smartphone.|
|[TITA UWB follower](https://github.com/DDTRobot/tita_uwb_follower)|A TITA follower using UWB, which can let the robot follows the tag|
>* Note : The developer's repository is not officialy maintained.
>* Your issues uploaded to the developer's repository will be synchronized to the developers, which is welcomed.
