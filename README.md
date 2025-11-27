# 通用文件处理工具库

这是一个功能丰富的通用文件处理工具库，旨在提供高效的文件操作、多媒体处理和算法工具。该库集成了多种常用的文件处理功能，为开发者提供便捷的工具集合。

## 功能特性

### 音频处理 (Audio)
- 音频文件格式转换
- 音频信息提取
- 音频剪辑与合并
- 音频质量调整

### 文件操作 (File)
- 文件读写操作
- 文件类型检测
- 文件编码转换
- 文件权限管理
- 文件路径处理

### 文件夹操作 (Folder)
- 文件夹遍历与搜索
- 批量文件操作
- 目录结构分析
- 文件夹大小计算

### 哈希算法 (Hash)
- MD5 哈希计算
- SHA-1 哈希计算
- SHA-256 哈希计算
- 自定义哈希算法支持

### 图像处理 (Image)
- 图片格式转换
- 图像尺寸调整
- 图像质量压缩
- 图像信息提取
- 图像裁剪与旋转

### 视频处理 (Video)
- 视频格式转换
- 视频剪辑与合并
- 视频信息提取
- 视频压缩与转码

### 排序算法 (Sort)
- 快速排序算法
- 归并排序算法
- 冒泡排序算法
- 堆排序算法
- 自定义排序比较器

## 安装使用

```bash
# 安装依赖
npm install your-file-utils-library

# 或使用 yarn
yarn add your-file-utils-library
```

## 使用示例

```javascript
// 导入工具库
const FileUtils = require('your-file-utils-library');

// 文件哈希计算示例
const hash = FileUtils.hash.calculate('path/to/file', 'sha256');
console.log('File hash:', hash);

// 图像处理示例
FileUtils.image.resize('input.jpg', 'output.jpg', { width: 800, height: 600 });

// 文件夹遍历示例
FileUtils.folder.traverse('path/to/directory', (file) => {
  console.log('Found file:', file.path);
});
```

## API 文档

详细 API 文档请参见各模块的独立文档。

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进这个项目。

## 许可证

本项目采用 MIT 许可证。