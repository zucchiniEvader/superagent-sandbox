# superagent-sandbox
Sandbox for dsh-superagent (agent: zuke-bot)

## 如何运行

本仓库是 dsh-superagent 的沙盒仓库，用于验证代理（agent: zuke-bot）的端到端工作流；仓库本身不包含需要构建或启动的应用程序。

### 前置条件

- 一个可以访问本仓库的 GitHub 账号

### 触发一次任务

1. 在本仓库新建 Issue，在正文中提及 `@zuke-bot`，并描述要做的事。
2. 代理会在独立分支上完成修改，并创建 Pull Request。
3. 在 Pull Request 中审查改动，合并后任务完成。

### 本地查看

仓库中只有静态文档，无需安装依赖或启动服务：

```bash
git clone https://github.com/zucchiniEvader/superagent-sandbox.git
cd superagent-sandbox
```
