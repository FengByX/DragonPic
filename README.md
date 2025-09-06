# 🐉 龙图库（General 分支）

![Stars](https://img.shields.io/github/stars/FengByX/DragonPic?style=social)
![Forks](https://img.shields.io/github/forks/FengByX/DragonPic?style=social)
![最新提交](https://img.shields.io/github/last-commit/FengByX/DragonPic/General)
![文件总数](https://img.shields.io/github/directory-file-count/FengByX/DragonPic/General)

---

## 📖 简介

**龙图库** 是一个开源表情包仓库，专注于收集和整理「龙图」相关素材。
无论是日常聊天、社交互动，还是整活斗图，都能在这里找到适合的龙图。

项目分为两个分支：

* **General**：通用龙图，适合大多数聊天场景。
* **Sensitive**：攻击性或带情绪的龙图，适合个性化表达。

👉 分支链接：[General](https://github.com/FengByX/DragonPic/tree/General) ｜ [Sensitive](https://github.com/FengByX/DragonPic/tree/Sensitive)

---

## 🚀 快速使用

1. 克隆仓库并切换分支：

   ```bash
   git clone https://github.com/FengByX/DragonPic.git
   cd DragonPic
   git checkout General
   ```

2. 引用表情包示例：

   * **HTML**

     ```html
     <img src="assets/general/long_happy.png" alt="龙图 开心" />
     ```
   * **Markdown**

     ```markdown
     ![龙图 开心](https://raw.githubusercontent.com/FengByX/DragonPic/General/assets/general/long_happy.png)
     ```
   * **Word**
     插入 > 图片 > 选择 `assets/general/` 下的表情。

---

## 🛠️ 表情上传方式

你可以通过 **本地提交** 或者使用 **PicGo / Flutter-PicGo** 上传龙图。

### 1. 本地提交

1. Fork 本仓库
2. 将图片放到 `assets/general/`
3. 提交 PR，我们会尽快合并

---

### 2. 使用 PicGo 上传（推荐 🎯）

1. **安装 PicGo**
   👉 [下载地址](https://github.com/Molunerfinn/PicGo/releases)

2. **配置 GitHub 图床**

   * 图床类型：`GitHub`
   * 仓库名：`FengByX/DragonPic`
   * 分支名：`General`
   * Token：前往 [GitHub Token 设置](https://github.com/settings/tokens) 创建，勾选 `repo` 权限
   * 存储路径：`assets/general/`

3. **上传图片**

   * 拖拽图片到 PicGo 或使用快捷键上传
   * 上传成功后自动返回直链，例如：

     ```
     https://raw.githubusercontent.com/FengByX/DragonPic/General/assets/general/long_happy.png
     ```
![配置方法](https://github.com/FengByX/DragonPic/blob/General/PicGo%E9%85%8D%E7%BD%AE%E7%A4%BA%E4%BE%8B1.png)
---

### 3. 使用 Flutter-PicGo 上传（移动端 ⚡）

1. **安装 Flutter-PicGo**
   👉 [下载地址](https://github.com/PicGo/flutter-picgo/releases)

2. **配置 GitHub 图床**（与 PicGo 一致）

   * 仓库名：`FengByX/DragonPic`
   * 分支名：`General`
   * Token：GitHub Personal Access Token
   * 存储路径：`assets/general/`

3. **手机端上传**

   * 选择表情图片 → 一键上传
   * 上传成功后，链接会自动复制，方便粘贴到聊天或 Markdown

![配置方法](https://github.com/FengByX/DragonPic/blob/General/Flutter-PicGo%E9%85%8D%E7%BD%AE%E7%A4%BA%E4%BE%8B1.jpg)

---

## 🤝 贡献指南

欢迎加入龙图建设！你可以：

* ✨ 添加新龙图
* 🐛 修复图片命名或分类
* 📚 完善文档与示例

流程：

1. Fork 本仓库
2. 创建分支 `feature/xxx`
3. 提交 PR 等待审核

---

## 💡 小贴士

* 推荐统一命名规则：`long_描述.png`（例：`long_happy.png`）
* 建议上传 **透明背景 PNG**，方便二次使用
* 可用 PicGo / Flutter-PicGo 实现 **即传即用**，效率拉满

---

## ✨ 致谢

感谢所有贡献者对龙图库的支持。
愿龙图让你的对话更加生动有趣！🐉🔥
