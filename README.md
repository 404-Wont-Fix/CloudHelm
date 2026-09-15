# CloudHelm

> 云端 Helm —— 项目仓库初始化占位说明。

## 项目简介

CloudHelm 是一个正在开发中的项目。本仓库已完成 Git 协作基础设施初始化，尚未包含业务代码。

## 仓库结构

```
CloudHelm/
├── README.md      # 项目说明
├── WORKFLOW.md    # 双账户协作工作流（开发前必读）
└── .gitignore     # Git 忽略规则
```

## 开发环境准备

```bash
git clone <your-fork-url> CloudHelm
cd CloudHelm
```

克隆后请先阅读 [WORKFLOW.md](./WORKFLOW.md)，了解本仓库的双账户远端与分支约定。

## 分支约定

| 分支     | 位置                 | 用途                              |
| -------- | -------------------- | --------------------------------- |
| `main`   | 上游主仓库（新账户） | 稳定分支，仅通过 PR 合入          |
| `dev`    | 开发 fork（老账户）  | 长期开发集成分支，日常推送到这里  |

## 协作流程一句话版本

**开发 → 推送老账户 `dev` → 老账户发 PR → 新账户 `main`。**

详细操作与命令见 [WORKFLOW.md](./WORKFLOW.md)。

## 许可证

待补充。
