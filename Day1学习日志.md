# mini-swe-agent 学习日志 · Day 1

> 日期：__26__年_10_月_10_日　　用时：_2_小时　　分支：`day-1-setup`

## 今日目标

- [ ] 配置 Git 与 GitHub（SSH key、fork/新建学习仓库）
- [ ] 安装并跑通 mini-swe-agent（`uvx mini-swe-agent` 或源码 `pip install -e .`）
- [ ] 配置模型 API key，运行 `mini` 完成一个小任务
- [ ] 浏览仓库结构，记录每个目录的作用
- [ ] 提交并 push 到 GitHub

## 今天做了什么

| 事项 | 结果 | 备注 |
| --- | --- | --- |
| Git 全局配置（user.name / user.email） | ✅/❌ |  |
| 生成 SSH key 并添加到 GitHub | ✅/❌ | `ssh -T git@github.com` 验证 |
| Fork / 新建学习仓库并 clone | ✅/❌ | 仓库地址： |
| 安装 mini-swe-agent | ✅/❌ | 方式：uvx / pip / 源码 |
| 配置 API key | ✅/❌ | 模型： |
| 跑通一次 `mini` 任务 | ✅/❌ | 任务内容： |
| 浏览仓库结构 | ✅/❌ |  |
| commit & push | ✅/❌ | commit hash： |

## 仓库结构速记（今日观察）

```javascript
src/minisweagent/
├── agents/        # （填：作用）
├── environments/  # （填：作用）
├── models/        # （填：作用）
├── run/           # （填：作用）
└── config/        # （填：作用）
```

## 遇到的问题与解决办法

1. **问题：**（例：pip install 报依赖冲突 / SSH 连接被拒 / API key 不生效……）

- **现象：** 报错信息：
- **排查过程：**
- **解决办法：**

2. **问题：**

- **现象：**
- **排查过程：**
- **解决办法：**

## 今日收获（3 句话以内）

1.
2.
3.

## 明日计划（Day 2：精读 Agent 主循环）

- 逐行读 `minisweagent/agents/default.py`
- 加 print 观察 messages 的线性追加过程
- 画主循环流程图

---

**Git 记录：** `git log --oneline` 最新一条：