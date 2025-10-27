# THU-SIGS-AIID-2025-AIID-HACKATHON-PERSONAL-PROJECT-Yixuan-Li
---

# 🦊 Fox Project — 智能学习宠物 | AI-Driven Educational Pet

本项目展示了从 硬件原型设计（Hardware Prototype Design） 到 UI界面与角色建模（UI Interface & Character Modeling） 的完整开发过程。
目前已完成硬件接口与尺寸设计、UI原型以及角色模型制作。前端部分使用 HTML 实现界面展示。
> This project demonstrates a complete development process — from hardware prototype design to UI interface and character modeling.
> The hardware interface, sizing, UI prototypes, and 3D character models have been completed. The frontend uses HTML for interface display.
![123456](https://github.com/user-attachments/assets/e25811e4-88b0-4df7-8ec7-7f839dd1b8bd)

---

## 💡 项目灵感 | Project Inspiration

这个项目的灵感源于一个结合 教育（Education 与 情感陪伴（Emotional Companionship) 的创意。
当代的学习工具往往缺乏情感互动，而玩具又缺乏教育意义。
我们希望通过一个 AI驱动的“宠物”，让学习与陪伴融合在一起。
> This proposal presents an AI-driven “pet” designed to combine **education** with **interactive companionship**.
> The pet has a physical appearance similar to a **traditional stuffed animal**, creating warmth and familiarity.

孩子们可以通过完成学习任务来“喂养”这只宠物，而宠物的情绪状态会随着孩子的学习进度变化。
这种机制鼓励孩子主动学习，并在过程中培养责任感与情感连接。
通过结合陪伴与教育，这款 AI 宠物既能满足家长对教育工具的需求，也能满足孩子对有趣互动学习伙伴的期望。
> Children “feed” the pet by completing learning tasks, and the pet’s **emotional state** changes based on their progress.
> This encourages children to engage actively in learning while developing responsibility and emotional connection.
> By combining **companionship with education**, the AI pet meets both **parents’ desire for educational tools** and **children’s need for emotional engagement**.

---

## 📂 项目结构 | Project Structure

### 硬件开发/Hardware

硬件部分包含所有与设备实现相关的文件：
> The hardware section contains all files related to device implementation.
> Source Code：硬件源代码请查看google drive: https://drive.google.com/drive/folders/1jRvZkDxoGEdzoCoVHyK0wyxFGtLVlXFX?usp=sharing

* Interface Table：硬件接口定义与通信说明 (Hardware interface definitions & communication specs)
* Hardware Size：设备尺寸与结构文件 (Hardware sizing & mechanical design)
* Emoji GIF：用于设备表情显示的动态素材 (Animated GIFs for facial expressions)

---

### UI界面原型设计与演示视频 / UI Prototype & Demo Video/**

包含导出的 Figma 原型文件与交互演示视频：
> Includes Figma-exported prototype files and demo videos.

* 原型界面设计 *(UI layout & interaction design)
* 演示视频 *(Demonstration of user interaction flow)

---

### 前端代码 / Frontend Code/

该部分为本项目的核心前端实现，基于 Next.js + TypeScript + Tailwind CSS + Prisma 构建。
URL: https://a0f4y981g5t0-deploy.space.z.ai
> This section contains the core frontend implementation built with Next.js, TypeScript, Tailwind CSS, and Prisma.

| 文件夹 / 文件                                   | 说明 / Description                                                                                    |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| `src/app/`                                 | Next.js 页面结构，包含 `layout.tsx` 与 `page.tsx` *(Next.js app structure including layout and page files)* |
| `src/components/ui/`                       | 自定义 UI 组件，如 Button、Card、Calendar 等 *(Custom UI components such as Button, Card, Calendar, etc.)*    |
| `public/`                                  | 静态资源文件（图片、图标等） *(Static assets like images and icons)*                                              |
| `prisma/schema.prisma`                     | 数据库模型定义，使用 Prisma ORM *(Database schema defined with Prisma ORM)*                                   |
| `server.ts`                                | 自定义服务器端入口（可能包含 API 或 WebSocket） *(Custom server entry, possibly including API or WebSocket)*        |
| `postcss.config.mjs`, `tailwind.config.ts` | 样式与构建配置 *(Styling and build configurations)*                                                        |
| `package.json`                             | 项目依赖与脚本定义 *(Project dependencies and scripts)*                                                      |

⚙️ 该前端支持组件化开发、服务端渲染（SSR）与数据库交互，为后续的智能交互逻辑提供基础。
This frontend supports component-based development, server-side rendering (SSR), and database interaction — serving as the foundation for future intelligent features.

---

### 小狐狸角色建模设计 / Fox Character Modeling/

包含 `.stl` 格式的三维模型：
> Contains .stl 3D model files.

* 角色姿态与表情模型 (Posing and facial models)
* 可用于 3D 打印与可视化渲染 (Usable for 3D printing or visualization)

---

### 小狐狸角色设计 / Fox Character Design/

角色的二维概念设计与视觉资料：
> 2D concept design and reference art for the fox character.

* 原画与草图 (Concept sketches & color design)
* 表情与动作设定 (Emotion & movement references)
---

### 演示视频 / Demo Video/

展示整体项目运行与交互效果：
> Demonstration videos showing overall system flow and interaction.



## 🚀 快速开始 | Quick Start

1. 克隆项目 / Clone the Repository
   ```bash
   git clone https://github.com/yourname/fox-project.git
   ```

2. 打开前端示例 / Open Frontend Example

   ```bash
   cd 前端代码
   open index.html
   ```
   或直接双击 `index.html` 文件打开浏览器

   > Or double-click `index.html` to open it in your browser.



## 📜 License

本项目遵循 **MIT License** 开源协议。
详情请参阅 [LICENSE](./LICENSE)。


