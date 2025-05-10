# 课程 01 · 开发环境搭建与第一个项目

本节课将带你完成从零搭建 Python 开发环境，并创建你的第一个项目，运行 Hello World。

---

## 🎯 学习目标

- 安装 Python 和 Trae IDE
- 使用虚拟环境管理依赖
- 编写并运行第一个 Python 程序
- 编写项目说明文档 README.md

---

## 🛠️ 步骤一：安装 Python

**为什么？**  
Python 是本系列课程使用的主要语言，开发与测试都依赖它。

**操作：**

1. 打开官网：<https://www.python.org>
2. 点击导航栏「Downloads」
3. 下载适用于 Windows 的安装包
4. 官网太慢的话使用华为云Python镜像。下载最新版本的Python。Windows下载amd64版本就好
5. 安装时**务必勾选** `Add Python to PATH`

**验证安装成功：**

打开命令提示符（CMD），输入：

```bash
python --version
```

输出版本号如：

```text
Python 3.13.3
```

---

## 🖥️ 步骤二：安装 Trae IDE

**推荐理由：**  
Trae 是轻量、快速、AI驱动的开发环境。

**操作：**

1. 打开官网：<https://www.trae.com.cn/>
2. 下载最新版并安装
3. 启动 Trae 后，用手机号登录。

---

## 📁 步骤三：创建项目目录

**为什么？**  
每个项目用单独目录维护，避免冲突和混淆。

**操作步骤（Windows）：**

```bash
mkdir 01_helloworld
cd 01_helloworld
```

---

## ✨ 步骤四：编写并运行 Hello World 程序

**操作：**

1. 打开 Trae IDE，打开 `01_helloworld` 文件夹
2. 新建一个文件 `main.py`
3. 输入以下代码：

```python
print("Hello, world!")
```

**运行：**

```bash
python main.py
```

**输出：**

```text
Hello, world!
```

---

## 🔗 下一课预告

👉 [课程 02 · 管理 Python 环境，管理版本](../02_git_basics/README.md)（即将发布）
