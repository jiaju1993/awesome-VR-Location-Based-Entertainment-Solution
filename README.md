# Awesome VR Headset Location-Based / Shared-Space / Free-Roam / Shared-Spatial-Anchors multiplayer Solution
## We mainly focus on resently top standalone VR headset, not pc-powered VR Headset (still with one mentioned below).
### For large space with multiplayer situation，VR headset should not require external base stations, and better have cameras with passthrough ability. 

Based on the so-called privacy issues, the mainstream VR Headset manufacturers do not support third-party applications to read the video stream of the camera（though users can still use Passthrough funtion to see outside）, and thus the third-party programs can not spot identification markers through on-board cameras to obtain the location of the space, but the device vendors have also retained the permission to use the external camera on the enterprise version, although this may lead to higher costs

> ✨Summary✨: You need additional pay for `Camera access permissions` from VR headsets.

> ✨Summary✨: You need additional pay for `Camera access permissions` from VR headsets.

> ✨Summary✨: You need additional pay for `Camera access permissions` from VR headsets.

（重要的事情说三遍）

# Table of Contents
<!-- MarkdownTOC depth=4 -->

- [VR headset manufacturers (Official Solutions)](#VR)
- [Third Party Hardware Solutions](#TPH)
- [Use Cases](#TPS)
- [Others](#Others)

  <a name="VR"></a>

# VR headset manufacturers (Official Solutions)

- HTC VIVE [Focus 3](https://business.vive.com/mea-en/solutions/vive-location-based-software-suite)

| SDK | README |
| ------ | ------ |
| Unity | - |
| Unreal | - |

&emsp;&emsp;`support area: 33m*30m = 1000m^2`




- Pico [4 Enterprise / NEO 3 Enterprise](https://business.picoxr.com/cn/doc/Enterprise-Settings-LBE-v1.2) ：Currently only Chinese Version

| SDK | README |
| ------ | ------ |
| Unity | [Advanced Guardian Example](https://github.com/picoxr/Advanced-Guardian-Example/blob/main/README.md) |
| Unreal | [by blueprints](https://pdocor.pico-interactive.com/reference/unreal/xr/12832/enable-large-space/) |

&emsp;&emsp;`support area: 20m*20m = 400m^2`





- Meta Quest [Pro / 2](https://developer.oculus.com/blog/build-local-multiplayer-experiences-shared-spatial-anchors)：Currently no unified portal

| SDK | README |
| ------ | ------ |
| Unity | [Shared Spatial Anchors](https://github.com/oculus-samples/Unity-SharedSpatialAnchors/blob/main/README.md) |
| Unreal | [Shared Spaces](https://github.com/oculus-samples/Unreal-SharedSpaces/blob/main-5.x/README.md) |

&emsp;&emsp;`use anchors point clouds sharing, not marker-based`


- Pimax Crystal QLED [TBD]
  
- pc-powered HP Reverb [G2 / G2 Omnicept Edition](https://learn.microsoft.com/en-us/windows/mixed-reality/enthusiast-guide/enterprise-lbe-faq) 

> Where should I begin with learning how to build immersive experiences for use with the Windows Mixed Reality platform or other virtual reality devices?
Begin your native development journey by getting acquainted with [OpenXR](https://learn.microsoft.com/en-us/windows/mixed-reality/develop/native/openxr), which can be used to develop unique immersive experiences with on any Windows Mixed Reality immersive VR headset. OpenXR is an open royalty-free API standard from Khronos, providing engines with native access to various devices across the [mixed reality spectrum](https://learn.microsoft.com/en-us/windows/mixed-reality/discover/mixed-reality).


<a name="TPH"></a>

# Third Party Hardware / Software Solutions

- External camera: [antilatency](https://antilatency.com/)
- External cloud map: [EasyAR MEGA](https://www.bilibili.com/video/BV1Zg4y1c7CS/?spm_id_from=333.999.0.0&vd_source=ba8f33ad83a9dcb49b3b3813840bed1d)

<a name="TPS"></a>

# Use Cases

- Game: [zerolatencyvr](https://zerolatencyvr.com/games/) 
- Exhibition: [horizon kheops](https://horizonkheops.com/en/home/)、[The Infinite](https://theinfiniteexperience.world/en)


<a name="Others"></a>

# Others worth mentioning
- VR PC: [VR GO](https://www.zotac.com/us/product/mini_pcs/vr-go-40-windows-11-pro)
