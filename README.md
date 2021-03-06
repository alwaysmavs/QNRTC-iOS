# 1 概述

QNRTC-Android/QNRTC-iOS 是七牛推出的一款适用于 Android/iOS 平台的音视频通话 SDK，提供了包括美颜、滤镜、水印、音视频通话等多种功能，提供灵活的接口，支持高度定制以及二次开发。

# 2 功能列表

| 功能列表 |
| --- |
| 实时音视频 |
| 支持内置音视频采集，带美颜、水印、闪光灯、摄像头切换、聚焦头切换、聚焦等常见功能 |
| 支持外部采集视频数据，支持的格式为：NV21 和 I420 |
| 支持外部采集音视频数据，支持的格式为：PCM，单通道，16bit 位宽 |
| 支持三方美颜、滤镜、面部特效 |
| 支持踢人功能 |
| 支持静音功能 |
| 支持帧率配置 |
| 支持视频码率的配置 |
| 支持视频尺寸配置 |
| 支持网络重连和超时的配置 |
| 支持丰富的消息回调 |
| 支持纯音频互动 |
| 支持视频的大小窗口切换 |
| 支持软硬件配置 |
| 支持视频画面的截帧 |

# 3 DEMO 体验

七牛云为了方便用户体验 QNRTC-Android/QNRTC-iOS SDK 的效果开发了『牛会议』APP，可以扫码下载体验。
![qnrt](media/15222083601797/qnrtc.png)

# 4 应用场景

## 4.1 主播连麦

- 支持主播之间互相连麦一起直播，带来比传统单向直播不一样的体验
- 自带美颜滤镜，第三方美颜贴纸、人脸识别，让直播过程更有趣
- 48KHz采样率、全频带编解码以及对音乐场景的特殊优化保证观众可以听到最优质的声音

## 4.2 视频会议

- 小范围实时音视频互动，提供多种视频连麦布局模板，更提供自定义布局方式，保证会议发言者互相之间的实时性，提升普通观众的观看体验
- 提供七牛云自有直播分发服务，可实现 HLS、RTMP、HTTP 等多种直播分发形式，支持更多人通过拉取直播流收看会议内容，适合大型的企业在线会议
- 支持动态邀人，踢人、禁音，禁视会议权限分级控制
- 客户可以利用七牛的连麦互动技术轻松做出一款类似 WebEx 的应用

## 4.3 一对一社交

- 客户可以利用七牛的连麦互动技术实现 QQ、微信、陌陌等社交应用的一对一视频互动
- 提供七牛云自有直播分发服务，可实现 HLS、RTMP、HTTP 等多种直播分发形式，画面清晰、声音清晰不卡顿不卡顿
- 自带美颜滤镜，第三方美颜贴纸、人脸识别，让社交更加有趣

## 4.4 狼人杀游戏

- 客户可以利用七牛的连麦互动技术实现 QQ、微信、陌陌等社交应用的一对一视频互动
- 提供七牛云自有直播分发服务，可实现 HLS、RTMP、HTTP 等多种直播分发形式，画面清晰、声音清晰不卡顿不卡顿
- 自带美颜滤镜，第三方美颜贴纸、人脸识别，让社交更加有趣

## 4.5 在线教育

- 自定义的连麦布局功能允许开发者按照自己的业务需求调整老师和连麦学生的显示位置
- 旁路直播功能加上网易云的直播功能，实现观众人数无上限，让更多学生享受在线教育的便利
- 搭配使用聊天室功能，文字、语音、图片、视频包括自定义消息等，更多的互动方式有效提升课堂氛围
- 服务端录制对接点播平台，支持课程录制以及在线回放，让优质资源服务更多学生

## 4.6 在线抓娃娃

- 娃娃机端，通过主板或 PC 机连接两个摄像头，采集视频数据
- 通过编码器编码，进行视频流的优化，通过实时流网络进行视频实时传输，最后到达操作端，解码、播放
- 操作端通过业务 Server 将操控指令发送给娃娃机端，通过视频流获得实时反馈
- 采用 WebSocket 技术，结合成熟稳定的直播云端，突破了 HLS 高延迟的技术限制，同时还能保持 H5 的传播便捷特性

## 4.7 客服

- 线上开展音视频对话，对客户的资信情况进行审核，为金融科技企业促成在线签约，视频开户验证， 呼叫中心
- 提供云端存储空间及海量数据的处理能力，提供的高可用的技术和高稳定的平台

# 5 FAQ

## 5.1 七牛云实时音视频云提供哪些服务

![rt](media/15222083601797/rtc.png)

- 客户端 SDK：方便客户调用终端的音视频接口，快速的让自己的应用具备音视频互动的能力。
- 服务端链路：保证音视频互动延时低，可用性高。
- 服务端配套功能：七牛将服务大量客户的经验抽象成一些具备共性的功能，以配套服务的方式提供给客户。

## 5.2 使用七牛音视频实时互动云服务和自主研发相比有什么优势

- 因为实时互动对网络的稳定性和演示要求非常苛刻，所以必须购买数据中心建设基础网络。而使用七牛云音视频实时互动的云服务，不需要投入大量资金做传输网络的基础建设，按量计费灵活方便。
- 经验丰富的音视频团队提供稳定、易用的客户端 SDK。保证了客户端应用开发的效率和可用性。
- 完整的音视频产品线，使用七牛云的实时互动云服务的同时可以无缝接入七牛其他的所有服务。例如短视频、直播、存储、大数据分析等等服务。



