![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - 面向技术团队的安全工作流自动化平台

n8n 是一个工作流自动化平台，为技术团队提供代码的灵活性与无代码的开发速度。凭借 400 多个集成、原生 AI 能力以及公平代码许可证，n8n 让你在完全掌控数据和部署的同时，构建强大的自动化工作流。

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## 核心功能

- **按需编码**：编写 JavaScript/Python，添加 npm 包，或使用可视化界面
- **AI 原生平台**：基于 LangChain，使用你自己的数据和模型构建 AI 智能体工作流
- **完全掌控**：通过公平代码许可证自托管，或使用我们的[云服务](https://app.n8n.cloud/login)
- **企业就绪**：高级权限管理、SSO 单点登录和离线部署
- **活跃社区**：400 多个集成，900 多个开箱即用的[工作流模板](https://n8n.io/workflows)

## 快速开始

使用 [npx](https://docs.n8n.io/hosting/installation/npm/) 即时体验 n8n（需要安装 [Node.js](https://nodejs.org/en/)）：

```
npx n8n
```

或使用 [Docker](https://docs.n8n.io/hosting/installation/docker/) 部署：

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

访问编辑器：http://localhost:5678

## 资源链接

- 📚 [官方文档](https://docs.n8n.io)
- 🔧 [400+ 集成](https://n8n.io/integrations)
- 💡 [示例工作流](https://n8n.io/workflows)
- 🤖 [AI 与 LangChain 指南](https://docs.n8n.io/langchain/)
- 👥 [社区论坛](https://community.n8n.io)
- 📖 [社区教程](https://community.n8n.io/c/tutorials/28)

## 项目介绍

n8n（读作 "n-eight-n"）是 "nodemation"（节点自动化）的缩写。项目名称来源于 Node.js 的 "node-" 前缀，以及 "automation"（自动化）的 "-mation" 后缀。由于完整名称较长，最终简化为 "n8n"。

n8n 由 Jan Oberhauser 于 2019 年创立，目前已成为最受欢迎的开源工作流自动化工具之一。

### 主要特点

1. **可视化工作流设计器**：通过拖拽方式连接不同的服务和操作，无需深入了解底层 API
2. **强大的集成能力**：支持 400 多个应用程序和服务，涵盖 CRM、数据库、通信工具等各类场景
3. **灵活的代码支持**：在工作流中直接编写 JavaScript 或 Python 代码，满足复杂业务需求
4. **AI 工作流**：内置 LangChain 集成，轻松构建 AI 智能体、RAG 应用和 LLM 驱动的自动化流程
5. **自托管部署**：可在自有服务器或私有云上部署，数据完全由自己掌控
6. **企业级功能**：支持 SSO、RBAC、审计日志、环境管理等企业级特性

### 适用场景

- **数据同步**：在不同系统之间自动同步数据
- **通知与告警**：根据特定条件触发邮件、Slack、钉钉等通知
- **数据处理**：自动抓取、转换和处理数据
- **AI 自动化**：构建基于大模型的智能客服、内容生成等应用
- **DevOps 自动化**：自动化 CI/CD、监控告警和运维任务

## 支持

需要帮助？欢迎访问我们的社区论坛获取支持并与其他用户交流：
[community.n8n.io](https://community.n8n.io)

## 许可证

n8n 采用[公平代码](https://faircode.io)分发模式，使用[可持续使用许可证](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)和 [n8n 企业许可证](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md)。

- **源码可见**：源代码始终公开可见
- **可自托管**：可在任意环境部署
- **可扩展**：添加自定义节点和功能

如需额外功能和支持，可申请[企业许可证](mailto:license@n8n.io)。

更多许可证模型信息，请参阅[文档](https://docs.n8n.io/reference/license/)。

## 参与贡献

发现了 Bug 🐛 或有新功能想法 ✨？查看我们的[贡献指南](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md)开始参与！

---

[English](./README.md) | 简体中文
