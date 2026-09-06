# Oss-Blog

基于 Ghost 开源博客系统二次开发的个人博客。

## 技术栈

- **Ghost** 6.62.0
- **Node.js** 22.23.2
- **SQLite**（开发环境）

## 快速开始

### 环境要求

- Node.js 22 LTS
- Ghost CLI 1.32.3

### 安装与运行

```bash
cd runtime
ghost start
```

访问 http://localhost:2368 查看前台，http://localhost:2368/ghost 管理后台。

### 停止

```bash
cd runtime
ghost stop
```

## 项目结构

```
oss-blog/
├── docs/          # 文档（基线、架构图等）
├── theme/         # 自定义主题源码
├── tests/         # 测试记录
├── runtime/       # Ghost 运行实例（.gitignore 排除运行数据）
└── README.md
```

## 上游项目

- [TryGhost/Ghost](https://github.com/TryGhost/Ghost) (MIT License) - 固定版本 6.62.0

## 二次开发内容

（待补充）

## 许可证

（待补充）