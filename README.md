# Steve Leonard
Senior software engineer with 20+ years in financial services, 
currently expanding into AI and LLM-powered systems.

### 🤖 Chat with my AI twin
[![Chat with the AI twin of Steve Leonard](https://raw.githubusercontent.com/leonarduk/ai-systems-lab/main/projects/08-linkedin-avatar/site/og-image.png)](https://leonarduk.github.io/ai-systems-lab/projects/08-linkedin-avatar/site/)

Ask it about my career or any project in my GitHub — it reads both, and says when it doesn't know. **[Try it →](https://leonarduk.github.io/ai-systems-lab/projects/08-linkedin-avatar/site/)**

## What I build
- 🤖 LLM-powered systems and MCP tool servers
- ☁️ Serverless AWS architectures  
- 📊 Financial data platforms and risk systems
- 🎵 Real-time audio/DSP systems with CUDA-accelerated ML inference

## Currently working on

**CiCAID, IssueWorm, and Doodlebug** - tools to automate and simplify code development from issue to release
- [cicaid](https://github.com/leonarduk/cicaid) *(public)* — GitHub plumbing CLI: sync issues, work-on-issue/PR, dependabot auto-merge, local CI checks, PR linking
- [cicaid-pro](https://github.com/leonarduk/cicaid-pro) *(private)* — adds the AI engine on top: LLM code review for local diffs and PRs (Claude/DeepSeek/GPT/Ollama), issue triage and AI-slop cleanup, AI-drafted commit/PR messages, aider integration
- [issue-worm](https://github.com/leonarduk/issue-worm) *(public)* — CLI shell: config, workspace management, run history, version checks
- [issue-worm-pro](https://github.com/leonarduk/issue-worm-pro) *(private)* — the multi-agent engine: Coder→Verifier→Analyser orchestration loop, scheduler (poll/dispatch/label lifecycle), the coder/analyser/triage agents, and the [cicaid-pro](https://github.com/leonarduk/cicaid-pro) bridge
- [doodlebug](https://github.com/leonarduk/doodlebug) *(private)* — CLI tool that audits a website against a QA plan specified in YAML — it will be split into open core later
- [local-github-runner](https://github.com/leonarduk/local-github-runner) *(public)* — ephemeral, containerised, self-hosted GitHub Actions runners for private repos, to avoid burning through Actions minutes

**AllotMint** — serverless investment tracking platform
- [allotmint](https://github.com/leonarduk/allotmint) *(public)* — React frontend, FastAPI backend, portfolio analytics
- [allotmint-pro](https://github.com/leonarduk/allotmint-pro) *(private)* — screener, risk/VaR, compliance, allowances, and AWS deploy infra
- [allotmint-mcp](https://github.com/leonarduk/allotmint-mcp) — Spring Boot MCP server exposing the AllotMint API

**Other**
- [sing-attune](https://github.com/leonarduk/sing-attune) *(private)*  — Windows desktop app for choir singers; real-time pitch detection against a MusicXML score using CUDA/torchcrepe, with WebSocket streaming and a Web Audio API frontend

## Teaching

**[Udemy](https://www.udemy.com/user/stephen-leonard/)** — six published practice-test courses, timed and
scored, with every answer explained (and cited) rather than just a letter. Code questions are compiled and
run against a real JDK or runtime before they ship. Each course has a private packaging repo (the question
bank plus the CSV bulk-upload tooling), most of them fed by a separate repo where the content is authored
and verified.

**Certification prep**
- **[Java SE 25 Certification Practice Tests (1Z0-831)](https://www.udemy.com/course/java-se-25-certification-practice-tests-1z0-831/)** —
  6 timed mock exams, 300 questions, all 10 official exam domains. Explanations cite the JLS, the relevant
  JEP or the API docs; code-output questions are verified against JDK 25.0.1. Use `LOYALTY_PAYS` for free access (valid until mid-November 2026).
  — [java25-udemy-practice-tests](https://github.com/leonarduk/java25-udemy-practice-tests) *(private)*, from [java_25_cert](https://github.com/leonarduk/java_25_cert) *(private)*
- **[Java SE 21 Certification Practice Tests (1Z0-830)](https://www.udemy.com/course/java-se-21-certification-practice-tests-1z0-830/)** —
  6 timed mock exams, 300 questions, all 10 official exam domains, verified against JDK 21.
  — [java21-udemy-practice-tests](https://github.com/leonarduk/java21-udemy-practice-tests) *(private)*
- **[Python Institute PCEP + PCAP Practice Tests](https://www.udemy.com/course/python-institute-pcep-pcap-practice-tests/)** —
  222 questions across 6 timed tests (PCEP-30, PCAP-31 and two code-output-prediction challenges), mapped
  to both certifications' official domains. Use `LOYALTY_PAYS` for free access (valid until mid-November 2026).
  — [python-udemy-practice-tests](https://github.com/leonarduk/python-udemy-practice-tests) *(private)*, from [python-cert-prep](https://github.com/leonarduk/python-cert-prep) *(private)*

**Engineering in practice**
- **[Practice Tests: Spring Boot & Spring AI](https://www.udemy.com/course/practice-tests-spring-boot-spring-ai/)** —
  3 timed tests, 138 questions on Spring Boot 4.1 and Spring AI 2.0, built from code that was actually run.
  — [spring-boot-ai-udemy-practice-tests](https://github.com/leonarduk/spring-boot-ai-udemy-practice-tests) *(private)*, from [spring_boot_ai_cert](https://github.com/leonarduk/spring_boot_ai_cert) *(private)*
- **[AI Code Review for Finance Developers: Practice Tests](https://www.udemy.com/course/ai-code-review-for-finance-developers-practice-tests/)** —
  216 questions on 72 AI-written pull requests in Python and Java, seeded with money, date and payment bugs;
  every answer is proven by a test. The exercise pack (no answers) is public:
  [ai-code-review-exercises](https://github.com/leonarduk/ai-code-review-exercises).
  — [ai-code-review-practice-tests](https://github.com/leonarduk/ai-code-review-practice-tests) *(private)*
- **[Financial Risk & Markets Concepts for Software Engineers](https://www.udemy.com/course/financial-risk-markets-concepts-for-software-engineers/)** —
  150 questions that catch the settlement-date bug before it ships: the risk and markets concepts engineers
  need when building trading and settlement systems.
  — [risk-eng-for-swe-udemy-practice-tests](https://github.com/leonarduk/risk-eng-for-swe-udemy-practice-tests) *(private)*, from [risk_eng_for_swe_cert](https://github.com/leonarduk/risk_eng_for_swe_cert) *(private)*

**Shared tooling:** [udemy-practice-test-kit](https://github.com/leonarduk/udemy-practice-test-kit) *(public)*

## What I'm looking for
Currently focused on AI-native backend systems, MCP tooling, and 
LLM integration in financial services. Open to senior engineering 
roles where AI is central to the work.

## Writing
[Medium](https://medium.com/@steveleonard11) - 
technical articles on AWS, serverless, and AI systems

## Connect
[LinkedIn](https://www.linkedin.com/in/steveleonard/)
