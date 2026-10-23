# FlowPilot Demo

AI Builder 求职演示用的静态网页原型。站点入口为 `index.html`，运行逻辑为本地模拟，不连接真实模型 API。

## 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库，建议仓库名 `flowpilot-demo`。这个仓库会公开网页源文件。
2. 将本目录中的文件放到仓库根目录，并推送到 `main` 分支。
3. 在仓库的 **Settings → Pages** 中，将 **Build and deployment → Source** 设为 **GitHub Actions**。
4. 打开 **Actions**，等待 `Deploy FlowPilot Demo to GitHub Pages` 工作流完成。

网站地址格式为 `https://<GitHub用户名>.github.io/flowpilot-demo/`，只包含 GitHub 用户名和中性的仓库名，不包含本地文件夹路径。

