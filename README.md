# Claude Skills

我的 Claude Code 自定义 Skills 集合，致力于最高效的开发体验。

## 已安装 Skills

### project-mentor — 项目开发导师

像老师一样引导你一步步完成项目开发的 skill。触发场景：

- 想做项目但不知从何入手
- 想学新技术并通过实战掌握
- 需要系统化的项目规划和分步引导

**核心特性：**

- **启动同步** — 每次触发自动读取存档，中断后可无缝续接
- **苏格拉底式引导** — 提问优先，引向正确方向后再给具体指导
- **Word 项目方案** — 自动生成结构化项目计划文档
- **分阶段推进** — 4-8 个阶段，完成一步才进下一步
- **五级帮助机制** — 提问→指方向→直白引导→代码询问→代码+讲解
- **自动存档** — .md + memory 双重保障，攻克难点额外存档
- **复盘摘要** — 每阶段生成 Word 复盘（目标/功能/Bug/技术点）
- **项目总结** — 完成后输出含学习者分析的 Word 总结
- **全流程 Skill 驱动** — 自动发现并推荐适用的 skills
- **上下文管理** — 60% 自动触发 compact

## 目录结构

```
claude-skills/
└── project-mentor/
    └── SKILL.md
```

## 安装

```bash
# 克隆仓库
git clone https://github.com/Liamyio/claude-skills.git

# 将 skill 链接到 Claude Code skills 目录
cp -r claude-skills/project-mentor ~/.claude/skills/
```

或者直接用 npx skills 安装（待发布）。

## 许可

MIT
