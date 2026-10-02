# care-platform

居家照护、康养支持与家政服务的静态前端原型，包含「服务需求方」与「服务人员」两种角色。使用 HTML、CSS 和原生 JavaScript，不需要安装依赖或启动服务器。

## 打开方式

下载并完整解压仓库，使用新版 Microsoft Edge 或 Google Chrome 双击打开 `index.html`。请保持 `data` 目录与 `index.html` 在同一层级；地图、行政区划和照片均通过项目内相对路径加载，支持离线浏览。

```text
index.html
data/
  regions.js
  china.js
  images/
```

## 演示范围

支持角色切换、服务与地点筛选、省市区联动、省级地图选择、人员资料、模拟预约、发布需求、申请工作、资料草稿和模拟消息。

所有人员姓名、资质、评价、工作经历、服务需求与地址输入均为演示用途，不代表真实服务人员或实际服务订单。人物照片为公开图库占位图片，与虚构姓名、资质和经历无关。没有真实登录、支付、消息发送或后端数据库；输入内容仅保留在当前页面会话，刷新后重置，不上传到服务器。

## 第三方数据与图片

- 大陆行政区划：[kk-418/cn-division](https://github.com/kk-418/cn-division)，使用其带编码的省市区数据；该项目采用 MIT 许可。数据快照日期：2026-10-02。
- 全国省级 GeoJSON、港澳分区：[阿里云 DataV.GeoAtlas](https://datav.aliyun.com/portal/school/atlas/area_selector)。数据来源说明参考 [zhChuXiao/ChinaGeoJson](https://github.com/zhChuXiao/ChinaGeoJson)。地图保留来源边界，界面仅进行投影与高亮。
- 台湾省：来源数据仅提供省级信息，未自行编造下级市县数据。
- 照片：[Unsplash](https://unsplash.com/)，原图标识保留在 `data/images` 文件名中，仅作为人物与家庭场景占位；图片使用遵循 [Unsplash License](https://unsplash.com/license)。

第三方数据和照片的权利归其原权利人，仓库不为这些资源另行授予许可。来源链接仅用于说明，页面运行不依赖在线 CDN 或图片服务。

此仓库不包含真实用户资料或凭据。请勿将真实个人资料、详细地址、账号密钥或其他私密配置提交到公开仓库。
