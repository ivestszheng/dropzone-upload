# Dropzone 文件上传工具

一个基于 Dropzone.js 实现的现代化文件上传工具，支持自定义上传地址、请求 Headers 配置等功能。

## 在线访问

🌐 [https://ivestszheng.github.io/dropzone-upload/](https://ivestszheng.github.io/dropzone-upload/)

## 功能特性

- 📤 **拖放上传**: 支持将文件拖放到上传区域进行上传
- 🔗 **自定义上传地址**: 可自由配置上传服务器地址
- 📝 **请求 Headers 配置**: 支持自定义 HTTP 请求头
- 💾 **本地存储**: 配置自动保存到 localStorage
- 🔧 **URL 参数支持**: 可通过 URL 参数直接设置上传地址和 Headers
- 📱 **响应式设计**: 完美适配桌面端和移动端
- 🎨 **现代化 UI**: 简洁美观的界面设计

## 使用说明

### 上传地址设置

1. 在"上传地址设置"区域输入您的上传服务器地址
2. 点击"保存"按钮保存配置（支持回车键保存）
3. 点击"重置"按钮恢复默认地址

### 请求 Headers 配置

1. 点击"请求配置"区域展开配置面板
2. 在 Headers 表格中添加或修改请求头参数
3. 配置会自动保存并立即生效

### URL 参数支持

#### 设置上传地址
```
https://ivestszheng.github.io/dropzone-upload?uploadUrl=https://your-server.com/upload
```

#### 设置 Headers
```
https://ivestszheng.github.io/dropzone-upload?headers=[{"key":"Authorization","value":"Bearer token"}]
```

### 优先级说明

系统按以下优先级使用配置：
1. URL 查询参数（最高优先级）
2. 本地存储的配置
3. 默认配置

## 默认配置

- **默认上传地址**: `https://httpbin.org/post`
- **默认 Headers**: 无

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- [Dropzone.js](https://docs.dropzone.dev/)

## 开发

直接打开 `index.html` 即可运行，无需额外依赖安装。

## 许可证

MIT License - 详见 LICENSE 文件

## 作者

ivestszheng (无声2017)