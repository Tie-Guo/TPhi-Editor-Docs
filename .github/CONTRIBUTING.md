# 贡献指南

感谢你有兴趣为本项目做出贡献！以下是参与贡献的基本流程和注意事项。

## 1. 注册 GitHub

如果你还没有 GitHub 账号，请前往 [GitHub官网](https://github.com/) 注册一个账号。

## 2. 准备必须的软件

在开始贡献之前，请确保你已安装以下软件：

- **Visual Studio Code**：推荐用于编辑和预览文档。下载地址：[https://code.visualstudio.com/](https://code.visualstudio.com/)
- **Photoshop**：如需编辑或制作图片素材，请安装 Photoshop（或其他兼容的图像编辑软件）。

## 3. 熟悉 Docsify 和 HTML 图像上传相关知识

- 本项目文档采用 [Docsify](https://docsify.js.org/) 生成和预览。建议阅读其官方文档，了解如何本地启动预览、目录结构和自定义配置等。
- 建议熟悉 Markdown 与 HTML 的基础用法，特别是图片的插入方法：
  - 图片建议上传至项目的 `assets` 或指定图片目录，并采用相对路径引用，例如：`![](./assets/image.png)`。
  - 若图片较大，建议优化后再上传，减少仓库体积。
  - 如需更复杂的排版，可以在 Markdown 文件内嵌入简单的 HTML 代码。
- 如需本地预览 Docsify 文档，可使用以下命令（需先安装 Node.js 和 docsify-cli）：
  ```bash
  npm i -g docsify-cli
  docsify serve .
  ```
  访问本地 http://localhost:3000 预览效果。

## 4. Fork 和克隆仓库

1. 打开本项目的 GitHub 页面：[SungHerobrine97/TPhi-Editor-Docs-Update](https://github.com/SungHerobrine97/TPhi-Editor-Docs-Update)
2. 点击右上角的 **Fork** 按钮，将仓库 Fork 到你的账号下。
3. 在你的 Fork 仓库页面，点击绿色的 **Code** 按钮，复制仓库地址。
4. 在本地终端执行以下命令克隆仓库：
   ```bash
   git clone <你的仓库地址>
   ```
5. 进入仓库目录：
   ```bash
   cd TPhi-Editor-Docs-Update
   ```

## 5. 开始修改

1. 使用 Visual Studio Code 打开项目文件夹。
2. 按照项目需求进行文档或代码修改。
3. 图片建议统一放入 `assets` 文件夹，并采用合适的命名规范。
4. 如果需要添加或修改图片，可使用 Photoshop 处理后，将图片放入合适的文件夹。

## 6. 提交并推送 fork 仓库更改

1. 在本地终端中，先添加更改：
   ```bash
   git add .
   ```
2. 提交更改（请填写有意义的提交信息）：
   ```bash
   git commit -m "你的修改说明"
   ```
3. 推送更改到你的 fork 仓库：
   ```bash
   git push origin main
   ```
   > 注：如有分支，请将 `main` 替换为你的分支名。

## 7. 提交一个 Pull Request

1. 进入你的 fork 仓库页面，点击 **Pull requests** 标签页。
2. 点击 **New pull request** 按钮，选择要合并到本仓库（SungHerobrine97/TPhi-Editor-Docs-Update）的分支。  
   - 通常是你的 `main` 分支对比本仓库的 `main` 分支，或你创建的 feature 分支对比本仓库的相应分支。
3. 在页面下方，填写 Pull Request 的标题和详细描述，说明你的更改内容和目的，尤其是涉及图片、Docsify 配置或结构调整时请详细说明。
4. 检查差异（Diff）页面，确认更改无误。
5. 如有需要，可 @相关维护者或添加标签，便于审核。
6. 点击 **Create pull request** 按钮，正式提交你的 PR。

### 提交 PR 后的注意事项

- **等待审核**：维护者会尽快对你的 Pull Request 进行审核。请保持关注，如有反馈请及时响应。
- **根据反馈修改**：如果审核过程中有需要修改的地方，可以继续在你的分支上进行提交，PR 会自动更新。
- **避免频繁关闭重开 PR**：如需大量修改，请在原有分支完成后推送，无需关闭原有 PR。
- **合并后操作**：PR 被合并后，可以同步（Sync）你的 fork 仓库，保持与主仓库一致。  
  ```bash
  git remote add upstream https://github.com/SungHerobrine97/TPhi-Editor-Docs-Update.git
  git fetch upstream
  git merge upstream/main
  # 或使用 rebase: git rebase upstream/main
  git push origin main
  ```

---

如有任何问题，欢迎在 Issues 区留言或联系项目维护者。感谢你的贡献！