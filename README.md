# 轻减 · 体重与饮食记录（GitHub Pages 版）

这是一个可离线使用的移动端 PWA，包含以下文件：

- `index.html`：应用入口
- `echarts.min.js`：本地图表库
- `manifest.webmanifest`：PWA 安装配置
- `sw.js`：离线缓存 Service Worker
- `icon-192.png` / `icon-512.png`：应用图标

## 发布到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 仓库，例如 `qingjian`。
2. 把本目录里的所有文件上传到该仓库根目录。
3. 打开仓库 `Settings → Pages`。
4. `Source` 选择 `Deploy from a branch`，`Branch` 选择 `main`、目录 `/ (root)`，保存。
5. 稍等片刻，页面会显示访问地址，通常是：

   `https://你的用户名.github.io/qingjian/`

## 在手机上安装

1. 用手机 Chrome 打开上面的 HTTPS 地址。
2. 点击浏览器菜单，选择「安装应用」或「添加到主屏幕」。
3. 桌面会出现“轻减”图标，点击即可像 App 一样独立运行，并支持离线使用。

## 数据说明

数据保存在当前浏览器的 `localStorage` 中，不会自动同步到其他设备。更换设备或重新安装前，请先在应用「设置」中使用「导出备份」保存数据。
