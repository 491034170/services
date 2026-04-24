<h1 align="center">天智工坊 · 服务目录</h1>
<p align="center"><b>Tianmind Studio — Service Catalog, Pricing Guide, and Delivery Flow</b></p>

<p align="center">
  <a href="https://tianmind.com"><img src="https://img.shields.io/badge/官网-tianmind.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="mailto:wx@tianmind.com"><img src="https://img.shields.io/badge/Email-wx@tianmind.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://491034170.github.io/tianmind-landing/"><img src="https://img.shields.io/badge/案例演示-Live_Demo-7C3AED?style=flat-square&logo=githubpages&logoColor=white" alt="Demo"/></a>
  <img src="https://img.shields.io/badge/淘宝店-天智工坊-FF6A00?style=flat-square&logo=alibabadotcom&logoColor=white" alt="Taobao"/>
  <img src="https://img.shields.io/badge/营业执照-已认证-2EA043?style=flat-square" alt="Licensed"/>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License"/></a>
</p>

---

## 如果你是来咨询合作的，先看这里

我适合这几类需求：
- 你需要一个能尽快上线的官网 / 落地页 / 品牌页
- 你需要一个真正可用的后台 / 内部工具 / SaaS 原型或企业版功能
- 你想把 AI 接进业务流程，而不是只要一个“能演示”的聊天框
- 你需要从开发到部署的一条龙交付，而不是找几个人东拼西凑

如果你只是想找最低价外包，我可能不是最便宜的。
如果你要的是“看起来像样、实际上能交付”的东西，这个仓库就是给你看的。

---

## 服务范围 / What I deliver

| 服务方向 | 典型交付 | 起价参考（RMB） | 说明 |
|---|---|---:|---|
| **企业官网 / 落地页** | 响应式站点、多语言、SEO 基础、Cloudflare / VPS 部署 | ¥1,500 起 | 适合品牌展示、产品介绍、获客承接 |
| **管理后台 / 内部工具** | RuoYi / Vue / React 管理系统、报表、审批流、权限 | ¥5,000 起 | 适合团队流程、数据管理、业务提效 |
| **小程序 / H5** | 微信小程序、Uni-app、活动页、报名 / 收集表单 | ¥3,000 起 | 适合活动、会员、业务触达 |
| **SaaS 平台定制** | 多租户改造、企业版功能、数据看板、租户隔离 | ¥15,000 起 | 适合长期运营的软件业务 |
| **AI 应用集成** | Claude Skill、Agent 工作流、LLM 集成、内容生成、RAG | ¥2,000 / 模块起 | 适合把 AI 接到真实流程里 |
| **部署 / 运维托管** | Docker、Nginx、域名 SSL、Cloudflare、自动部署 | ¥500 起 | 可按次，也可月度托管 |

> 报价说明：以上为起价，不同需求复杂度差异很大。需求越明确，报价越快。首次沟通免费。

---

## 公开案例 / Public proof

### 建站 / 部署 工程工具链（真实 production 沉淀开源）

### 1. [site-bootstrap](https://github.com/491034170/site-bootstrap) ⭐
一条命令部署静态站 / Node 应用到 VPS —— Cloudflare DNS + nginx + Let's Encrypt 全链路自动化。带 rollback、`--dry-run`、zero-deps。
- 源码：<https://github.com/491034170/site-bootstrap>
- Release：<https://github.com/491034170/site-bootstrap/releases/latest>

### 2. [vps-init](https://github.com/491034170/vps-init) ⭐
一键初始化 Ubuntu / Debian VPS，为中国大陆 / 香港 VPS 做过针对性调优。4 种 profile（minimal / web-cn / node-app / docker-host），全部模块幂等、可预览、带防锁死保护。
- 源码：<https://github.com/491034170/vps-init>
- Release：<https://github.com/491034170/vps-init/releases/latest>

