# Google Scholar 增强插件

一个简单但功能强大的浏览器插件，用于增强 Google Scholar 的论文访问体验。

## 功能特点

### 1. 智能论文访问按钮
根据论文的可用性，自动显示不同的访问选项：

- 当论文提供直接 PDF 下载时：
  - 显示"预览 PDF"按钮 - 在页面内直接预览论文
  - 显示"下载 PDF"按钮 - 直接下载论文

- 当论文需要通过 Sci-Hub 访问时：
  - 显示"通过 Sci-Hub 访问"按钮 - 智能跳转到 Sci-Hub

### 2. 智能 Sci-Hub 链接生成
按照以下优先级自动选择最佳的访问方式：

1. DOI（数字对象识别符）- 最准确的识别方式
2. PMID（PubMed ID）- 适用于生物医学文献
3. 原始 URL - 作为后备方案

### 3. PDF 预览功能
- 内置 PDF 预览窗口
- 支持全屏查看
- 简单的关闭控制
- 无需离开当前页面即可浏览论文内容

### 4. 自动化支持
- 自动检测页面变化
- 动态添加访问按钮
- 支持 Google Scholar 的动态加载

## 技术特性

- 使用 WeakSet 防止重复处理
- 响应式设计
- 支持动态内容加载
- 轻量级实现
- 无需外部依赖

## 安装方法

1. 下载源代码
2. 在浏览器的扩展管理页面中启用开发者模式
3. 加载已解压的扩展程序
4. 选择包含插件代码的文件夹

## 使用方法

安装插件后，访问 Google Scholar：

1. 进行正常的论文搜索
2. 在每个搜索结果旁边会出现新的访问按钮
3. 根据论文的可用性，选择合适的访问方式：
   - 直接预览/下载 PDF
   - 通过 Sci-Hub 访问

## 版本发布历史

### v1.0.0 (2024-11-18)
- 🎉 首次发布
- ✨ 支持 PDF 预览和下载
- ✨ 智能 Sci-Hub 访问支持（DOI/PMID/URL）
- ✨ 内置 PDF 预览器
- 🎨 简洁的用户界面
- 📦 轻量级实现，无需外部依赖

## 注意事项

- 该插件仅用于学术研究目的
- 需要合理使用 Sci-Hub 资源
- 某些院校可能有自己的论文访问权限，请优先使用官方渠道
- PDF 预览功能需要浏览器支持内联 PDF 查看

## 隐私说明

- 插件不收集任何用户数据
- 不发送任何网络请求到第三方服务器
- 所有功能在本地运行

## 代码贡献

欢迎通过以下方式贡献：
- 提交 Bug 报告
- 提供功能建议
- 提交代码改进
- 完善文档

## 许可证

MIT License 

## 免责声明

此插件仅用于学术研究目的。用户应当遵守所在地区的相关法律法规，合理使用学术资源。开发者不对使用该插件可能带来的任何问题负责。