# Story Garden 内容复刻与来源说明 · 来源：jnuyao/jnuyao.github.io

本文件夹包含从公开 GitHub 仓库 `jnuyao/jnuyao.github.io`（项目名：Story Garden · Primary English）复刻的内容，用于本英语学习项目的参考和结构复用。

## 复刻内容清单

| 文件 | 来源路径 | 用途 |
|---|---|---|
| `story-garden-ref/book-data.ts` | `app/book-data.ts` | 32 本 Primary 1-3 绘本数据（书名、页面、任务结构、音频链接） |
| `story-garden-ref/word-data.ts` | `app/word-data.ts` | 单词数据与学习任务结构 |

## 复刻范围（根据用户确认）
- ✅ 绘本书目与内容参考（书名、故事结构、任务类型）
- ✅ 数据库结构参考（书本、单词、进度设计模式）
- ✅ 网站构建代码参考（数据结构使用方式）
- ❌ 不包含真实音频文件（`public/audio/`）——文件过大且涉及生成记录
- ❌ 不包含真实图片文件（`public/pages/`、`public/books/`）——涉及版权与文件体积

## 来源注明
原始项目：**Story Garden · Primary English**
作者仓库：https://github.com/jnuyao/jnuyao.github.io
许可证：仓库公开，内容用于学习参考，注明原作者来源。

本英语学习页面 (`index.html`) 在以下方面引用了原项目内容：
1. 绘本书目参考：列出原项目包含的 32 本绘本书名（如 Dan the Flying Man、Mrs Wishy-Washy、Walking Through the Jungle 等），用于说明新加坡小学英语教学内容方向。
2. 数据结构参考：参考原项目的 `Book`、`StoryPage`、`BookTasks` 数据模型，用于理解绘本与任务的关联方式。
3. 学习流程参考：参考原项目的“Read → Learn words → Say → Spell → Review”五步学习流程，用于设计本页的互动卡片和复习机制。

## 版权与使用限制
- 本文件夹内容仅作为学习参考和结构复刻使用，不作为商业发行内容。
- 如需在公开页面中直接使用原项目的图片、音频或完整绘本内容，请先确认原仓库的许可协议并获得授权。
- 本英语学习页面的互动内容（单词卡片、绘本模拟故事、KET 对应表）为基于参考内容的自创简易版本，未直接复制原项目的完整绘本页面或音频。
