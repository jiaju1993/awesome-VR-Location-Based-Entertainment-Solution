[English](README.md),
[中文](README.zh-CN.md)

# 主流 大空间多人 VR 解决方案
Location Based Entertainment / Shared Space / Free Roam / Shared Spatial Anchors / multiplayer

### 经历了昂贵的第三方大规模定位器识别年代，大空间多人VR也进入了新的时代，本文重点就当下主流VR一体机，介绍主要大空间多人VR解决方案

基于所谓的隐私问题，主流VR设备商均直接或间接禁止了第三方app读取机身摄像头的功能（虽然仍可使用Passthrough功能，但视频内容无法获取），由此第三方应用无法通过摄像头识别进而完成空间定位，不过VR设备商仍通过发布企业版或付费SDK，保留了开发者使用该功能的可能性

## 目录
<!-- MarkdownTOC depth=4 -->

- [设备商方案 (官方解决方案)](#VR)
- [第三方硬件解决方案](#TPH)
- [知名案例](#TPS)
- [其他](#Others)

  <a name="VR"></a>

## 设备商方案 (官方解决方案)

- HTC VIVE [Focus 3](https://business.vive.com/mea-en/solutions/vive-location-based-software-suite)

  | SDK | README |
  | ------ | ------ |
  | Unity | - |
  | Unreal | - |

  `支持空间尺寸: 33m*30m = 1000m^2`

- Pico [4 Enterprise / NEO 3 Enterprise](https://business.picoxr.com/cn/doc/Enterprise-Settings-LBE-v1.2) ：Currently only Chinese Version

  | SDK | README |
  | ------ | ------ |
  | Unity | [Advanced Guardian Example](https://github.com/picoxr/Advanced-Guardian-Example/blob/main/README.md) |
  | Unreal | [by blueprints](https://pdocor.pico-interactive.com/reference/unreal/xr/12832/enable-large-space/) |

  `支持空间尺寸: 20m*20m = 400m^2`

- Meta Quest [Pro / 2](https://developer.oculus.com/blog/build-local-multiplayer-experiences-shared-spatial-anchors)：Currently no unified portal

  | SDK | README |
  | ------ | ------ |
  | Unity | [Shared Spatial Anchors](https://github.com/oculus-samples/Unity-SharedSpatialAnchors/blob/main/README.md) |
  | Unreal | [Shared Spaces](https://github.com/oculus-samples/Unreal-SharedSpaces/blob/main-5.x/README.md) |

  `使用锚点分享，不是marker识别技术，精度取决于离公共锚点距离`

- Pimax Crystal QLED [TBD]

- pc-powered HP Reverb [G2 / G2 Omnicept Edition](https://learn.microsoft.com/en-us/windows/mixed-reality/enthusiast-guide/enterprise-lbe-faq) 

  > Where should I begin with learning how to build immersive experiences for use with the Windows Mixed Reality platform or other virtual reality devices?
Begin your native development journey by getting acquainted with [OpenXR](https://learn.microsoft.com/en-us/windows/mixed-reality/develop/native/openxr), which can be used to develop unique immersive experiences with on any Windows Mixed Reality immersive VR headset. OpenXR is an open royalty-free API standard from Khronos, providing engines with native access to various devices across the [mixed reality spectrum](https://learn.microsoft.com/en-us/windows/mixed-reality/discover/mixed-reality).
  > 

<a name="TPH"></a>

## 第三方软件/硬件解决方案

- 外置摄像头: [antilatency](https://antilatency.com/)
- 第三方点云比对: [EasyAR MEGA](https://www.bilibili.com/video/BV1Zg4y1c7CS/?spm_id_from=333.999.0.0&vd_source=ba8f33ad83a9dcb49b3b3813840bed1d)

<a name="TPS"></a>

## 知名案例

- 游戏: [zerolatencyvr](https://zerolatencyvr.com/games/) 
- 展览: [horizon kheops](https://horizonkheops.com/en/home/)、[The Infinite](https://theinfiniteexperience.world/en)

<a name="Others"></a>

## 值得一提的其他
- VR PC: [VR GO](https://www.zotac.com/us/product/mini_pcs/vr-go-40-windows-11-pro)
- VR Compare：[vrcompare](https://vr-compare.com/compare?h1=-MpSqv-rB&h2=QCggQgEXT&h3=vEajWefj-&h4=2WZ0E44Hw)

## ✨总结✨
- 想要获得摄像头数据需要额外付费
- 所有方案基本上也是各家在做各家，无法通用
- 即使使用一体机，想要实现大尺度复杂模型空间游走，也可能需要使用串流

## 关于我们
- 北京嘉境天禾科技有限责任公司 [ixdera.com](https://www.ixdera.com)
