🧩 染上了拼豆 · 拼豆图纸生成器

Bead Pattern Generator

一个基于浏览器的拼豆图纸生成工具，将任意图片转换为可编辑的拼豆像素图纸，支持多色号系统、颜色统计与手动编辑。

A browser-based bead pattern generator that converts any image into an editable pixel bead pattern, with multi color systems, statistics, and editing tools.

⸻

✨ 功能特性 | Features

🎨 图纸生成
	•	上传图片（支持 PNG / JPG / WEBP）
	•	自动转换为拼豆像素图纸
	•	自定义横向颗粒数（分辨率控制）
	•	自动颜色匹配（最近色算法）

Upload image → convert to bead pattern with adjustable resolution and automatic color mapping.

⸻

🎯 多色号系统支持

支持多个拼豆品牌色号系统切换：
	•	MARD
	•	COCO
	•	漫漫
	•	盼盼
	•	咪小窝

Supports multiple bead brand color systems.

⸻

🛠 编辑工具
	•	查看：查看颜色信息
	•	上色：手动修改单个像素
	•	替换：批量替换颜色
	•	连通擦除：区域删除（洪水填充）

Interactive editing tools for precise control.

⸻

📊 数据统计
	•	总用豆数
	•	颜色种类数量
	•	每种颜色使用数量
	•	实时更新

Real-time statistics of bead usage and colors.

⸻

📦 导出功能
	•	导出拼豆图纸 PNG
	•	导出 CSV（颜色统计）

Export pattern as PNG and CSV.

⸻

🎯 交互体验优化
	•	Hover 显示颜色信息
	•	可缩放画布
	•	网格线开关
	•	响应式布局

Smooth UX with zoom, hover info, and responsive layout.

⸻

🖼️ 项目预览 | Preview
<img width="1710" height="898" alt="截屏2026-04-15 12 53 46" src="https://github.com/user-attachments/assets/c5f1226d-1479-469b-ab9d-7cdeb0723858" />

🧠 技术实现 | Tech Stack
	•	原生 HTML / CSS / JavaScript
	•	Canvas 图像处理
	•	颜色量化（最近邻算法）
	•	Flood Fill（区域擦除）
	•	自定义调色板映射（291 色）

Built with vanilla JS and Canvas-based image processing.

🏗 核心逻辑 | Core Logic

图像转拼豆流程
	1.	读取原图
	2.	按网格切分
	3.	计算每个格子的主色
	4.	映射到最近拼豆颜色
	5.	渲染 Canvas

连通擦除（Flood Fill）
	•	类似 PS 魔棒工具
	•	基于 DFS / 栈实现

🧩 可扩展方向 | Future Improvements
	•	图片裁剪功能
	•	AI 自动优化配色
	•	导出 PDF 拼豆说明书
	•	社区分享 / 模板库
	•	移动端优化
	•	多图层支持

💡 项目背景 | Background

本项目源于个人兴趣与 Vibe Coding 实践，旨在探索：
	•	用户体验优化
	•	创意工具设计
	•	轻量级图像处理

Built as a personal project combining UX thinking and creative coding.

🙌 致谢 | Acknowledgements

感谢所有拼豆爱好者社区的灵感支持 ❤️
Inspired by the bead art community.

⸻

⭐ 如果你觉得有用

欢迎 Star ⭐ / Fork 🍴 / 提 Issue！
