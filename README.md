# 三维与后期技术

Table of Contents
=================

   * [三维与后期技术](#三维与后期技术)
     * [飞行器模型建模](#飞行器模型建模)
       * [整体模型](#整体模型)
       * [主体](#主体)
         * [1.主体原型 | MainBodyPrototype](#1主体原型--mainbodyprototype)
         * [2.顶部组件  | TopComponent](#2顶部组件---topcomponent)
         * [3.风挡 | Windshield](#3风挡--windshield)
         * [4.前保险杠 | FrontBumper](#4前保险杠--frontbumper)
         * [5.通风窗 | VentilationWindow](#5通风窗--ventilationwindow)
           * [前通风窗](#前通风窗)
           * [前通风盖板](#前通风盖板)
           * [后通风窗](#后通风窗)
           * [后部组件](#后部组件)
         * [6.引擎 | Engine](#6引擎--engine)
         * [7.前控制面板 | FrontControlPanel](#7前控制面板--frontcontrolpanel)
         * [8.平滑 | Smoothing](#8平滑--smoothing)
           * [添加循环边](#添加循环边)
           * [添加折痕](#添加折痕)
       * [机械臂](#机械臂)
         * [1.前臂 | FroeArm](#1前臂--froearm)
         * [2.前臂连接器 | FrontConnector](#2前臂连接器--frontconnector)
         * [3.后臂 | HindArm](#3后臂--hindarm)
         * [4.下臂连接器 | LowerConnector](#4下臂连接器--lowerconnector)
         * [5.下臂 | LowerArm](#5下臂--lowerarm)
         * [6.钳子 | Pliers](#6钳子--pliers)
         * [7.钳子基座 | PliersPedestal](#7钳子基座--plierspedestal)
         * [8.钳子管索 | PliersTube](#8钳子管索--plierstube)
     * [纹理材质](#纹理材质)
       * [效果整体图](#效果整体图)
       * [纹理图](#纹理图)
         * [Antenna](#antenna)
         * [Arm decorate](#arm-decorate)
         * [Arm inner](#arm-inner)
         * [Arm outer](#arm-outer)
         * [Bilnd](#bilnd)
         * [Claw](#claw)
         * [Engine](#engine)
         * [Mainbody](#mainbody)
         * [Window screen](#window-screen)
     * [动画](#动画)
       * [场景](#场景)
       * [路径动画](#路径动画)
     * [灯光 &amp; 渲染](#灯光--渲染)
       * [渲染练习](#渲染练习)
       * [飞行器渲染效果](#飞行器渲染效果)
         * [只有天光](#只有天光)
         * [8束光照明系统](#8束光照明系统)
         * [粒子感](#粒子感)
     * [剪辑](#剪辑)
       * [时间轴](#时间轴)
       * [时间重映射](#时间重映射)
       * [蒙版路径](#蒙版路径)
       * [故事线](#故事线)

-----

## 飞行器模型建模

### 整体模型

<img src="Aircraft/ScreenShots/FinalModel/final_model1.png" alt="final_model1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/FinalModel/final_model2.png" alt="final_model2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/FinalModel/final_model4.png" alt="final_model4" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/FinalModel/final_model3.png" alt="final_model3" style="zoom:50%;" />

----

### 主体

#### 1.主体原型 | MainBodyPrototype

<img src="Aircraft/ScreenShots/MainBody/1.MainBodyPrototype/MainBodyPrototype1_1.png" alt="MainBodyPrototype1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/1.MainBodyPrototype/MainBodyPrototype1_2.png" alt="MainBodyPrototype1_2" style="zoom:50%;" />

#### 2.顶部组件  | TopComponent

<img src="Aircraft/ScreenShots/MainBody/2.TopComponent/TopComponent1_1.png" alt="TopComponent1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/2.TopComponent/TopComponent1_2.png" alt="TopComponent1_2" style="zoom:50%;" />

#### 3.风挡 | Windshield

<img src="Aircraft/ScreenShots/MainBody/3.Windshield/Windshield1_1.png" alt="Windshield1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/3.Windshield/Windshield1_2.png" alt="Windshield1_2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/3.Windshield/Windshield1_3.png" alt="Windshield1_3" style="zoom:50%;" />

#### 4.前保险杠 | FrontBumper

<img src="Aircraft/ScreenShots/MainBody/4.FrontBumper/FrontBumper1_1.png" alt="FrontBumper1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/4.FrontBumper/FrontBumper1_2.png" alt="FrontBumper1_2" style="zoom:50%;" />

#### 5.通风窗 | VentilationWindow

##### 前通风窗

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Front/VentilationWindow1_1.png" alt="VentilationWindow1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Front/VentilationWindow1_2.png" alt="VentilationWindow1_2" style="zoom:50%;" />

##### 前通风盖板

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Front/VentilationCover1_1.png" alt="VentilationCover1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Front/VentilationCover1_2.png" alt="VentilationCover1_2" style="zoom:50%;" />

##### 后通风窗

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Back/VentilationWindow1_1.png" alt="VentilationWindow1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Back/VentilationWindow1_2.png" alt="VentilationWindow1_2" style="zoom:50%;" />

##### 后部组件

<img src="Aircraft/ScreenShots/MainBody/5.VentilationWindow/Back/BackComponent1_1.png" alt="BackComponent1_1" style="zoom:50%;" />

#### 6.引擎 | Engine

<img src="Aircraft/ScreenShots/MainBody/6.Engine/Engine1_1.png" alt="Engine1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/6.Engine/Engine1_2.png" alt="Engine1_2" style="zoom:50%;" />

#### 7.前控制面板 | FrontControlPanel

<img src="Aircraft/ScreenShots/MainBody/7.FrontControlPanel/FrontControlPanel1.png" alt="FrontControlPanel1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/7.FrontControlPanel/FrontControlPanel2.png" alt="FrontControlPanel2" style="zoom:50%;" />

#### 8.平滑 | Smoothing

##### 添加循环边

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_1a.png" alt="Smooth1_1a" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_1b.png" alt="Smooth1_1b" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_2a.png" alt="Smooth1_2a" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_2b.png" alt="Smooth1_2b" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_3a.png" alt="Smooth1_3a" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth1_3b.png" alt="Smooth1_3b" style="zoom:50%;" />

##### 添加折痕

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth2_1a.png" alt="Smooth2_1a" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth2_1b.png" alt="Smooth2_1b" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/MainBody/8.Smooth/Smooth2_2.png" alt="Smooth2_2" style="zoom:50%;" />

-----

### 机械臂

#### 1.前臂 | FroeArm

<img src="Aircraft/ScreenShots/Arm/1.ForeArm/ForeArm1_1.png" alt="ForeArm1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/1.ForeArm/ForeArm1_2.png" alt="ForeArm1_2" style="zoom:50%;" />

#### 2.前臂连接器 | FrontConnector

<img src="Aircraft/ScreenShots/Arm/2.FrontConnector/FrontConnector1.png" alt="FrontConnector1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/2.FrontConnector/FrontConnector2.png" alt="FrontConnector2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/2.FrontConnector/FrontConnector3.png" alt="FrontConnector3" style="zoom:50%;" />

#### 3.后臂 | HindArm

<img src="Aircraft/ScreenShots/Arm/3.HindArm/HindArm1.png" alt="HindArm1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/3.HindArm/HindArm2.png" alt="HindArm2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/3.HindArm/HindArm3.png" alt="HindArm3" style="zoom:50%;" />

#### 4.下臂连接器 | LowerConnector

<img src="Aircraft/ScreenShots/Arm/4.LowerConnector/LowerConnector1.png" alt="LowerConnector1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/4.LowerConnector/LowerConnector2.png" alt="LowerConnector2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/4.LowerConnector/LowerConnector3.png" alt="LowerConnector3" style="zoom:50%;" />

#### 5.下臂 | LowerArm

<img src="Aircraft/ScreenShots/Arm/5.LowerArm/LowerArm1_1.png" alt="LowerArm1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/5.LowerArm/LowerArm1_2.png" alt="LowerArm1_2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/5.LowerArm/LowerArm2_1.png" alt="LowerArm2_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/5.LowerArm/LowerArm3_1.png" alt="LowerArm3_1" style="zoom:50%;" />

#### 6.钳子 | Pliers

<img src="Aircraft/ScreenShots/Arm/6.Pliers/Pliers1_1.png" alt="Pliers1_1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/6.Pliers/Pliers1_2.png" alt="Pliers1_2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/6.Pliers/Pliers2_1.png" alt="Pliers2_1" style="zoom:50%;" />

#### 7.钳子基座 | PliersPedestal

<img src="Aircraft/ScreenShots/Arm/7.PliersPedestal/PliersPedestal1.png" alt="PliersPedestal1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/7.PliersPedestal/PliersPedestal2.png" alt="PliersPedestal2" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/7.PliersPedestal/PliersPedestal3.png" alt="PliersPedestal3" style="zoom:50%;" />

#### 8.钳子管索 | PliersTube

<img src="Aircraft/ScreenShots/Arm/8.PliersTube/PliersTube1.png" alt="PliersTube1" style="zoom:50%;" />

<img src="Aircraft/ScreenShots/Arm/8.PliersTube/PliersTube2.png" alt="PliersTube2" style="zoom:50%;" />

-----

## 纹理材质

### 效果整体图

<img src="Texture/ScreenShots/Effect_picture1.png" alt="Effect_picture1" style="zoom: 25%;" />

<img src="Texture/ScreenShots/Effect_picture2.png" alt="Effect_picture2" style="zoom:25%;" />

<img src="Texture/ScreenShots/Effect_picture3.png" alt="Effect_picture3" style="zoom:25%;" />

<img src="Texture/ScreenShots/Effect_picture4.png" alt="Effect_picture4" style="zoom:25%;" />

<img src="Texture/ScreenShots/Effect_picture5.png" alt="Effect_picture5" style="zoom:25%;" />

-----

### 纹理图

#### Antenna

<img src="Texture/Resources/antenna1_Roughness.png" alt="antenna1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/antenna1_BaseColor.png" alt="antenna1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/antenna1_Metalness.png" alt="antenna1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/antenna1_Normal.png" alt="antenna1_Normal" style="zoom:25%;" />

#### Arm decorate

<img src="Texture/Resources/arm_decorate1_Roughness.png" alt="arm_decorate1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/arm_decorate1_BaseColor.png" alt="arm_decorate1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/arm_decorate1_Metalness.png" alt="arm_decorate1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/arm_decorate1_Normal.png" alt="arm_decorate1_Normal" style="zoom:25%;" />

#### Arm inner

<img src="Texture/Resources/arm_inner1_Roughness.png" alt="arm_inner1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/arm_inner1_BaseColor.png" alt="arm_inner1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/arm_inner1_Metalness.png" alt="arm_inner1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/arm_inner1_Normal.png" alt="arm_inner1_Normal" style="zoom:25%;" />

#### Arm outer

<img src="Texture/Resources/arm_outer1_Roughness.png" alt="arm_outer1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/arm_outer1_BaseColor.png" alt="arm_outer1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/arm_outer1_Metalness.png" alt="arm_outer1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/arm_outer1_Normal.png" alt="arm_outer1_Normal" style="zoom:25%;" />

#### Bilnd

<img src="Texture/Resources/blind1_Roughness.png" alt="blind1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/blind1_BaseColor.png" alt="blind1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/blind1_Metalness.png" alt="blind1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/blind1_Normal.png" alt="blind1_Normal" style="zoom:25%;" />

#### Claw

<img src="Texture/Resources/claw1_Roughness.png" alt="claw1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/claw1_BaseColor.png" alt="claw1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/claw1_Metalness.png" alt="claw1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/claw1_Normal.png" alt="claw1_Normal" style="zoom:25%;" />

#### Engine

<img src="Texture/Resources/engine1_Roughness.png" alt="engine1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/engine1_BaseColor.png" alt="engine1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/engine1_Metalness.png" alt="engine1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/engine1_Normal.png" alt="engine1_Normal" style="zoom:25%;" />

#### Mainbody

<img src="Texture/Resources/mainbody1_Roughness.png" alt="mainbody1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/mainbody1_BaseColor.png" alt="mainbody1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/mainbody1_Metalness.png" alt="mainbody1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/mainbody1_Normal.png" alt="mainbody1_Normal" style="zoom:25%;" />

#### Window screen

<img src="Texture/Resources/windscreen1_Roughness.png" alt="windscreen1_Roughness" style="zoom:25%;" />

<img src="Texture/Resources/windscreen1_BaseColor.png" alt="windscreen1_BaseColor" style="zoom:25%;" />

<img src="Texture/Resources/windscreen1_Metalness.png" alt="windscreen1_Metalness" style="zoom:25%;" />

<img src="Texture/Resources/windscreen1_Normal.png" alt="windscreen1_Normal" style="zoom:25%;" />

-----

## 动画

### 场景

<img src="Animation/ScreenShots/background.png" alt="background" style="zoom:50%;" />

-----

### 路径动画

![path_animation](Animation/ScreenShots/path_animation.png)

![path_animation2](Animation/ScreenShots/path_animation2.png)

-----

## 灯光 & 渲染

### 渲染练习

![exercise1](Rendering/ScreenShots/exercise1.png)

------

### 飞行器渲染效果

#### 只有天光

108帧

![108](Rendering/Aircraft/skydome light/108.png)

------

#### 8束光照明系统

<img src="Rendering/ScreenShots/lighting system.png" alt="image-20191226221038495" style="zoom: 50%;" />

初始帧

![16](Rendering/Aircraft/lighting system/16.png)

88帧

![88](Rendering/Aircraft/lighting system/88.png)

108帧

![108](Rendering/Aircraft/lighting system/108.png)

153帧

![153](Rendering/Aircraft/lighting system/153.png)

176帧

![176](Rendering/Aircraft/lighting system/176.png)

------

#### 粒子感

89帧

![89](Rendering/Aircraft/particle/89.png)

109帧

![109](Rendering/Aircraft/particle/109.png)

149帧

![149](Rendering/Aircraft/particle/149.png)

-----

## 剪辑

### 时间轴

![image-20191226222551580](Edit/ScreenShots/technology/timer_shaft.png)

------

### 时间重映射

![time_remapping](Edit/ScreenShots/technology/time_remapping.png)

------

### 蒙版路径

![masking_path](Edit/ScreenShots/technology/masking_path.png)

------

### 故事线

![story1](Edit/ScreenShots/story/story1.png)

![story2](Edit/ScreenShots/story/story2.png)

![story3](Edit/ScreenShots/story/story3.png)

![story4](Edit/ScreenShots/story/story4.png)

![story5](Edit/ScreenShots/story/story5.png)

![story6](Edit/ScreenShots/story/story6.png)

![story7](Edit/ScreenShots/story/story7.png)

![story8](Edit/ScreenShots/story/story8.png)

![story9](Edit/ScreenShots/story/story9.png)
