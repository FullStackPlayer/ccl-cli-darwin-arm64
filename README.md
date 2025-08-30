# ccl-cli-darwin-arm64

适用于 darwin-arm64 架构（Apple Silicon Mac）的 ccl-cli 包。

## 描述

此软件包为 macOS 上的 ARM64 架构（Apple Silicon 芯片）专门编译的 ccl 命令行工具。

## 安装

### 使用 npm 安装（推荐）

```bash
npm install -g ccl-cli-darwin-arm64
```

安装过程中，软件包将自动：
1. 从包含的 zip 文件中解压 ccl 二进制文件
2. 将其放置在适当的 bin 目录中
3. 设置所需的执行权限

## 使用方法

安装完成后，您可以使用 `ccl-darwin-arm64` 命令：

```bash
# 显示版本
ccl-darwin-arm64 --version

# 显示帮助信息
ccl-darwin-arm64 --help
```

注意：命令名称是 `ccl-darwin-arm64`，而不是 `ccl`，这样可以明确表示此二进制文件是为特定架构编译的。如果你想要直接使用 `ccl` 命令，请全局安装 `ccl-cli` 包。

## 架构

此软件包专门为以下架构构建：
- 操作系统：darwin（macOS）
- CPU：arm64（Apple Silicon）

它无法在其他架构或操作系统上工作。

## 许可证

MIT