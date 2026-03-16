![横幅图片](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - 面向技术团队的安全工作流自动化平台

[English](./README.md) | 简体中文

n8n 是一个工作流自动化平台，为技术团队提供代码的灵活性与无代码的开发速度。凭借 400+ 集成、原生 AI 能力以及公平代码许可证，n8n 让你在构建强大自动化流程的同时，完全掌控自己的数据和部署环境。

![n8n.io - 截图](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## 核心能力

- **按需编写代码**：可编写 JavaScript/Python、引入 npm 包，或直接使用可视化界面操作
- **AI 原生平台**：基于 LangChain 构建 AI 智能体工作流，使用你自己的数据和模型
- **完全掌控**：通过公平代码许可证自托管，或使用我们的[云服务](https://app.n8n.cloud/login)
- **企业级就绪**：支持高级权限管理、SSO 单点登录及离线（Air-gapped）部署
- **活跃社区**：提供 400+ 集成和 900+ 开箱即用的[工作流模板](https://n8n.io/workflows)

## 快速开始

通过 [npx](https://docs.n8n.io/hosting/installation/npm/) 即刻体验 n8n（需要安装 [Node.js](https://nodejs.org/en/)）：

```bash
npx n8n
```

或使用 [Docker](https://docs.n8n.io/hosting/installation/docker/) 部署：

```bash
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

启动后在浏览器访问 http://localhost:5678 打开编辑器。

## 相关资源

- 📚 [官方文档](https://docs.n8n.io)
- 🔧 [400+ 集成列表](https://n8n.io/integrations)
- 💡 [示例工作流](https://n8n.io/workflows)
- 🤖 [AI 与 LangChain 指南](https://docs.n8n.io/langchain/)
- 👥 [社区论坛](https://community.n8n.io)
- 📖 [社区教程](https://community.n8n.io/c/tutorials/28)

## 获取支持

需要帮助？欢迎访问我们的社区论坛，与其他用户交流并获得支持：
[community.n8n.io](https://community.n8n.io)

## 许可证

n8n 采用[公平代码](https://faircode.io)模式，在[可持续使用许可证](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)和 [n8n 企业许可证](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md)下发布。

- **源码开放**：源代码始终可见
- **可自托管**：可部署到任意环境
- **可扩展**：支持添加自定义节点和功能

如需企业许可证以获取更多功能和支持，请联系：[license@n8n.io](mailto:license@n8n.io)

更多许可证信息请参阅[官方文档](https://docs.n8n.io/reference/license/)。

## 参与贡献

发现了 Bug 🐛 或有新功能想法 ✨？请查阅我们的[贡献指南](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md)以了解如何参与。

## 加入团队

想要共同塑造自动化的未来？查看我们的[招聘信息](https://n8n.io/careers)，加入我们的团队！

## n8n 是什么意思？

**简短回答：** n8n 代表"nodemation"，发音为 n-eight-n（n 八 n）。

**详细回答：** "我经常被问到这个问题（比我预想的还要频繁），所以我决定在这里作一个解答。在寻找一个好名字并且域名还未被注册的过程中，我很快意识到所有我能想到的好名字都已经被占用了。最终，我选择了 nodemation。'node-' 代表它使用了节点视图（Node-View）并且基于 Node.js；'-mation' 来自 'automation'（自动化），这正是这个项目要实现的目标。但我不喜欢这个名字太长，也无法想象每次在命令行里都要输入这么一大串。于是，'n8n' 就这样诞生了。" —— **Jan Oberhauser，n8n.io 创始人兼 CEO**
