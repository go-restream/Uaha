# 快速入门指南

本指南将帮助你安装 Uaha 并完成首次配置。

## 系统要求

### 必需项

- **Go** 1.25 或更高版本
- **Node.js** 18 或更高版本（用于前端构建）
- **Task** 命令运行器（`go install github.com/go-task/task/v3/cmd/task@latest`）

## 安装方式

### 方式一：从 GitHub Release 下载（推荐）

1. 访问 [Uaha Releases](https://github.com/go-restream/Uaha/releases)
2. 下载对应平台的安装包：
   - macOS: `.dmg` 文件
   - Windows: `.exe` 安装程序 // TODO: 添加 Windows 安装程序
   - Linux: `.AppImage` 文件 // TODO: 添加 Linux 安装程序
3. 运行安装程序并完成安装

### 方式二：从源码构建

```bash
# 1. 克隆仓库
git clone https://github.com/go-restream/Uaha.git
cd Uaha

# 2. 构建应用
wails3 build
wails3 package GOOS=darwin

# 4. 查看构建产物
ls -la bin/
```

## 首次运行配置

### 1. 启动应用

首次启动 Uaha 后，你将看到主界面，包含以下功能区域：

- **模型列表** - 浏览和管理 AI 模型
- **API 服务** - 管理运行中的服务实例
- **配置** - 应用设置和首选项

### 2. 配置 Aha 引擎路径

1. 进入「配置」页面
2. 设置「Aha 可执行文件路径」
   - macOS: `/usr/local/bin/aha` 或自定义路径
   - Windows: `C:\Program Files\Aha\aha.exe`
   - Linux: `/usr/bin/aha` 或自定义路径
3. 点击「保存」应用配置

### 3. 配置模型下载目录

1. 在「配置」页面找到「模型下载目录」
2. 设置模型存储位置（默认：`~/.aha/<model_id>`）
3. 确保目录有足够的磁盘空间

### 4. 主题设置

1. 选择「亮色」或「深色」主题
2. 调整字体大小（16px 为默认值）
3. 自定义主色调（可选）

## 快速验证安装

### 验证步骤

1. **检查应用版本**
   - 进入「关于」页面
   - 确认版本为 `v0.1.0-beta` 或更高

2. **测试模型列表加载**
   - 进入「模型列表」页面
   - 确认能看到可用的模型列表

3. **验证配置保存**
   - 修改配置并保存
   - 重启应用，确认配置已持久化

4. **检查日志输出**（开发模式）
   ```bash
   task dev
   # 查看控制台是否有错误输出
   ```

### 常见安装问题

如果遇到安装问题，请查看 [常见问题文档](faq.md) 获取帮助。

## 下一步

安装完成后，你可以：

- 阅读 [用户指南](user-guide.md) 了解详细功能
- 查看 [开发指南](development.md) 了解如何贡献代码
- 访问 [GitHub Issues](https://github.com/go-restream/Uaha/issues) 报告问题
