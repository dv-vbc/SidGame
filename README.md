# SidGame - 贪吃蛇游戏

## 项目简介

此项目是基于 **OpenClaw** 环境实现的经典 **贪吃蛇（Snake）**  Web 游戏，使用原生 JavaScript、HTML5 Canvas 开发，无任何第三方库。

- **响应式布局**：在 PC、移动端均能自适应显示。
- **多级关卡**：每吃 5 颗食物提升一级，蛇速随之加快。
- **键盘快捷键**：
  - `S` / `Space` 开始游戏
  - `P` / `Space` 暂停游戏
  - `R` / `Space` 继续游戏
  - `N` / `Esc` 重新开始（在游戏结束或暂停时可用）
  - 方向键（↑ ↓ ← →）控制移动
- **触控滑动**：在移动设备上通过左右、上下滑动控制方向。
- **本地存储**：记录最高分和历史成绩（`localStorage`），每局结束后自动保存。

## 技术细节

- **HTML5 Canvas** 用于渲染游戏画面。
- **CSS** 实现渐变背景、按钮样式及响应式布局。
- **JavaScript** 完成游戏逻辑、状态管理、键盘/触控事件、分数和关卡系统。
- **GitHub Pages** 自动部署，访问地址：<https://dv-vbc.github.io/SidGame/>

## 本地运行

1. 克隆仓库或直接打开 `index.html`。
2. 在浏览器中打开即可开始游戏，无需任何依赖。

```bash
# 克隆仓库（如果需要）
git clone https://github.com/dv-vbc/SidGame.git
cd SidGame
# 直接双击 index.html 或使用本地服务器
npx http-server .
```

## 贡献指南

欢迎提交 **Issue** 或 **Pull Request** 来改进功能、优化代码或修复 bug。请确保遵循以下步骤：

1. Fork 本仓库。
2. 创建新分支：`git checkout -b feature/your-feature`。
3. 进行代码修改并本地测试。
4. 提交更改：`git commit -m "Add new feature"`。
5. 推送分支并在 GitHub 上发起 Pull Request。

## 许可证

本项目采用 MIT 许可证，详细请查看 `LICENSE` 文件（如需添加，可自行添加）。
