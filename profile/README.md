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


### Update Info
| Date        | Brief info   |
| --------   | -----  | 
| 20241030|   1. Add TITA ROS2 Control Simulation environment <br>   2. Developer's repository updated. |

### 🍿 Officially Maintained Repositories

#### TITA
| Title        | Descroption   |
| --------   | -----:  | 
| [TITA basic simulation environment](https://github.com/DDTRobot/tita-sim-env)     | tita basic simulation environment based on webots, with windows and linux executable samples.| 
|      [TITA ROS2 SDK](https://github.com/DDTRobot/TITA-SDK-ROS2)                 |       TITA ROS2 SDK to run a real TITA Robot, based on ubuntu 22.04              |
|[TITA ROS2 Control Sim](https://github.com/DDTRobot/TITA_ROS2_Control_Sim) | TITA ROS2 Control simulation environment. Webots and Gazebo Supported.|
|[TITA URDF Description for ROS2 Control Sim](https://github.com/DDTRobot/TITA_Description) |TITA URDF Description, mainly used by ros2 control sim |
>* Note : TITA can directly control the motor's torque through the ros2 control interface, or USB2CAN. If help is needed leave issue or contact our FAE.

#### DIABLO
| Title        | Descroption   |
| --------   | -----:  | 
| [DIABLO basic simulation environment](https://github.com/DDTRobot/diablo-sim-env)        |    DIABLO simulation environment based on webots, including how to install webots by docker or on system   | 
| [DIABLO ROS2 SDK](https://github.com/DDTRobot/diablo_ros2)        |    DIABLO ROS2 SDK to run on a real DIABLO robot    |
|[DIABLO ROS1 SDK](https://github.com/DDTRobot/diablo_sdk)| DIABLO ROS1 SDK to run the real DIABLO robot |

>* Note : If you would like to control the DIABLO via its joint interface, please contact our FAE.

#### Motors
| Title        | Descroption   |
| --------   | -----:  | 
|[Control the P10 motor on TITA](https://github.com/DDTRobot/p10-ros2-node)| A ROS2 node to control a single P10 moto, which is a QDD motor developed by Direct Drive Technology|
| [Direct Drive motor control examples](https://github.com/DDTRobot/motor-driver-examples)  | Driver examples for M0602C and M1502D  |

### 🧙 Recommended Developer's Repository
| Title        | Descroption   |
| --------   | -----:  | 
|      [CMU Navigation based on DIABLO](https://github.com/DDTRobot/autonomy_stack_diablo_setup)  |    A navigation example on DIABLO, based on CMU Ji Zhang's work : [View the video](https://www.bilibili.com/video/BV1Ws421T7TJ/?spm_id_from=333.1387.homepage.video_card.click)     |
|[People Tracking](https://github.com/DDTRobot/DIABLO_People_Tracking)| A people tracking function on DIABLO, base on Shiyang Liu's work : [View the video]((https://www.bilibili.com/video/BV1BZtWebEWF/?spm_id_from=333.337.search-card.all.click)) |
|[TITA CAN Interface sample](https://github.com/DDTRobot/Col_TITA_CAN_Inerface)| TITA CAN interface sample, use usb2can to control TITA's movement, without installing ROS or ROS2 |
|[DIABLO RL-sample](https://github.com/DDTRobot/Col_DIABLO_Issac_RL) | DIABLO RL training sample on ISSAC Gym.  |
>* Note : The developer's repository is not officialy maintained.
>* Your issues uploaded to the developer's repository will be synchronized to the developers, which is welcomed.
