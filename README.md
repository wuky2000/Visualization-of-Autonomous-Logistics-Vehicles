# 无人物流车 · 模块化智能物流解决方案

以同一辆三维车辆为中心，展示模块化车体、集成控制、智能底盘、货物输送与灵活能源五大系统，共二十项技术。

页面提供三级连续探索、三维空间热点、技术演示、产品导览，以及车身参数和传感器视场配置；支持桌面与移动端。

## 浏览与下载

- [网站入口文件](index.html)
- [下载离线单文件 HTML](https://github.com/wuky2000/Visualization-of-Autonomous-Logistics-Vehicles/raw/refs/heads/main/downloads/logistics_vehicle_website.html)
- [下载 ZIP 压缩包](https://github.com/wuky2000/Visualization-of-Autonomous-Logistics-Vehicles/raw/refs/heads/main/downloads/logistics_vehicle_website.zip)

离线使用：下载 HTML 后用支持 WebGL 的现代浏览器打开；也可以解压 ZIP 后打开 `index.html`。页面所需的 JavaScript、样式和三维资源均已内置，无需安装依赖或联网。

## 文件说明

| 路径 | 用途 |
| --- | --- |
| `index.html` | 网站入口，也是 ZIP 包中全部内容 |
| `downloads/logistics_vehicle_website.html` | 独立离线页面，与网站入口内容一致 |
| `downloads/logistics_vehicle_website.zip` | 包含 `index.html` 的离线压缩包 |
| `.nojekyll` | 让 GitHub Pages 按静态文件提供服务 |

## 静态托管

本项目无需安装依赖或构建。已配置 `.github/workflows/pages.yml`，推送到 `main` 会部署网页和下载文件。

首次使用时，在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**，随后在 Actions 中运行 **Publish product website**。也可选择 **Deploy from a branch → main → /(root)**，直接发布仓库根目录。

实际在线地址与发布状态以 **Settings → Pages** 和 **Actions** 的结果为准。
