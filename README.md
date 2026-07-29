# ZingLam

> Building tools that extend Claude Code — memory, thinking, code quality, and infrastructure automation.

网络工程专业，专注 Claude Code 周边工具链开发与运维自动化。

---

## Claude Code 工具生态

四组工具，解决四个 Claude Code 使用者的高频痛点：

### Auto Memory System / 自动记忆系统

[![GitHub](https://img.shields.io/badge/repo-auto--memory--system-blue)](https://github.com/ZingLam0924/auto-memory-system)

Claude Code 会话结束后记忆不保留。Auto Memory System 以 Windows 计划任务每日定时触发，自动解析前一日会话记录，提取技术决策、Bug 修复方案、环境配置等值得留存的内容，写入记忆目录。零人工干预。

**关键设计**：Prompt 内置护栏——不提取情绪化内容、不编造事实、不删除已有记忆。适用于无人值守场景下的隐私与安全性要求。

### Thinking Toolkit / 思维工具箱

[![GitHub](https://img.shields.io/badge/repo-thinking--toolkit-blue)](https://github.com/ZingLam0924/thinking-toolkit)

为 Claude Code 提供结构化思维框架。集成多种分析方法（第一性原理、六顶思考帽、5W2H、鱼骨图、PDCA 等），将模糊的"帮我想想"转化为可复用的分析流程。

### Code Craft / 代码工艺

[![GitHub](https://img.shields.io/badge/repo-code--craft-blue)](https://github.com/ZingLam0924/code-craft)

Claude Code 代码质量 skill。覆盖编码规范、重构检查、错误处理审查，将代码评审标准固化为可重复触发的规则集。

### Dev Environment Playbook / 开发环境搭建手册

[![GitHub](https://img.shields.io/badge/repo-dev--env--playbook-blue)](https://github.com/ZingLam0924/dev-env-playbook)

从裸机到可开发状态的标准化流程。覆盖 Windows/Linux 双平台，包含 JDK、Node.js、Python、Redis、MySQL、Docker 等工具链的安装与配置验证。目标是消除"在我机器上能跑"类问题。

### Nginx Load Balance Playbook / Nginx 负载均衡实战

[![GitHub](https://img.shields.io/badge/repo-nginx--loadbalance--playbook-blue)](https://github.com/ZingLam0924/nginx-loadbalance-playbook)

三台 CentOS 7 虚拟机 → 完整负载均衡集群的实战记录。11 项任务（L7 upstream、L4 iptables NAT、SSL 自签证书、Redis Session 共享、SSH 端口转发、Fail2ban 安全加固、JMeter 压测 5000 次零错误）全部验证通过。每篇文档说明配置原因、验证方法与踩坑记录。

---

## 技术栈

`Claude Code` `GitHub Actions` `Windows Task Scheduler` `PowerShell` `Nginx` `CentOS 7` `Redis` `SSL/TLS` `iptables` `Fail2ban` `JMeter` `Docker` `Java` `Python` `Node.js`

---

## 联系

- GitHub: [@ZingLam0924](https://github.com/ZingLam0924)
- Email: 26947251@qq.com
