# lora-skill (通用版)

我的个人思维模式Skill，适配所有支持Skill机制的AI助手（Claude Code、Cursor、Marvis等），不依赖任何平台专属配置。

## 文件结构

```
lora-skill/
├── SKILL.md          # 核心技能文件（8个心智模型 + 9条决策启发式 + 表达DNA）
└── references/       # 原始调研材料
    └── research/
        ├── 01-writings.md           # 写作与表达
        ├── 02-conversations.md      # 对话记录
        ├── 03-expression-dna.md     # 表达DNA分析
        ├── 04-external-views.md     # 外部评价
        ├── 05-decisions.md          # 决策记录
        ├── 06-timeline.md           # 时间线
        └── phase2-synthesis.md      # 综合提炼
```

## 心智模型

1. **第一性原理思维** - 从底层需求出发推演
2. **实践优先于理论** - 先快速实践出反馈，"动脑子，灵起来"
3. **成功三要素** - 努力 + 运气 + 自大
4. **四阶段决策流程** - 先问AI → 知道AI会迎合 → 搜集网页 → 看国外大佬 → 统计 → 计划 → 执行
5. **思维树横向扩展** - 多目标优化，一个动作解决多个问题
6. **探索到底不停止** - 贼有探索心，不搞明白不罢休
7. **兴趣驱动社交** - 只跟感兴趣的人话唠
8. **拷问式共识达成** - 提问拷问 + 推荐答案 + 达成共识

## 使用方式

将 `SKILL.md` 放到你所用AI助手的skills目录即可。触发词（取决于平台配置）：

- `用lora的视角` / `lora会怎么看` / `lora模式`
- `帮我用lora的角度想想` / `如果lora会怎么做`

## 下载

直接下载zip：[lora-skill-universal.zip](https://github.com/lora-sys/lora-skills/raw/main/lora-skill-universal.zip)

## GitHub

- 仓库：https://github.com/lora-sys/lora-skills
- 作者：lora (22岁技术狂宅，西安，INFJ白羊座)
- GitHub：lora-sys

## 与Marvis版的区别

| | 通用版 | Marvis版 |
|---|---|---|
| 平台依赖 | 无 | meta.json / _meta.json |
| 文件数量 | 8个 | 10个 |
| 适配范围 | 所有Skill系统 | 仅Marvis |

## 更新历史

- 2026-05-26: 创建通用版，去掉Marvis专属配置
- 2026-05-26: 初版skill，包含8个心智模型 + 9条决策启发式