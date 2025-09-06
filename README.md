# 龙图库（General 分支）

![Stars](https://img.shields.io/github/stars/FengByX/DragonPic?style=social)
![Forks](https://img.shields.io/github/forks/FengByX/DragonPic?style=social)
![最新提交](https://img.shields.io/github/last-commit/FengByX/DragonPic/General)
![文件总数](https://img.shields.io/github/directory-file-count/FengByX/DragonPic/General)

## 📖 项目简介

项目分支链接：[General 分支](https://github.com/FengByX/DragonPic/tree/General) ｜ [Sensitive 分支](https://github.com/FengByX/DragonPic/tree/Sensitive)

**龙图库** 是一个收集和整理「龙图」相关表情包的开源仓库，致力于为社区提供多样化、高质量的交流素材。

* **General 分支**：收录最适合日常交流的表情。
* **Sensitive 分支**：包含攻击性、辱骂类表情，适合个性化表达。

---

## 🚀 安装与使用

1. 克隆仓库并切换到 General 分支：

   ```bash
   git clone https://github.com/FengByX/DragonPic.git
   cd DragonPic
   git checkout General
   ```

2. 将 `assets/general/` 中的表情包复制到你的项目。

3. 在 HTML 或 Markdown 中引用：

   * HTML

     ```html
     <img src="path/to/assets/general/long_happy.png" alt="龙图 开心" />
     ```

   * Markdown

     ```markdown
     ![龙图 开心](https://github.com/FengByX/DragonPic/blob/General/assets/general/long_happy.png?raw=true)
     ```

4. 在 Office Word 中插入：

   * 打开 Word → 插入 → 图片 → 设备上的图片 → 选择对应文件 → 调整大小/布局。

---

## 🌟 使用 PicGo 上传图片到仓库

如果你想快速上传新表情到仓库，推荐使用 [PicGo](https://github.com/Molunerfinn/PicGo)。

### 1. 安装 PicGo

* [下载地址](https://github.com/Molunerfinn/PicGo/releases)
* 安装完成后启动 PicGo 客户端。

### 2. 配置 GitHub 图床

1. 打开 **PicGo 设置 → 图床设置 → GitHub**。
2. 填写以下信息：

   * **仓库名**：`FengByX/DragonPic`
   * **分支名**：`General`
   * **Token**：你的 GitHub Personal Access Token（需要 `repo` 权限）。
   * **存储路径**：`assets/general/`
   * **自定义域名**（推荐）：

     ```
     https://raw.githubusercontent.com/FengByX/DragonPic/General
     ```
3. 点击 **确定** 保存。

### 3. 上传图片

* 将图片拖拽到 PicGo 窗口，上传后会自动生成 Markdown 链接：

  ```markdown
  ![龙图 开心](https://raw.githubusercontent.com/FengByX/DragonPic/General/assets/general/long_happy.png)
  ```

这样就可以直接复制链接在 README、博客、聊天等场景中使用。

---

## 🤝 贡献指南

欢迎提交任何形式的改进：

* ✏️ 添加或优化表情包
* 🐞 修复命名或资源问题
* 📄 完善文档、分类或示例

请先 fork 本仓库并创建分支，提交 PR 后我们会尽快审阅。

---

✨ 愿龙图为你的交流增添更多乐趣！

要不要我直接帮你把这个优化后的 `README.md` 文件生成并替换掉原来的？
