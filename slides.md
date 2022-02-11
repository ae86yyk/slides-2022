---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false

layout: intro
---

# 平台研发-汇报总结


<div class="absolute bottom-10">
  <span class="font-700">
    余怡恺
  </span>
</div>

---

# 做了什么?

2021年的工作成果

- **GPS坐标转换到模型坐标** - gps定位功能都会用到
- **d3m格式支持** - 李佳模型格式的兼容
- **3.0版本** - 多维度支持配置，灵活快速
- **天气** - 雪天、雨天、大小控制
- **灯光、火焰、喷水** - 报警、喷淋
- **构件切分** - 货垛、管道
- **纹理动画** - 皮带动画

---

# 3.0版本功能

- **界面改版** - 网站的样式重新设计
- **数据源接入** - 后续gps定位功能都会用到
- **目录树** - 目录树配置及目录树模板
- **属性面板** - 属性设置，数据来源，右键菜单，模型颜色，关联标识，卡片，自动的属性窗口显示
- **自定义窗体** - 支持在线vue代码编写界面，并能调用SDK的功能
- **自定义事件** - 支持API、打开新页面、视口、视频
- **工具条** - 内置功能、弹出自定义窗体、自定义事件
- **孪生协议** - 通过协议对场景的模型、目录树进行操作，提高扩展性
- **业务模块** - 目录树、工具条、视口、窗口的组合，支持同一场景的不同业务
- **二维场景功能加强** - 增加对孪生协议中模型编辑、加载的支持

---

# Demo

- **数据中心** - 后续gps定位功能都会用到
- **地铁** - 后续gps定位功能都会用到
- **金苑大厦** - 后续gps定位功能都会用到

---

# GIS

将3.0的配置功能融合进入GIS和MAP 

- **图层设置**
- **模型布置**
- **飞行漫游，路径漫游**
- **电子围栏**
- **视角**
- **3D标注**
- **地物检索**

---

# GIS+BIM（3.5）

将BIM场景放入GIS中，并且一些数据互通

- **路径漫游**
- **3D标注**
- **视角**
- **属性**

---
layout: section
---

# 2022年平台开发
超级引擎及FM基础平台研发

---

# V3.6（BIM+GIS）

- **完善BIM模型融入GIS场景**
- **BIM炫酷效果**
- **GIS SDK功能扩充**


3月份

---

# V3.7（SaaS）

- **SaaS开发场景整合**
<br>-场景 (bim gis3d gis2d)
<br>-模型（不能动） 
<br>-设备（抽象类型：如人、传感器、摄像头） 
<br>-构件（动态变化模型+添加） 

- **对接李佳模型转换服务，支持格式**
- **gis场景简单配合**


6月份

---

# V3.8（数据贯通）
- **从李佳转化后的json形成**
<br>-模型构件层级(树)
<br>-业务对象
<br>-业务属性(md5)
<br>-轻量化数据(md5)
<br>-存入数据库，及能够检索
- **模型版本管理**
- **模型版本比较**

8月份
---

# V3.9（施工方案）
- 集成李佳Revit进度wbs节点-人、机械、工期
- 基于模型创建施工方案，上传施工规划成果，播放

10月份

---
layout: fact
---
# UE 云渲染
前端界面 + UNREAL ENGINE

---
layout: statement
---

# 通用运维平台BIMFM设计及开发


---
layout: statement
---
# **开发手册**
# **河图AR定位**
# **轴网接口**
# **GISLOD实例研究**
# 其他项目中的技术开发研究


---
layout: statement
---
# 谢谢
