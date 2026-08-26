<div align="center">
  <img src="assets/banner.jpg" alt="码上座舱 · 车载 Android 中间件" width="100%" />
</div>

<br/>

<div align="center">

# Jason

**车载 Android 中间件** · Vehicle HAL · CarService · 车辆属性

在智能座舱里写代码。源码对照 AOSP 14，Demo 会标明 Mock 还是真接口。

<br/>

[博客](https://jason5200.github.io) · 
[中间件地图](https://jason5200.github.io/#/articles/00-overview/middleware.md) · 
[AAOS-Guide](https://github.com/jason5200/AAOS-Guide) · 
[邮箱](mailto:rdszdl@163.com)

<img src="assets/divider.svg" alt="" width="420" />

</div>

## 中间件怎么读

```
App  →  android.car  →  com.android.car  →  Vehicle HAL  →  总线 / ECU
```

1. [全景：AAOS 是什么](https://jason5200.github.io/#/articles/00-overview/aaos-intro.md)
2. [中间件地图](https://jason5200.github.io/#/articles/00-overview/middleware.md) ← 建议从这里进
3. [CarPropertyManager](https://jason5200.github.io/#/articles/carservice-api/carproperty-manager.md) · [Vehicle HAL](https://jason5200.github.io/#/articles/permission/vehicle-hal.md)
4. 动手：[Car-Launcher-Demo](https://github.com/jason5200/Car-Launcher-Demo)（需要 AAOS 模拟器）

对照标签：`android-14.0.0_r67`

## 开源

<table>
<tr>
<td width="50%" valign="top">

**主线**

- [AAOS-Guide](https://github.com/jason5200/AAOS-Guide)  
  车载中间件学习路线
- [码上座舱](https://jason5200.github.io)  
  文章站 · Docsify

</td>
<td width="50%" valign="top">

**配套**

- [Framework-Source-Note](https://github.com/jason5200/Framework-Source-Note)  
  Binder / Handler / AMS
- [Car-Launcher-Demo](https://github.com/jason5200/Car-Launcher-Demo)  
  车机 Home 骨架
- [AI-Android-Demo](https://github.com/jason5200/AI-Android-Demo)  
  对话 UI · 可接 OpenAI 兼容 API

</td>
</tr>
</table>

## 最近在写

- [车载中间件地图](https://jason5200.github.io/#/articles/00-overview/middleware.md)
- [CarPropertyManager](https://jason5200.github.io/#/articles/carservice-api/carproperty-manager.md)
- [Vehicle HAL（AIDL）](https://jason5200.github.io/#/articles/permission/vehicle-hal.md)
- [CarService 架构](https://jason5200.github.io/#/articles/car-service/carservice-architecture.md)
- [电源：熄火准备](https://jason5200.github.io/#/articles/audio/car-power.md)

[全部文章 →](https://jason5200.github.io)

<img src="assets/divider.svg" alt="" width="420" />

<div align="center">

`AAOS` `Vehicle HAL` `CarService` `AOSP 14` `Kotlin` `Binder`

[jason5200](https://github.com/jason5200) · [rdszdl@163.com](mailto:rdszdl@163.com)

</div>
