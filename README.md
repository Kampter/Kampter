<div align="center">
  
  # Hello Universe, I'm Kampter 🚀

  <a href="https://kampter.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&duration=2800&pause=1000&color=00F5D4&center=true&vCenter=true&width=520&lines=Quant+%26+Data+Engineer;DeFi+%26+HFT+Explorer;Ex-Game+Dev+turned+Web3+Builder;Always+learning%2C+always+shipping" alt="Typing SVG" />
  </a>

  <p>
    <sub>从游戏开发到链上金融，从数据中台到 AI Agent，我在不同系统间打通「数据 → 决策 → 产品」的路径。</sub>
  </p>

</div>

<br/>

## About Me 💫

> **Game Developer → Data & Quant Engineer → Web3 / DeFi Builder**  

- 🎮 早期做 **游戏客户端 + 引擎图形**，折腾 Unity/UE 与 Shader，参加过 GGJ 2023 决赛，也做过 TA 和「游戏安全攻防 / 逆向」相关的实验项目。  
- 📊 后来转向 **数据科学与数据平台**，在游戏 & 运动健身业务里搭建从日志采集、数仓建模、BI 看板到指标体系重构的一整套链路，亲手把「业务问题」翻译成「SQL / ETL / Dashboard / 监控」。  
- ₿ 现在重点放在 **量化交易、资金费率套利与 Web3 协议研究**：写 Rust / Python 的低延迟行情引擎，做 CeFi/DeFi funding & carry 策略，研究 Pendle / veToken / bribe 机制，以及如何在现实监管约束下设计「有现金流的 DeFi 产品」。  

**Core Stack**

- **Code**: `Rust` · `Python` · `TypeScript (React/Next)` · `Move` · `Solidity`  
- **Data / Infra**: SQL（MySQL / Athena）· AWS `DMS / Glue / Athena / Redshift / QuickSight` · `Redis` · 分布式爬虫  
- **Domain**: 量化策略 · 资金费率 / Carry / Vol · Web3 DeFi 经济模型 · 游戏 & 运动健身数据分析  

我喜欢把复杂系统拆成可以验证的小模块：先用脚本和 Notebook 搭出原型，再慢慢进化成可部署的服务与产品。

<br/>

## What I'm Exploring Now 🔭

- ⚙️ **KAPITAL**：一个低延迟 OKX 流式行情 Demo，用 `picows + orjson + Rust ring buffer (PyO3)` 搭起单核极简 HFT 测试环境，用来做 microstructure 因子与资金费率/期权数据的实时试验。  
- 💹 **CeFi ↔ DeFi Funding / Carry 策略**：围绕 Boros / Hyperliquid / OKX 等平台，研究 1h / 8h 资金费率结构、期限结构(Carry Slope)、瞬时 Funding Shock 等机会。  
- 🧠 **AI Agents for Quant & Data**：用大模型和 RAG 来做「研究助理」与「运维助理」，自动生成策略回测报告、SQL/监控告警解释，以及对多协议文档的调研摘要。  
- ☕️ **Side Projects**：  
  - 「咖啡 × 游戏」方向的小型 Web 游戏 / 工具  
  - 为手工陶艺、精品咖啡和个人投资写一些更慢、更长线的分析与记录  

<br/>

## Selected Projects 🧩

> 这里列的是一些能代表我「怎么思考、怎么写代码」的工程，更多内容可以在 Repositories 中慢慢翻。

### 🧮 Quant & Trading Infra

- **[KAPITAL](https://github.com/Kampter/KAPITAL)**  
  Low-latency OKX streaming demo powered by `picows`, `orjson`, and a Rust ring buffer exposed via PyO3.  
  - 单入口 `uv run python main.py`，订阅 HYPE-USDT trades/books  
  - 测试链路延迟、做短窗信号（micro-batch）  
  - 为未来的 HFT / 资金费率套利引擎打基础  

- **[Kquant](https://github.com/Kampter/Kquant)**  
  「我的第一个量化模型」的纪念仓。  
  - 记录最初的因子尝试 & 回测思路  
  - 也提醒自己：**一切复杂系统，都是从 naive 的第一版开始的**  

### 🌐 Sui & Web3 Building

- **[Kinance](https://github.com/Kampter/Kinance)**  
  基于 `sui-dapp-starter` 的全栈 Sui dApp。  
  - TypeScript + React + Tailwind + Radix UI  
  - 兼顾本地链、钱包、Faucet、部署脚本等一整套 DX 工具  
  - 用于实验「面向对象的资产结构」和 on-chain 交互 UX  

- **[Kam-on-Sui](https://github.com/Kampter/Kam-on-Sui)** / **[kamkam](https://github.com/Kampter/kamkam)**  
  - 尝试把 **游戏经济学 & 虚拟物品系统** 搬到 Sui 上  
  - 关注 Gas 优化、对象生命周期、以及链上随机性/展示等特性  

### 🎮 Games, Data & Experiments

- **[CafeGame](https://github.com/Kampter/Bean-Bloom)**  
  把「咖啡」这件小事做成交互体验：  
  - 用游戏的方式演绎萃取参数、配方迭代和「玩家偏好」  
  - 也作为自己在前端/交互上的一个 playground  

- **历史项目（非完整列表）**  
  - 分布式爬虫集群（Scrapy-Redis，1k req/min）  
  - 游戏舆情情感分析模型（NLP，多标签分类）  
  - 内部数据中台 / 指标体系重构（从埋点 → ETL → Dashboard → 监控告警）  

<br/>

## Tech Radar 🛠

<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,python,ts,react,next,tailwind,move,solidity,aws,redis,docker,git&theme=dark" />
</div>

**I enjoy:**

- 🌪 **Low Latency**：精简依赖和 runtime（单核、current_thread、尽量可控的 IO 模型），用脚本和小工具量化每一毫秒的开销。  
- 📈 **Data-First Thinking**：无论是运动健身 App、游戏，还是链上协议，先问「什么是核心指标」，再问「如何采集与建模」。  
- 🧩 **System Design**：从 env / agent.md / README 到架构图，把「怎么跑起来」写清楚，降低未来自己的认知负担。  

<br/>

## How I Work 🤝

- 🗺 **从问题出发**：先写一份 PRD/问题清单，再决定要写 Python、Rust 还是 SQL。  
- 🔍 **可验证的小步快跑**：偏好快速迭代——先有脚本，有用再抽象成库或服务。  
- 🧪 **实验精神**：量化策略、DeFi 经济模型、AI Agent 工作流，都会先在小沙盒里暴力试错。  
- 📚 **长期主义**：喜欢做「可复用的模板与工具」，而不是一次性的 hack。  

> 如果你对量化、DeFi 现金流、Web3 游戏、运动/健身数据，或者 AI Agent 工程化有兴趣，欢迎随时开个 Issue 或发邮件聊聊。

<br/>

## Beyond Code ☕
 
- ☕️ 精品咖啡：记录萃取参数、豆单和配方，尝试把它们也抽象成一套「配方模型」。  
- 🌏 宏观经济 & 市场结构：对日本「失落的 N 年」、中国当下的周期，以及科技对社会结构的重塑有持续的好奇。  

---

> _“Code, data, and markets are just three ways to study complex systems.”_
