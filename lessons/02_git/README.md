# 课程 02 · Git 与版本控制基础

本节课将带你掌握 Git 的基本使用方法，学会如何初始化代码仓库、提交修改，并管理项目的历史版本。

---

## 🎯 学习目标

- 安装并验证 Git 环境
- 初始化本地 Git 仓库
- 使用 Git 跟踪、提交文件
- 查看修改历史与差异
- 恢复旧版本（基础）

---

## 🛠️ 步骤一：安装 Git

**为什么？**  
Git 是最常用的版本控制系统，可以追踪代码历史，便于协作与回滚。

**操作步骤：**

1. 打开官网：<https://git-scm.cn>
2. 下载并安装 Windows 版本
3. 安装完成后，打开命令行执行：

   ```bash
   git --version
   ```

若看到版本号如 `git version 2.42.0`，说明安装成功。

---

## 📁 步骤二：初始化 Git 仓库

**操作：**

1. 进入你之前创建的项目文件夹：

   ```bash
   cd my-first-project
   ```

2. 初始化 Git 仓库：

   ```bash
   git init
   ```

3. 创建 `.gitignore` 文件，忽略某些不需要跟踪的文件（例如虚拟环境，虽然本课未涉及）：

   ```dir
   venv/
   __pycache__/
   ```

---

## 📝 步骤三：首次提交代码

1. 查看当前状态：

   ```bash
   git status
   ```

2. 添加所有文件：

   ```bash
   git add .
   ```

3. 提交变更：

   ```bash
   git commit -m "Initial commit: Hello World project"
   ```

---

## 🧪 步骤四：修改文件并提交第二次

1. 修改 `main.py` 中的输出内容：

   ```python
   print("Hello, Git!")
   ```

2. 查看修改：

   ```bash
   git status
   git diff
   ```

3. 提交变更：

   ```bash
   git commit -am "Update greeting message"
   ```

---

## 🕘 步骤五：查看历史与回退（可选）

查看历史：

```bash
git log --oneline
```

恢复旧版本（仅演示）：

```bash
git checkout <提交ID> main.py
```

恢复当前版本：

```bash
git checkout main.py
```

---

## 📂 项目结构示例（已启用 Git）

```dir
my-first-project/
├── .git/                 # Git 仓库
├── main.py
├── README.md
├── .gitignore
```

---

## 🔗 下一课预告

👉 课程 03 · 虚拟环境与依赖管理（venv + requirements.txt）
