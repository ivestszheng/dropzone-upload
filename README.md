# Dropzone 文件上传工具

## 在线访问

https://ivestszheng.github.io/dropzone-upload/

## 使用说明

### 介绍

基于 [Dropzone.js](https://docs.dropzone.dev/) 实现的上传工具 demo，支持自定义上传地址。

### 上传地址设置

1. 在"上传地址设置"区域输入您的上传服务器地址
2. 点击"保存"按钮保存配置（支持回车键保存）
3. 点击"重置"按钮恢复默认地址
4. **URL 查询参数支持**：可通过 URL 参数直接设置上传地址，例如：
   ```
   https://ivestszheng.github.io/dropzone-upload?uploadUrl=https://your-server.com/upload
   ```
   系统会优先使用 URL 参数中的地址，如果没有参数则使用本地保存的配置，最后使用默认地址

### 默认配置

默认使用 `https://httpbin.org/post` 作为测试上传地址。您可以根据需要修改为您的实际服务器地址。
