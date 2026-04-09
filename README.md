# Skills Repository

> 收集和整理好用的 AI Agent Skills，提升开发效率

---

## 📁 项目结构

```
skills_repository/
├── skills/                 # 自定义 Skills（自己编写）
│   └── generate-tech-proposal/    # 技术方案生成器
├── third-party/            # 第三方 Skills（GitHub 开源）
│   └── README.md           # 第三方 Skills 列表及使用说明
└── README.md               # 本文件
```

---

## 🛠️ 已收录 Skills

### 自定义 Skills

| Skill 名称 | 路径 | 说明 |
|-----------|------|------|
| **generate-tech-proposal** | [skills/generate-tech-proposal/](skills/generate-tech-proposal/) | 根据图片、文字描述或蓝湖链接生成项目技术方案 |

### 第三方 Skills

详见 [third-party/README.md](third-party/README.md)

---

## 🌐 主流 Skills 资源网站

### MCP Servers 聚合

| 网站 | 地址 | 说明 |
|------|------|------|
| **Awesome MCP Servers** | [github.com/punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | 最全面的 MCP 服务器精选列表 |
| **MCP 官方文档** | [modelcontextprotocol.io](https://modelcontextprotocol.io/) | Model Context Protocol 官方文档 |
| **MCP Servers** | [mcpservers.org](https://mcpservers.org/) | MCP 服务器目录 |

### 官方/知名 Skills

| Skill | 来源 | 说明 |
|-------|------|------|
| **Playwright MCP** | Microsoft | 浏览器自动化 |
| **Framelink Figma MCP** | Framelink | Figma 设计稿集成 |
| **GitHub MCP** | GitHub | GitHub 操作集成 |

---

## 📝 常用命令

### MCP 服务器安装

```bash
# 安装 MCP 服务器（以 Playwright 为例）
npm install -g @playwright/mcp
```

---

## 🚀 如何添加新 Skill

### 添加自定义 Skill

1. 在 `skills/` 目录下创建新文件夹
2. 编写 `SKILL.md` 文件，定义 Skill 的功能和使用方式
3. 参考现有 Skill 的格式编写

### 添加第三方 Skill

1. 编辑 [third-party/README.md](third-party/README.md)
2. 在对应分类的表格中添加新 Skill 信息
3. 包含：名称、GitHub 地址、安装命令、说明

---

## 📌 使用建议

1. **分类管理**：自定义 Skills 放 `skills/`，第三方 Skills 记录到 `third-party/`
2. **文档完善**：每个 Skill 都要有清晰的说明文档
3. **定期更新**：关注第三方 Skills 的更新，及时同步
4. **按需安装**：只安装实际需要的 Skills，保持环境整洁

---

## 📄 License

本仓库仅做 Skills 收集和整理，各 Skills 遵循其原作者的许可证。