### 3. [cloudflare-cn-kit](https://github.com/491034170/cloudflare-cn-kit) ⭐
面向中国/香港运维的 Cloudflare CLI。核心卖点：`cfcn ssl diag` 一条命令诊断 Flexible-SSL 无限重定向死循环（这是 CN 区域运维最常撞的墙）。
- 源码：<https://github.com/491034170/cloudflare-cn-kit>
- Release：<https://github.com/491034170/cloudflare-cn-kit/releases/latest>

### 其它作品 / Other work

### 4. [tianmind-landing](https://github.com/491034170/tianmind-landing)
独立开发者 / 工作室品牌落地页模板。
- 源码：<https://github.com/491034170/tianmind-landing>
- 在线演示：<https://491034170.github.io/tianmind-landing/>

### 5. [expert-review-panel](https://github.com/491034170/expert-review-panel)
严审型 Claude Skill / AI 工作流，面向论文、BP、代码、竞赛材料的提交前评审。
- Live Guide：<https://491034170.github.io/expert-review-panel/>

### 6. [english-coach](https://github.com/491034170/english-coach)
把 Claude 对话变成英语学习流程的 skill。
- Live Guide：<https://491034170.github.io/english-coach/>

### 7. ruoyi-saas（私有商业项目，可提供 demo）
基于 RuoYi-Vue 的多租户 SaaS 管理系统，支持泛域名部署和企业租户隔离。

---

## 合作流程 / How we work

```text
1. 需求沟通      → 2. 方案与报价      → 3. 合同 / 定金
   免费，通常当天回复    1-2 个工作日内给出   50% 定金后启动

4. 阶段交付      → 5. 验收与尾款      → 6. 部署与售后
   每个里程碑有 demo     验收通过后结算       30 天免费修复
```

我更偏好这样合作：
- 先把范围说清楚，再谈报价
- 先做可运行里程碑，再继续扩展
- 能复用开源方案就不重复造轮子
- 必须交源码，不做“系统绑架”

---

## 为什么客户愿意继续合作 / Why clients come back

- ✅ 阶段可见：每个里程碑都有东西能看、能跑、能验收
- ✅ 可签合同、可开发票
- ✅ 源码交付 + 部署文档 + 基本运维说明
- ✅ 支持后续迭代，不是一锤子买卖
- ✅ 接受保密协议（NDA）
- ✅ 不满意可按进度结算、退余款

---

## 常见问题 / FAQ

### Q1. 你和低价外包的区别是什么？
A：我更强调“可交付结果”，不是便宜到做不下去。你买到的是清晰沟通、阶段可见、源码交付、可上线能力。

### Q2. 可以签合同、开票吗？
A：可以。已工商注册，有营业执照，可配合合同流程与开票。

### Q3. 能做 AI，但也能做完整系统吗？
A：能。我的优势不是只会写 prompt，而是能把前端、后端、部署、AI 集成接成完整链路。

### Q4. 只做定制，不做模板吗？
A：两种都做。预算有限可以从成熟模板 / 开源方案起步，预算充足可以按需求定制。

### Q5. 项目做到一半不满意怎么办？
A：按已完成进度结算，未完成部分退余款。阶段交付就是为了避免一次性赌全款。

### Q6. 能先看案例或 demo 吗？
A：可以。公开仓库里能先看一部分；涉及商业项目的可在沟通后提供 demo 或截图。

---

## 联系方式 / Contact

- 🌐 官网：<https://tianmind.com>
- 📧 邮箱：<mailto:wx@tianmind.com>
- 🛒 淘宝：搜索「天智工坊」
- 💬 GitHub：直接提一个 [Issue](https://github.com/491034170/services/issues/new)

如果你准备发需求，建议带上这几项：
- 项目目标
- 预期上线时间
- 预算范围
- 参考链接 / 参考产品
- 是否需要部署、运维、后续维护

---

## License

MIT © 2026 天智工坊 · Tianmind Studio
