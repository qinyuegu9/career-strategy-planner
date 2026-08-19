# 商科战略顶层规划师 (Career Strategy Planner)

> 为商科学生提供一对一定制化职业顶层规划，从"神仙打架"切换到"坐地称王"。

## 项目简介

这是一个 DroiClaw 平台 Skill，专为商科学生（尤其是财务、会计、金融背景）设计的职业规划助手。通过系统化的七步流程，帮助学生找到差异化赛道，避免同质化竞争。

## 核心功能

### 七步规划流程

1. **了解个人情况** - 面谈了解意向城市、经历、兴趣、优劣势
2. **选定细分赛道** - 结合十五五规划和区域发展，选定最适合的方向
3. **圈定目标岗位** - 冲、稳、保三档目标，体制内/泛体制/市场化多路径
4. **反向拆解 JD** - 提取岗位共性要求，制定复合背景搭建方案
5. **设计仿真项目** - 2-3 个实战项目，在校即解决实际问题
6. **规划实习路径** - 让每段实习服务于最终目标
7. **整理作品集** - 让隐性能力具象化，持续对齐进度

## 文件结构

```
career-strategy-planner/
├── SKILL.md          # Skill 定义文件（核心）
├── _meta.json        # Skill 元数据
├── README.md         # 项目说明
├── .gitignore        # Git 忽略规则
└── LICENSE           # 开源协议
```

## 安装方法

### 方法一：通过 DroiClaw 技能市场（推荐）

在 DroiClaw 设备上搜索"career-strategy-planner"或"商科战略顶层规划师"，直接安装。

### 方法二：本地安装

1. 克隆本仓库：
```bash
git clone https://github.com/your-username/career-strategy-planner.git
```

2. 通过 devbridge 安装到设备：
```bash
# 打包
python devbridge.py pack career-strategy-planner/SKILL.md

# 安装
python devbridge.py skill-install-zip --name career-strategy-planner --name-zh "商科战略顶层规划师" --zip career-strategy-planner_1.0.0.zip
```

## 使用示例

安装后，在 DroiClaw 对话中直接说：

- "我是厦大财务的，想规划一下职业方向"
- "我想去上海发展，帮我选一个细分赛道"
- "帮我圈定目标单位和岗位"
- "帮我设计几个仿真项目"
- "我的实习应该怎么规划"
- "帮我整理作品集"

## 设计理念

### 为什么需要这个 Skill？

商科生面临的最大问题是**同质化竞争**：
- 大家都考 CPA
- 大家都去四大
- 大家都卷投行

结果是"神仙打架"，谁都出不来。

### 解决方案

**财务底座 + 细分赛道 = 差异化竞争力**

这个 Skill 帮你：
1. 找到属于你的细分赛道
2. 精准匹配目标岗位
3. 设计实战项目积累经验
4. 用作品集展示隐性能力

从"随大流"切换到"坐地称王"。

## 技术细节

- **平台**: DroiClaw
- **类型**: Skill（对话式技能）
- **MCP 工具**: 主要依赖模型能力，不依赖特定手机 MCP 工具
- **版本**: 1.0.0

## 贡献

欢迎提交 Issue 和 Pull Request。

## 许可证

MIT License

## 作者

 Created for OPC 免费全球训练营

## 更新日志

### v1.0.0 (2026-08-19)
- 初始版本
- 七步规划流程
- 个性化职业策略
