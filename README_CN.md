<h1 align="center">精选 Claude 技能集</h1>

<p align="center">
<a href="https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills">
  <img width="1280" height="640" alt="Composio banner" src="https://github.com/user-attachments/assets/adb3f57a-2706-4329-856f-059a32059d48">
</a>


</p>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
  <a href="https://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
  </a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square" alt="License: Apache-2.0" />
  </a>
</p>
<div>
<p align="center">
  <a href="https://twitter.com/composio">
    <img src="https://img.shields.io/badge/Follow on X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" />
  </a>
  <a href="https://www.linkedin.com/company/composiohq/">
    <img src="https://img.shields.io/badge/Follow on LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Follow on LinkedIn" />
  </a>
  <a href="https://discord.com/invite/composio">
    <img src="https://img.shields.io/badge/Join our Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord" />
  </a>
  </p>
</div>

一个精心策划的实用 Claude 技能列表，用于提升 Claude.ai、Claude Code 和 Claude API 的生产力。


> 如果您希望您的技能能够在 500+ 个应用中执行操作，请使用 [Composio](https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills) 进行连接


## 目录

- [什么是 Claude 技能?](#什么是-claude-技能)
- [技能列表](#技能列表)
  - [文档处理](#文档处理)
  - [开发与代码工具](#开发与代码工具)
  - [数据与分析](#数据与分析)
  - [商业与营销](#商业与营销)
  - [沟通与写作](#沟通与写作)
  - [创意与媒体](#创意与媒体)
  - [生产力与组织](#生产力与组织)
  - [协作与项目管理](#协作与项目管理)
  - [安全与系统](#安全与系统)
- [快速开始](#快速开始)
- [创建技能](#创建技能)
- [贡献指南](#贡献指南)
- [资源](#资源)
- [许可证](#许可证)

## 什么是 Claude 技能?

Claude 技能是可定制的工作流程，教导 Claude 如何根据您的独特需求执行特定任务。技能使 Claude 能够在所有 Claude 平台上以可重复、标准化的方式执行任务。

## 技能列表

### 文档处理

- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - 创建、编辑、分析 Word 文档，支持修订跟踪、注释、格式化。
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - 提取文本、表格、元数据，合并和注释 PDF。
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - 读取、生成和调整幻灯片、布局、模板。
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - 电子表格操作:公式、图表、数据转换。
- [Markdown to EPUB Converter](https://github.com/smerchek/claude-epub-skill) - 将 markdown 文档和聊天摘要转换为专业的 EPUB 电子书文件。*由 [@smerchek](https://github.com/smerchek) 提供*

### 开发与代码工具

- [artifacts-builder](https://github.com/anthropics/skills/tree/main/web-artifacts-builder) - 用于创建精细的、多组件 claude.ai HTML 工件的工具套件,使用现代前端 Web 技术(React、Tailwind CSS、shadcn/ui)。
- [aws-skills](https://github.com/zxkane/aws-skills) - AWS 开发,包含 CDK 最佳实践、成本优化 MCP 服务器以及无服务器/事件驱动架构模式。
- [Changelog Generator](./changelog-generator/) - 通过分析历史记录并将技术提交转换为客户友好的发布说明,自动从 git 提交创建面向用户的变更日志。
- [Claude Code Terminal Title](https://github.com/bluzername/claude-code-terminal-title) - 为每个 Claude-Code 终端窗口提供动态标题,描述正在进行的工作,这样您就不会忘记哪个窗口在做什么。
- [D3.js Visualization](https://github.com/chrisvoncsefalvay/claude-d3js-skill) - 教导 Claude 生成 D3 图表和交互式数据可视化。*由 [@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay) 提供*
- [FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) - 集成 ffuf web 模糊测试工具,使 Claude 能够运行模糊测试任务并分析漏洞结果。*由 [@jthack](https://github.com/jthack) 提供*
- [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - 通过提供清晰的选项并处理所选工作流程来指导开发工作的完成。
- [iOS Simulator](https://github.com/conorluddy/ios-simulator-skill) - 使 Claude 能够与 iOS 模拟器交互,用于测试和调试 iOS 应用程序。*由 [@conorluddy](https://github.com/conorluddy) 提供*
- [MCP Builder](./mcp-builder/) - 指导创建高质量的 MCP(模型上下文协议)服务器,用于使用 Python 或 TypeScript 将外部 API 和服务与 LLM 集成。
- [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - 根据官方 Move Book 代码质量检查表分析 Move 语言包,以确保符合 Move 2024 版本的合规性和最佳实践。
- [Playwright Browser Automation](https://github.com/lackeyjb/playwright-skill) - 模型调用的 Playwright 自动化,用于测试和验证 Web 应用程序。*由 [@lackeyjb](https://github.com/lackeyjb) 提供*
- [prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) - 教授知名的提示工程技术和模式,包括 Anthropic 最佳实践和代理说服原则。
- [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - 使用 PICT(成对独立组合测试)为需求或代码设计全面的测试用例,生成具有成对覆盖的优化测试套件。
- [Skill Creator](./skill-creator/) - 提供创建有效 Claude 技能的指导,通过专业知识、工作流程和工具集成扩展功能。
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - 在几分钟内自动将任何文档网站转换为 Claude AI 技能。*由 [@yusufkaraaslan](https://github.com/yusufkaraaslan) 提供*
- [software-architecture](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) - 实现设计模式,包括整洁架构、SOLID 原则和全面的软件设计最佳实践。
- [subagent-driven-development](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) - 为各个任务分派独立的子代理,在迭代之间进行代码审查检查点,以实现快速、受控的开发。
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - 在实现任何功能或错误修复时使用,在编写实现代码之前。
- [using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) - 创建隔离的 git 工作树,具有智能目录选择和安全验证。
- [Webapp Testing](./webapp-testing/) - 使用 Playwright 测试本地 Web 应用程序,用于验证前端功能、调试 UI 行为和捕获屏幕截图。

### 数据与分析

- [CSV Data Summarizer](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - 自动分析 CSV 文件并生成包含可视化的全面见解,无需用户提示。*由 [@coffeefuelbump](https://github.com/coffeefuelbump) 提供*
- [postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) - 对 PostgreSQL 数据库执行安全的只读 SQL 查询,支持多连接和深度防御安全。*由 [@sanjay3290](https://github.com/sanjay3290) 提供*
- [root-cause-tracing](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) - 当错误发生在执行深处时使用,您需要追溯以找到原始触发器。

### 商业与营销

- [Brand Guidelines](./brand-guidelines/) - 将 Anthropic 的官方品牌颜色和排版应用于工件,以实现一致的视觉识别和专业设计标准。
- [Competitive Ads Extractor](./competitive-ads-extractor/) - 从广告库中提取和分析竞争对手的广告,以了解引起共鸣的消息传递和创意方法。
- [Domain Name Brainstormer](./domain-name-brainstormer/) - 生成创意域名想法并检查多个 TLD 的可用性,包括 .com、.io、.dev 和 .ai 扩展名。
- [Internal Comms](./internal-comms/) - 帮助撰写内部沟通,包括第三方更新、公司通讯、常见问题解答、状态报告和项目更新,使用公司特定格式。
- [Lead Research Assistant](./lead-research-assistant/) - 通过分析您的产品、搜索目标公司并提供可操作的外展策略来识别和筛选高质量潜在客户。

### 沟通与写作

- [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - 从网页中提取完整的文章文本和元数据。
- [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) - 通过结构化提问和替代方案探索,将粗略的想法转化为完整的设计。
- [Content Research Writer](./content-research-writer/) - 通过进行研究、添加引用、改进钩子并提供逐节反馈来协助撰写高质量内容。
- [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) - 提供规划家族史和家谱研究项目的帮助。
- [Meeting Insights Analyzer](./meeting-insights-analyzer/) - 分析会议记录以揭示行为模式,包括冲突回避、发言比例、填充词和领导风格。
- [NotebookLM Integration](https://github.com/PleasePrompto/notebooklm-skill) - 让 Claude Code 直接与 NotebookLM 聊天,以获得基于上传文档的源基础答案。*由 [@PleasePrompto](https://github.com/PleasePrompto) 提供*

### 创意与媒体

- [Canvas Design](./canvas-design/) - 使用设计哲学和美学原则在 PNG 和 PDF 文档中创建精美的视觉艺术,用于海报、设计和静态作品。
- [imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - 使用 Google Gemini 的图像生成 API 生成 UI 模型、图标、插图和视觉资产。*由 [@sanjay3290](https://github.com/sanjay3290) 提供*
- [Image Enhancer](./image-enhancer/) - 通过增强分辨率、清晰度和清晰度来提高图像和屏幕截图质量,用于专业演示和文档。
- [Slack GIF Creator](./slack-gif-creator/) - 创建针对 Slack 优化的动画 GIF,具有大小约束验证器和可组合动画原语。
- [Theme Factory](./theme-factory/) - 将专业字体和颜色主题应用于工件,包括幻灯片、文档、报告和 HTML 登录页面,提供 10 个预设主题。
- [Video Downloader](./video-downloader/) - 从 YouTube 和其他平台下载视频,用于离线观看、编辑或存档,支持各种格式和质量选项。
- [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - 从 YouTube 视频中获取转录并准备摘要。

### 生产力与组织

- [File Organizer](./file-organizer/) - 通过理解上下文、查找重复项并建议更好的组织结构来智能地组织文件和文件夹。
- [Invoice Organizer](./invoice-organizer/) - 通过读取文件、提取信息并一致地重命名,自动组织发票和收据以进行税务准备。
- [kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) - 应用持续改进方法论,采用多种分析方法,基于日本改善哲学和精益方法论。
- [n8n-skills](https://github.com/haunchen/n8n-skills) - 使 AI 助手能够直接理解和操作 n8n 工作流程。
- [Raffle Winner Picker](./raffle-winner-picker/) - 从列表、电子表格或 Google Sheets 中随机选择获胜者,用于赠品和竞赛,具有加密安全的随机性。
- [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - 基于反馈循环,帮助迭代下一步要构建或学习的内容的技能。
- [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) - 将相关文档互联并总结为知识网络。

### 协作与项目管理

- [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - 自动化 git 操作和存储库交互。
- [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - 评估代码实现计划并与规范保持一致。
- [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - 检测失败的测试并提出补丁或修复。

### 安全与系统

- [computer-forensics](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) - 数字取证分析和调查技术。
- [file-deletion](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) - 安全文件删除和数据清理方法。
- [metadata-extraction](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) - 提取和分析文件元数据以进行取证。
- [threat-hunting-with-sigma-rules](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) - 使用 Sigma 检测规则来搜寻威胁并分析安全事件。

## 快速开始

### 在 Claude.ai 中使用技能

1. 在聊天界面中点击技能图标(🧩)。
2. 从市场添加技能或上传自定义技能。
3. Claude 会根据您的任务自动激活相关技能。

### 在 Claude Code 中使用技能

1. 将技能放置在 `~/.config/claude-code/skills/` 中:
   ```bash
   mkdir -p ~/.config/claude-code/skills/
   cp -r skill-name ~/.config/claude-code/skills/
   ```

2. 验证技能元数据:
   ```bash
   head ~/.config/claude-code/skills/skill-name/SKILL.md
   ```

3. 启动 Claude Code:
   ```bash
   claude
   ```

4. 技能会自动加载并在相关时激活。

### 通过 API 使用技能

使用 Claude Skills API 以编程方式加载和管理技能:

```python
import anthropic

client = anthropic.Anthropic(api_key="your-api-key")

response = client.messages.create(
    model="claude-3-5-sonnet-20241022",
    skills=["skill-id-here"],
    messages=[{"role": "user", "content": "Your prompt"}]
)
```

有关详细信息,请参阅 [Skills API 文档](https://docs.claude.com/en/api/skills-guide)。

## 创建技能

### 技能结构

每个技能都是一个包含 `SKILL.md` 文件的文件夹,该文件带有 YAML 前置内容:

```
skill-name/
├── SKILL.md          # 必需:技能说明和元数据
├── scripts/          # 可选:辅助脚本
├── templates/        # 可选:文档模板
└── resources/        # 可选:参考文件
```

### 基本技能模板

```markdown
---
name: my-skill-name
description: 清楚描述此技能的功能以及何时使用它。
---

# 我的技能名称

技能目的和功能的详细描述。

## 何时使用此技能

- 用例 1
- 用例 2
- 用例 3

## 说明

[关于 Claude 如何执行此技能的详细说明]

## 示例

[展示技能实际应用的真实示例]
```

### 技能最佳实践

- 专注于特定的、可重复的任务
- 包含清晰的示例和边缘情况
- 为 Claude 编写说明,而不是最终用户
- 在 Claude.ai、Claude Code 和 API 上进行测试
- 记录先决条件和依赖项
- 包含错误处理指导

## 贡献指南

我们欢迎贡献!请阅读我们的[贡献指南](CONTRIBUTING.md)以了解以下详细信息:

- 如何提交新技能
- 技能质量标准
- 拉取请求流程
- 行为准则

### 快速贡献步骤

1. 确保您的技能基于真实用例
2. 检查现有技能中的重复项
3. 遵循技能结构模板
4. 在各个平台上测试您的技能
5. 提交带有清晰文档的拉取请求

## 资源

### 官方文档

- [Claude Skills 概述](https://www.anthropic.com/news/skills) - 官方公告和功能
- [Skills 用户指南](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - 如何在 Claude 中使用技能
- [创建自定义技能](https://support.claude.com/en/articles/12512198-creating-custom-skills) - 技能开发指南
- [Skills API 文档](https://docs.claude.com/en/api/skills-guide) - API 集成指南
- [Agent Skills 博客文章](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - 工程深度剖析

### 社区资源

- [Anthropic Skills 存储库](https://github.com/anthropics/skills) - 官方示例技能
- [Claude 社区](https://community.anthropic.com) - 与其他用户讨论技能
- [Skills 市场](https://claude.ai/marketplace) - 发现和分享技能

### 灵感与用例

- [Lenny's Newsletter](https://www.lennysnewsletter.com/p/everyone-should-be-using-claude-code) - 人们使用 Claude Code 的 50 种方式
- [Notion Skills](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) - Notion 集成技能


## 加入社区

- 对将 Composio 与您的身份验证设置集成有疑问?[与我们快速通话](https://calendly.com/thomas-composio/composio-enterprise-setup)
- [在 Twitter 上关注我们](https://x.com/composio)
- [加入我们的 Discord](https://discord.com/invite/composio)

## 许可证

此存储库根据 Apache License 2.0 许可。

各个技能可能具有不同的许可证 - 请检查每个技能的文件夹以获取特定的许可信息。

---

**注意**: Claude Skills 适用于 Claude.ai、Claude Code 和 Claude API。一旦您创建了一个技能,它就可以在所有平台上移植,使您的工作流程在使用 Claude 的任何地方都保持一致。

- [AgentsKB](https://agentskb.com) - 通过研究答案升级您的 AI。我们进行了研究,因此您的 AI 第一次就能做对。
