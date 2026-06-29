# Hangul — Korean Learning Tool

An all-in-one Korean self-study tool: vocabulary flashcards, grammar quizzes, and shadowing practice. Open in your browser, no signup required.

## Usage

**Live site (recommended):** [itzak89.github.io/hangul](https://itzak89.github.io/hangul/)

> Vocabulary and Grammar modules work directly. Shadowing requires audio download — use the local setup.

Run locally:

```bash
git clone https://github.com/itzak89/hangul.git
open index.html            # Vocabulary + Grammar ready
python3 server.py          # Shadowing module (port 8766, requires yt-dlp)
```

## Features

**Vocabulary**
- 381 TOPIK 4-6 words, flashcard + typing input modes
- Filter by level / category, adjustable daily quota
- Daily review & intensive review (localStorage)
- Keyboard navigation (Enter to flip, arrow keys to switch)

**Grammar**
- 27 grammar study cards (accordion) + 27 fill-in-the-blank quizzes
- Instant feedback, filter by level / category

**Shadowing**
- Paste YouTube URL + VTT subtitles, auto-download audio
- Audio player with synced subtitle highlighting, click to jump
- "Learned" markers (deduped by video ID + content hash)

**Global**
- EN/CN bilingual UI toggle · daily streak tracker

## Tech

Vanilla HTML/CSS/JS, vocabulary/grammar data embedded as JSON. Shadowing module requires Python server + yt-dlp.

---

# Hangul — 韩语自学工具

一站式韩语自学工具，词汇闪卡 + 语法测验 + 跟读练习。打开浏览器即用。

## 使用

**直接访问（推荐）：**[itzak89.github.io/hangul](https://itzak89.github.io/hangul/)

> 词汇和语法模块可直接使用。跟读模块需下载音频，请用本地方式。

本地使用：

```bash
git clone https://github.com/itzak89/hangul.git
open index.html            # 词汇 + 语法可用
python3 server.py          # 跟读模块（端口 8766，需 yt-dlp）
```

## 功能

**词汇**
- 381 个 TOPIK 4-6 级词汇，闪卡 + 打字输入两种模式
- 等级 / 分类筛选，每日学习量可调
- 今日复习 & 强化复习（localStorage 持久化）
- 键盘导航（Enter 翻转，方向键切换）

**语法**
- 27 个语法点学习卡片（手风琴展开）+ 27 道填空选择题
- 即时反馈，等级 / 分类筛选

**跟读**
- 粘贴 YouTube 链接 + VTT 字幕，自动下载音频
- 音频播放器，字幕同步高亮，点击跳转时间戳
- 已学会标记（按视频 + 内容哈希去重）

**全局**
- 中英双语 UI 切换 · 学习连续天数统计

## 技术

纯静态 HTML/CSS/JS，词汇/语法数据内嵌 JSON。跟读模块依赖 Python server + yt-dlp。
