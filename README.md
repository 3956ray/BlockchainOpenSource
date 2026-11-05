# Blockchain Open Source

面向独立开发者的区块链开源贡献、开发赏金、社区和资助资源导航。

> 本清单中的资源类型不同：普通开源 Issue 不一定有报酬；赏金可能需要先认领或参加评选；Grant 通常是对项目的资助。任务状态、资格和支付规则以项目官方页面为准。

## 目录

- [如何开始](#如何开始)
- [已有资源清单](#已有资源清单)
- [开发赏金与开源任务](#开发赏金与开源任务)
- [开源项目与贡献入口](#开源项目与贡献入口)
- [开发者社区](#开发者社区)
- [项目资助 Grants](#项目资助-grants)
- [安全漏洞赏金](#安全漏洞赏金)
- [贡献流程](#贡献流程)

## 如何开始

- **想找可以提交代码的项目**：从[开源项目与贡献入口](#开源项目与贡献入口)进入 GitHub Issues，搜索 `good first issue` 或 `help wanted`。
- **想找有偿开发任务**：浏览[开发赏金与开源任务](#开发赏金与开源任务)，逐项确认是否有报酬、领取规则和验收要求。
- **已有开源项目，需要资金**：查看[项目资助 Grants](#项目资助-grants)。
- **想做安全研究**：查看[安全漏洞赏金](#安全漏洞赏金)，并按项目的披露规则提交。

## 已有资源清单

| 资源 | 覆盖范围 | 用途 |
| --- | --- | --- |
| [awesome-web3](https://github.com/useWeb3/awesome-web3) | Web3 开发工具、教程、社区与资助 | 广泛了解生态，发现项目 |
| [awesome-ethereum](https://github.com/w3hc/awesome-ethereum) | 以太坊资源、工具和项目 | 寻找以太坊生态项目 |
| [Ethereum Developer Tools List](https://github.com/Consensys/ethereum-developer-tools-list) | 以太坊开发工具和客户端 | 按技术方向发现工具与仓库 |
| [Awesome Web3 Grants](https://github.com/zkprimecapital/awesome-web3-grants) | 跨生态 Grant 计划 | 查找资助入口；申请状态须再次核实 |
| [web3-bounties](https://github.com/wolz-CODElife/web3-bounties) | 社区整理的 Web3 赏金项目 | 补充查找赏金；清单规模较小 |
| [OSS.Fund Funding Directory](https://www.oss.fund/funding/) | 开源赏金平台与资金来源 | 发现更多通用开源平台；包含历史项目 |

这些清单是导航，不代表所列项目当前正在招募或提供奖励。

## 开发赏金与开源任务

| 平台 | 范围 | 机会及报酬说明 |
| --- | --- | --- |
| [Superteam Earn](https://superteam.fun/earn) | 以 Solana 生态为主 | 开发赏金、项目、工作和 Grants；部分任务为竞赛，提交不保证获奖 |
| [Algora](https://algora.io/) | 通用开源软件 | 开源开发赏金；可搜索区块链相关项目 |
| [Dework](https://dework.xyz/) | Web3 社区与 DAO | 项目任务与社区协作；是否有偿取决于具体任务 |
| [FindOpenSource.dev](https://findopensource.dev/contribute) | 通用开源软件 | 聚合适合新贡献者的任务；不保证有报酬 |
| [Good First Issue](https://www.goodfirstissue.org/) | 通用开源软件 | 发现适合初次贡献的 GitHub Issue；不保证有报酬 |

### 已结束的平台

- **[OnlyDust](https://www.onlydust.com/)**：官网宣布 OnlyDust 项目结束，不再作为可用的贡献或资助入口推荐。创始人在公告中将转向归因于开源协作中的代码质量和安全问题；旧文档可能尚未更新。（查阅：2026-11-05）

## 开源项目与贡献入口

以下是项目仓库的公开 Issue 入口，普通 Issue 默认不保证有报酬。开始前请阅读仓库的贡献指南。

### 以太坊

| 项目 | 方向 | 入口 |
| --- | --- | --- |
| ethereum.org | 官网、开发者文档、翻译和网站功能 | [Issues](https://github.com/ethereum/ethereum-org-website/issues) |
| Geth | 以太坊执行客户端；Go | [Issues](https://github.com/ethereum/go-ethereum/issues) · [贡献指南](https://geth.ethereum.org/docs/developers/geth-developer/contributing) |
| Lighthouse | 以太坊共识客户端；Rust | [Issues](https://github.com/sigp/lighthouse/issues) |
| Lodestar | 以太坊共识客户端与工具；TypeScript | [Issues](https://github.com/ChainSafe/lodestar/issues) |

### Solana

| 项目 | 方向 | 入口 |
| --- | --- | --- |
| Agave | Solana 验证节点客户端；Rust | [Issues](https://github.com/anza-xyz/agave/issues) |
| Solana 开发者内容 | 开发者文档与教程 | [Issues](https://github.com/solana-foundation/developer-content/issues) |
| Superteam Earn | Solana 生态机会平台；其自身也是开源项目 | [Issues](https://github.com/SuperteamDAO/earn/issues) |

### 搜索技巧

- [搜索 Geth 的 good first issue](https://github.com/ethereum/go-ethereum/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [搜索 Agave 的 good first issue](https://github.com/anza-xyz/agave/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [搜索以太坊相关的 good first issue](https://github.com/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22%20ethereum)
- [搜索 Solana 相关的 good first issue](https://github.com/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22%20solana)

常见标签：`good first issue`（适合新贡献者）、`help wanted`（需要协助）、`documentation`（文档）、`bounty`（可能有赏金）。各项目标签用法不同，搜索无结果也可能只是没有使用该标签。

## 开发者社区

| 社区 | 方向 | 入口 |
| --- | --- | --- |
| Ethereum 社区 | 以太坊社区、活动与参与方式 | [官方参与导航](https://ethereum.org/community/get-involved/) |
| Superteam | Solana 生态建设者、任务和社区 | [如何参与](https://docs.superteam.fun/the-superteam-handbook/getting-involved/how-to-contribute) |

## 项目资助 Grants

Grant 通常支持一个项目或公共产品的建设，与完成一个固定赏金 Issue 不同。申请条件、周期、地区限制和资金发放方式以具体计划为准。

| 资源 | 说明 |
| --- | --- |
| [Ethereum Ecosystem Support Program](https://esp.ethereum.foundation/) | 以太坊生态项目资助入口 |
| [Gitcoin](https://gitcoin.co/) | Web3 公共产品资金与社区 |
| [Superteam Earn Grants](https://superteam.fun/earn) | 可在平台内查看 Solana 生态资助机会 |
| [Awesome Web3 Grants](https://github.com/zkprimecapital/awesome-web3-grants) | 社区整理的跨生态资助目录 |

## 安全漏洞赏金

以下平台主要面向安全漏洞报告或审计竞赛，和普通开发任务分开列出。请查看每个项目的授权范围和漏洞披露政策。

| 平台 | 方向 |
| --- | --- |
| [Immunefi](https://immunefi.com/) | Web3 安全漏洞赏金 |
| [CodeHawks](https://www.codehawks.com/) | 智能合约安全审计竞赛 |
| [CertiK Bounty](https://www.certik.com/bounty) | 安全赏金及相关服务 |
| [HackenProof](https://hackenproof.com/) | 网络与 Web3 安全漏洞赏金 |
| [TRON Bug Bounty](https://hackerone.com/tron_dao?type=team) | TRON 在 HackerOne 上的漏洞赏金计划 |

## 贡献流程

1. 找到与自己语言和经验匹配的 Issue，确认任务仍开放并查看近期讨论。
2. 阅读仓库的 README、`CONTRIBUTING.md` 和相关安全政策。
3. 在 Issue 留言介绍方案；较大任务或有偿任务先确认是否需要被指派。
4. Fork 仓库，完成修改并运行相关测试。
5. 提交 Pull Request，说明改动和验证方式，关联 Issue。
6. 根据维护者反馈继续修改。

有偿任务开始前，确认赏金金额、认领方式、验收标准、竞争规则、截止时间和支付方式。对安全漏洞使用项目指定的私密披露渠道。

---

本仓库为资源导航，收录不代表对第三方服务、奖励或资金安全的保证。欢迎通过 Issue 或 Pull Request 补充资源、修正失效链接。
