# life-bullet
## 项目概述/project outline
The game is called Life bullet, and as the name suggests, it is a bullet with a life. Even in a stagnant green environment, players can pick up the phone to open the project, fire lifebullet, and create their own virtual garden by growing virtual plants on the ground.

<img width="360" height="640" scr="github.com/lllllau/Life-Bullet/assets/163080192/dc4887b2-1017-481a-92aa-09294ab90932"/>

***
## 安装说明/Installation instructions
### 游戏所需的平台和设备/The platform and equipmentrequired for the game
1. Unity 2022.3.17f1c1
2. Xcode 15.2
3. iPhone with lidar capability
### 安装游戏的步骤/Steps to install the game
1. 克隆此仓库
2. 打开Unity并导入项目
3. 安装必要的依赖项，包括AR Foundation和ARKit Face Tracking
4. 在你的设备上运行项目

1.Clone the repository
2.Open Unity and import the project
3.Install the necessary dependencies, including AR Foundation and ARKit Face Tracking
4.Run the project on your device
***
##  游戏玩法/Game play
Sample AR-轻轻晃动手机，确保平面被手机充分识别，可通过手机中平面的白色边框来确认；对准平面后，点击屏幕，让子弹射出，在子弹接触平面的地方植株长出，每次长出的植物随机出现，让自制虚拟花园更具多样性。

（彩蛋）Face tracking-人体及面部出现在屏幕中，点击屏幕子弹射中目标为人体时，虚拟面部服饰生成。

Sample AR- Gently shake the phone to ensure that the plane is fully recognized by the phone, which can be confirmed by the white border of the plane in the phone; After aligning the plane, click on the screen, let the bullet shoot out, plants grow where the bullet touches the plane, and the plants that grow each time appear randomly, making the self-made virtual garden more diverse.

(Egg) Face tracking- Human body and face appear on the screen, click on the screen when the bullet hits the target of human body, virtual facial clothing will be generated.

![lAHPD3Ir6pTakCnNAdjNASw_300_472](https://github.com/lllllau/Life-Bullet/assets/163080192/814c93e7-7f5e-4d11-9833-596621ef98e5)
![lAHPJwKt64F3kBfNAdzNASw_300_476](https://github.com/lllllau/Life-Bullet/assets/163080192/3de7f6a5-71a8-4312-b379-39d8ea25a27d)

***
## 技术实现/Technical realization
此项目使用了Unity和AR Foundation来实现AR功能。我使用了AR Foundation samples中的Sample AR和Face Pose作为基础，通过它们我们可以在现实世界中放置虚拟对象，并跟踪用户的面部。

在游戏设计方面，我们使用了第一人称射击游戏的常见设计模式。玩家可以在现实世界中移动来控制游戏中的角色，通过点击屏幕来射击目标。

我们还使用了Unity的物理引擎来处理射击和碰撞效果。当玩家射击时，我们会创建一个子弹对象，并给它一个向前的力，使其向目标移动。当子弹碰到目标时，我们会检测碰撞并处理相应的效果。
此外，我们还使用了Unity的动画系统以及粒子系统来创建一些视觉效果，如射击动画和目标被击中的动画以及植物摇曳动画。

This project uses Unity and AR Foundation to implement AR functionality. I used the Sample AR and Face Pose in the AR Foundation samples as the basis through which we can place virtual objects in the real world and track the user's face.

In terms of game design, we used a common design pattern for first-person shooters. Players can move around the real world to control characters in the game, tapping the screen to shoot targets.

We also used Unity's physics engine to handle shooting and collision effects. When the player shoots, we create a bullet object and give it a forward force to move it towards the target. When the bullet hits the target, we detect the collision and process the effects accordingly.
In addition, we used Unity's animation system and particle system to create some visual effects, such as shooting animations and animations of targets being hit, and swaying plants.
***
## 项目流程/Project process
### 方案设计/Conceptual design
在设计阶段，我们首先确定了游戏的基本概念和规则。然后，我们设计了游戏的用户界面和交互方式。最终确定为第一人称射击类游戏。

In the design phase, we first determined the basic concepts and rules of the game. Then, we designed the user interface and interaction methods for the game. It was ultimately determined to be a first person shooter game.

![微信图片_20240423184734](https://github.com/lllllau/Life-Bullet/assets/163080192/5b5c6272-bd17-4e6b-9460-73c0b81cb1d4)

### 项目开发/Project development
在开发阶段，我们使用Unity和AR Foundation来实现游戏的主要功能。我们使用Sample AR和Face Pose来在现实世界中放置虚拟对象，并跟踪用户的面部表情。我们还使用Unity的物理引擎和动画系统来处理射击和碰撞效果，以及创建视觉效果。

In the development phase, we use Unity and AR Foundation to implement the main features of the game. We use Sample AR and Face Pose to place virtual objects in the real world and track user facial expressions. We also use Unity's physics engine and animation system to handle shooting and collision effects, as well as create visual effects.
### 测试/test
在测试阶段，我们进行了多轮的内部测试，以确保游戏的稳定性和性能。我们还收集了用户反馈，以进一步改进游戏。

During the testing phase, we conducted multiple rounds of internal testing to ensure the stability and performance of the game. We also collected user feedback to further improve the game.
***
## 计划中/Operation in progress
子弹能够实现换弹夹功能，按弹夹种类不同依次可生成藓类植物、灌木和树木等，增加更多美术资产，进一步增加自制虚拟花园多样性以及可玩性。

虚拟服饰能够实现在人体上盘绕生长的效果。

Bullets can change magazines, which can generate moss plants, shrubs and trees according to different types of magazines, adding more art assets and further increasing the diversity and playability of self-made virtual gardens.

Virtual clothing can achieve the effect of winding and growing on the human body.
***
## 致谢/Acknowledgeme
指导老师：俞同舟，卢泳如

advisor：Yu Tongzhou, Lu Yongru.
