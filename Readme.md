# use_nas

![my workflow](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)
![GitHub file size in bytes](https://img.shields.io/github/size/erbiaoger/code/use_nas.md?color=green&label=use_nas%20file%20size)

# Table of contents

- [use\_nas](#use_nas)
- [Table of contents](#table-of-contents)
  - [说明](#说明)
  - [使用](#使用)
    - [windows](#windows)
    - [linux (ubuntu)](#linux-ubuntu)
    - [Mac](#mac)
  - [自动同步功能](#自动同步功能)
    - [windows](#windows-1)
    - [ubuntu](#ubuntu)
    - [Mac](#mac-1)
  - [外网访问](#外网访问)
    - [网页端](#网页端)
    - [电脑客户端](#电脑客户端)
    - [手机](#手机)
  - [文件结构](#文件结构)
  - [使用终端 ssh 登陆](#使用终端-ssh-登陆)



<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
<!-- Added by: zhangzhiyu, at: 2022年11月24日 星期四 22时23分15秒 CST -->


Data: 2022年11月9日下午7:39:38

## 说明

现实验室购入一台NAS，用于数据存储和备份。大家可找我创建账户和密码（建议这样）或如果嫌麻烦可使用公共账户来登陆。希望大家可以共享自己的程序和数据，还有组会的PPT，各种材料等。（注：程序和数据写好Readme文件）

~~公共账户：CSIM_LAB 密码：Csim523245~~
<!-- Added by: zhangzhiyu, at: 2023.3.24 -->

## 使用

### windows

- 首先需要连接网络：inter1209 或 inter1209_5G

- 在文件夹中输入 `\\192.168.3.26`

  ![1](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092019100.png)

- 输入账户和密码

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092021022.png)

- 进入NAS文件夹

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092022010.png)

- 可以将`csim_lab`设为快速访问，便于进入该文件夹

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092023199.png)

- 在`csim_lab`下创建自己的文件夹

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092024072.png)

- 现在就可以自由上传和备份文件了！！！

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092025268.png)

### linux (ubuntu)

- 首先需要连接网络：inter1209 或 inter1209_5G

- 打开文件夹，找到其他位置，并点击`DS920(文件共享)`

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092038610.png)

- 输入用户名和密码，点击连接

  ![截图 2022-11-09 20-41-18](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092048190.png)

- 进入NAS文件夹

  ![截图 2022-11-09 20-42-33](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092048077.png)

- 可拖动文件进入文件夹

  ![截图 2022-11-09 20-45-59](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092048590.png)

- 在终端中打开

  ![截图 2022-11-09 20-54-56](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092055009.png)

### Mac

- 首先需要连接网络：inter1209 或 inter1209_5G

- 打开文件夹，找到位置，并点击`DS920`

  ![image-20221109下午85939724](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092059756.png)

- 点击连接身份

  ![image-20221109下午90054209](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092100236.png)

- 进入NAS目录

  ![image-20221109下午90113838](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092101866.png)

- 进入自己文件夹

  ![image-20221109下午90359857](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092103892.png)

- 终端如下

 ![image-20221109下午90540647](https://gitee.com/erbiaoger/PicGo/raw/master/img202211092105673.png)

Data: 2022年11月10日上午7:54:16

## 自动同步功能

- mac, ubuntu, windows 都需下载`Synology Drive Client` 网址：`https://www.synology.cn/zh-cn/support/download/DS920+?version=7.1#utilities`

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100755159.png)

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100757227.png)

### windows 

- 可仿照`ubuntu`和`Mac`

要是有人上传操作步骤, 就更好了

### ubuntu

- 安装`Synology Drive Client`

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100813172.png)

- 打开

  ![截图 2022-11-10 08-16-13](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100821430.png)

  ![截图 2022-11-10 08-16-54](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100822172.png)

- 登陆 Synology NAS 处还可填 `192.168.3.26` 域名应该

  ![截图 2022-11-10 08-17-32](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100822657.png)

- 选择同步或备份任务

  ![截图 2022-11-10 08-17-41](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100822788.png)

  ![截图 2022-11-10 08-17-59](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100823618.png)

- 设置同步文件夹，NAS端和PC端

  ![截图 2022-11-10 08-19-02](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100823793.png)

- 选择备份模式

  ![截图 2022-11-10 08-19-11](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100823819.png)

- 搞定

  ![截图 2022-11-10 08-19-31](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100823807.png)

### Mac

- 双击运行

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100759898.png)

- 一路下一步

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100802543.png)

- 点击`同步任务`或`备份任务`, 点击创建 (由于我已经登陆过，步骤可能稍有不同)

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100807306.png)

- 设置同步文件夹，NAS端和PC端

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100810352.png)


## 外网访问

### 网页端

在网页浏览器上，输入以下链接：

	http://QuickConnect.cn/CSIM-LAB

![](https://gitee.com/erbiaoger/PicGo/raw/master/image/202211242147906.png)

### 电脑客户端

- mac, ubuntu, windows 都需下载`Synology Drive Client` 网址：`https://www.synology.cn/zh-cn/support/download/DS920+?version=7.1#utilities`

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100755159.png)

  ![](https://gitee.com/erbiaoger/PicGo/raw/master/img202211100757227.png)

- 登陆 (注：`Synology NAS` 处需填 `CSIM-LAB`， 其余与自动备份功能一样)

![](https://gitee.com/erbiaoger/PicGo/raw/master/image/202211242125062.png)



- 备份完成后可点击下图小球

![](https://gitee.com/erbiaoger/PicGo/raw/master/image/202211242149310.png)

- 可跳转到如下界面

  ![image-20221124215038593](/Users/zhangzhiyu/Library/Application Support/typora-user-images/image-20221124215038593.png)

### 手机

![Screenshot_20221124-215244_Google Play Store](/Users/zhangzhiyu/Downloads/Screenshot_20221124-215244_Google Play Store.jpg)



![](https://gitee.com/erbiaoger/PicGo/raw/master/image/202211242157720.jpg)

- 登陆与其他类似，使用 `CSIM-LAB` 域名登陆

  

## 文件结构

![](https://gitee.com/erbiaoger/PicGo/raw/master/image/202211242221923.png)

## 使用终端 ssh 登陆

![image-20230615090331932](https://raw.githubusercontent.com/erbiaoger/PicGo/main/20230608202306150903002.png)

```shell
ssh Nas
cd /volume1/ZhangZhiyu
```

![](https://raw.githubusercontent.com/erbiaoger/PicGo/main/20230608202306150857368.png)

## Synology Photos

![截屏2023-07-12 15.39.50](https://raw.githubusercontent.com/erbiaoger/PicGo/main/20230608202307121539668.png)
