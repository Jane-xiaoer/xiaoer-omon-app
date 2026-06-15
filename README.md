<div align="center">

# 👂 Xiaoer Omon · 小耳万物阅读器

**纯本地的「万能阅读器」——什么文件都能 ① 打开 ② 转格式 ③ 改内容。**

[![下载最新内测版](https://img.shields.io/badge/⬇_下载最新内测版-DMG-7BC043?style=for-the-badge)](https://github.com/Jane-xiaoer/xiaoer-omon-app/releases/latest)

</div>

---

## 这是什么

Omon 是一个 macOS 桌面 app，一个窗口搞定几乎所有文件：

- **看**：Markdown / 文本代码 / HTML / Word(docx) / 老 .doc / Excel / PPT / PDF / 图片 / SVG / 音视频
- **转**：Word/HTML/MD/PDF 互转、Excel→CSV/JSON、PDF→文字/图片、图片互转……（Save As 选后缀）
- **改**：Markdown 所见即所得、代码、HTML、Word/Excel/PPT 就地改字

暖纸底 + 极简界面，内容优先，零导航。

---

## 📥 安装（内测版，3 步）

> ⚠️ **这是内部测试版，还没做苹果公证**，所以第一次打开 macOS 会拦你。按下面做一次就好，之后正常双击。

**第 1 步 · 下载**
点上面绿色按钮，或去 [Releases](https://github.com/Jane-xiaoer/xiaoer-omon-app/releases/latest) 下载 `Xiaoer-Omon-x.x.x-internal.dmg`。

**第 2 步 · 拖进应用程序**
双击打开 DMG → 把 **Xiaoer Omon** 拖到 **Applications** 文件夹。

**第 3 步 · 首次打开（绕过拦截，任选一种）**

- **方法 A（最简单）**：在「应用程序」里**右键点 Xiaoer Omon → 打开 → 再点「打开」**。
- **方法 B（macOS 比较新、方法 A 没有「打开」按钮时）**：双击一次（会被拦）→ 打开**系统设置 → 隐私与安全性** → 拉到最下面，会看到"已阻止 Xiaoer Omon" → 点**「仍要打开」**。
- **方法 C（最稳，懂终端的话）**：打开「终端」粘贴这一行回车，然后正常双击：
  ```bash
  xattr -dr com.apple.quarantine "/Applications/Xiaoer Omon.app"
  ```

做完一次，以后就是普通双击启动。✅

> 💡 **为什么要这一步？** 因为内测版是"未签名/未公证"的。等正式版做了苹果开发者签名+公证，下载下来直接双击就能开，不用任何绕过。

---

## 🧪 内测想收集什么反馈

- 打开各种文件**有没有打不开 / 乱码 / 空白**的
- 转格式（Save As）出来的**产物对不对**（尤其 PDF、Word、Excel）
- 改字、保存（覆盖原件 / 另存）顺不顺
- 缩放 +/− 有没有黑屏、双滚动条、糊
- 任何"我以为它会 XX 结果它 YY"的地方

**反馈方式**：直接发 [Issues](https://github.com/Jane-xiaoer/xiaoer-omon-app/issues) 或私聊小耳，**带上文件类型 + 截图**最好。

---

## 系统要求

- macOS（Apple Silicon / M 系列芯片）
- 纯本地运行，不联网、不上传你的文件

---

<div align="center">
<sub>Observe More, Organize Naturally · 由小耳打造 👂</sub>
</div>
