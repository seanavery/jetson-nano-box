# Computer Vision Starter Pack

> DIY Nvidia Computer Vision Camera

## Overview

I have recently been toying around with computer vision more. I need access to a low cost Nvidia GPU and camera sensor to bootstrap all the crazy ideas i have. Sure you can started programming inside a Google Colab notebook, but I am more interested in embedded systems and applied machine learning. 

The goal is to start programming real-time camera pipelines, converting state of the art models into TensorRT, and using Nvidia optimized computer vision libraries for things like optical flow and slam! My go to strategy in hardware is always to start small. I want to fully utilize the computing resources before I level up.

![jetson nano](jetson_nano.jpg)

So, I decided to build out a standard Jetson Nano hardware setup. This guide will go over how to put it all together.



## Materials

0. Nvidia Jetson Nano Developer Kit

1. Sony IMX219 Wide Angle CSI Camera Sensor

2. Samsung (MB-ME128GA/AM) 128GB 100MB/s (U3) MicroSDXC EVO Select Memory Card

3. Adafruit 5V 10A Switching Power Supply

4. Noctua NF-A4x20 5V PWM, Premium Quiet Fan, 4-Pin, 5V Version

5. Geekworm NVIDIA Jetson Nano Metal Case/Enclosure with Power & Reset Control Switch

## Tutorial

This is a pretty standard build for Nvidia newcomers like myself. I followed resources available from the developer nvidia documentation and Jetson Hacks helpful vidoes. Here are some links I found helpful:


### 0. Flash and bootup Jetson Nano


Before we get started, make sure you have ordered Jetson Nano Developer Kit, and Samsung Micro SD card. Hopefully you have also have a spare monitor with HDMI port laying around. 

The first step is to flash your SD card with Nvidia Jetpack OS, which is essentially Ubuntu with some extra software and Nvida SDKs that come pre-installed. Plug in the MicroSD card into your day to day computer for the initial flashing.

Follow the [instructions](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write) from the Jetson Nano Get Started guid to write the image to the SD card. It contains references for mac, linux, and windows.

### 1. Internet Connection and SSH



### 3. Attach Sony IMX219 Camera Sensor

### 4. Fan and Power Supply Setup

### 5. Enclosure and Camera Mount
