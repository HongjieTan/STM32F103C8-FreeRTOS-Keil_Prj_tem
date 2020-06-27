# STM32F103C8-FreeRTOS-Keil

[![STM10C8-keil](https://img.shields.io/badge/ST10C8-Keil-brightgreen)](https://github.com/HongjieTan/STM32F103C8-FreeRTOS-Keil_Prj_tem)


## 内容列表

- [背景](#背景)
- [安装](#安装)
    - [方法一](#方法一)
    - [方法二](#方法二)
- [使用说明](#使用说明)
- [维护者](#维护者)
- [如何贡献](#如何贡献)

## 背景

因为本人在面试嵌入式软件工程师实习生，被HR提醒自己在RTOS方面的不足，故痛定思过开始学习RTOS中的开源代表FreeRTOS，但在刚入手学习的时候发现无法找到一个
一个可以在STM32F103C8+keil的环境下无报错编译的模板（甚至就连FreeRTOS的demo中的STM32F10一样不行），只好将网上找的各种代码进行整合和修订，终于完善了
一个不会报错的模板，所以将其开源方便每一位想要使用STM32F103C8+keil学习FreeRTOS的同学门。


## 安装

### 方法一

方法一使用 [git](https://git-scm.com/) 来clone项目，请确保你本地安装了它们。

```sh
$ cd [mydir]
$ git clone https://github.com/HongjieTan/STM32F103C8-FreeRTOS-Keil_Prj_tem
```
### 方法二

方法二直接download本项目的zip包，下载完后解压即可。

## 使用说明

clone或下载解压后进入目录，打开Project\MyPrj.uvprojx进入keil，编译项目后会在Project\Objects下生成.hex文件以用于烧录。

## 维护者

[@HongjieTan](https://github.com/HongjieTan)。

## 如何贡献

因为本人也是一名初学者难免会有疏漏，因此非常欢迎大家的指正！[提一个 Issue](https://github.com/HongjieTan/STM32F103C8-FreeRTOS-Keil_Prj_tem/issues) 或者提交一个 [Pull Request](https://github.com/HongjieTan/STM32F103C8-FreeRTOS-Keil_Prj_tem/pulls)。
