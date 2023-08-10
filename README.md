# University_Freshman_Registration_System
大学新生报到系统
## 介绍
介于深北莫的不断扩招，新生注册服务压力也逐年增加，于是我们想做一个用于新生注册的智能系统来辅助我们的志愿者来统计分析注册数据，帮助新生实现自助注册，减少他们的压力。

## 目前想法
通过局域网实现手机与自己电脑的互联，然后使用手机获取数据并交由电脑进行处理。



## 发展规划
### 第一阶段
- 构建系内志愿者的局域网，以收集照片的电脑作为服务器处理信息。
- 以安卓手机或者另外一台电脑作为客户端上传收集的资料信息。
- 
    [电脑服务端程序](https://github.com/LJW0401/University_Freshman_Registration_System_PCServer)<br>
    [电脑客户端程序](https://github.com/LJW0401/University_Freshman_Registration_System_PCClient)<br>
    [安卓客户端程序](https://github.com/LJW0401/University_Freshman_Registration_System_AndroidClient)<br>
<!-- - 创建Windows端服务程序，自动分类，甄别考生照片。
- 创建Android端服务程序，统计新生报到材料情况并上传至数据库，当有缺失的同学回来时可以在原有基础上继续添加报到材料。
- 创建数据库云服务，后端统计材料状况。 -->

### 第二阶段
- 通过二维码、NFC等技术结合机器人硬件帮助志愿者整理材料。