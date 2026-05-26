# 开发指南

## 仓库角色

本仓库（`yuanbw2025/flying-sword-pinball`）是 **独立项目**，不在 my-website 的 subtree 中，拥有完全独立的开发和部署流程。

## 开发流程

```bash
cd ~/Desktop/projects/flying-sword-pinball
git checkout -b feat/xxx
# ... 开发 ...
git add . && git commit -m "feat: xxx"
git push origin main
```

## 本地目录结构

所有项目统一存放在 `~/Desktop/projects/` 下：

```
~/Desktop/projects/
├── my-website/                    ← 集成部署库（Vercel 入口）
├── storyforge/                    ← 故事熔炉
├── yuntype/                       ← 云中书
├── cyber-flying-sword/            ← 赛博飞剑
├── novel-game/                    ← 小说交互游戏
├── ai-slides/                     ← AI 演示文稿
├── ai-presentation/               ← AI 演示稿
├── Infinite_SpatioTemporal_Map/   ← 无限时空图（本仓库）
├── flying-sword-pinball/          ← 飞剑弹珠
├── wechat-html-injector/          ← 微信 HTML 注入器
└── freellmapizh/                  ← 免费 LLM API 中文文档
```
