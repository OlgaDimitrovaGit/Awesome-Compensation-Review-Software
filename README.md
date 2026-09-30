# Awesome-Compensation-Review-Software

## Top Compensation Review Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Compensation Benchmarking, Merit Cycles, Pay Equity Analysis & Total Rewards Statements*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Compensation Review**. These tools help HR and People teams design salary bands, benchmark roles against market data, run merit and bonus cycles, conduct pay equity audits, and communicate total rewards to employees.



**Examples** include Pave, beqom, Compport, OpenComp, Payfactors, Salary.com CompAnalyst, Workday Compensation, Oracle Compensation, Celential.ai, and PerformYard (the category leaders).



**Open-source emphasis**: Compensation review has a **fragmented open-source ecosystem**. Unlike adjacent HR categories, no single open-source platform covers the full compensation cycle end-to-end. Instead, the ecosystem provides **targeted building blocks**: **GapVision** offers a full-stack pay equity analysis and visualization platform ; **logib** delivers Switzerland's official equal pay analysis methodology as an R package ; **FairPay** demonstrates autonomous compensation benchmarking using Google ADK and BigQuery . **AI Agent Skills** like **afrexai-compensation-planner** provide structured frameworks for salary bands, geographic differentials, and pay equity audits . This section documents these focused solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Pave](https://www.pave.com/)**

  Compensation benchmarking and planning platform. Connects to HRIS systems for real-time market data, salary band management, and merit cycle planning.



- **[beqom](https://www.beqom.com/)**

  Enterprise compensation management platform. Handles merit cycles, bonus planning, sales compensation, and total rewards.



- **[Compport](https://compport.com/)**

  Compensation management software for mid-market and enterprise. Provides salary benchmarking, merit planning, and pay equity analysis.



- **[OpenComp](https://www.opencomp.com/)**

  Compensation decision software for ranges, benchmarks, and merit cycles. Features **Total Rewards Statements** that offer employees a clear picture of total comp with salary, bonuses, equity, and merit increases illustrated over time . Global comp data, pay strategy and ranges, pay equity, and total rewards statements .



- **[Payfactors](https://payfactors.com/)**

  Compensation data management and market pricing platform. Provides salary survey data aggregation, job matching, and merit planning.



- **[Salary.com CompAnalyst](https://www.salary.com/)**

  Compensation data and software platform. Provides market pricing, salary structures, and merit planning tools.



- **[Workday Compensation](https://www.workday.com/)**

  Compensation module within Workday HCM. Provides salary planning, merit cycles, bonus administration, and total rewards.



- **[Oracle Compensation](https://www.oracle.com/)**

  Compensation management within Oracle HCM Cloud. Provides salary planning, workforce compensation, and total rewards.



- **[Celential.ai](https://celential.ai/)**

  AI-powered compensation intelligence platform. Provides real-time market data and pay analytics.



- **[PerformYard](https://performyard.com/)**

  Performance management platform with compensation review capabilities integrated into performance cycles.



## Open-Source GitHub Projects



### Pay Equity Analysis Platforms



- **[GapVision](https://gitlab.com/Roxanne_Ardary/gapvision)**

  **The most comprehensive open-source compensation equity platform.** **AGPL 3.0+ licensed** . Designed to **track, analyze, and visualize compensation data** across industries with a focus on gender pay equity . **Core capabilities**: Compensation & pay data (base salary, bonuses, stock options, retirement contributions; gender breakdown; intersectional data on age, experience, education, seniority, ethnicity, disability status) ; **Equity & gap analysis** (auto-calculation of gender pay gaps, automatic flagging of roles/sectors exceeding thresholds, historical trends, predictive forecasts) ; **Company metrics** (average pay gap per company, % women in leadership, compliance flags, Pay Equity Seal for top performers) ; **Career mobility** (promotion tracking, bottleneck detection, negotiation frequency/success by gender) ; **AI & automation insights** (emerging skills pay impact, automation risk scoring, predictive modeling) ; **Community & crowdsourcing** (anonymous salary submissions, verified contributions, gamification) ; **Dashboards & visualization** (interactive by industry/role/company/gender, exportable reports) ; **Policy & advocacy tools** (anonymized reports for NGOs, policy simulation) . **Tech stack**: Python backend, React/Vue frontend, PostgreSQL database. **Installation**: `pip install -r requirements.txt`, `npm install`, `python app.py` .



- **[logib](https://github.com/admin-ebg/logib)**

  **Switzerland's official equal pay analysis methodology as an R package.** **GPL-3 licensed** . Implements the Swiss Confederation's standard analysis model for salary analyses, developed by the **Federal Office for Gender Equality of Switzerland** . **Intended for medium-sized and large companies (50+ employees)** — companies with at least 100 employees are required by the Gender Equality Act to conduct equal pay analysis . **Features**: Runs equal salary analysis in R with transparency into methodology and automation capabilities . **Functions**: `analysis()` with parameters for reference month/year, usual weekly hours, gender encoding, age format, entry date format; `build_custom_mapping()` for column name mapping . **Data cleaning and validation** built-in. Published on CRAN, version 0.2.0 (December 2024) .



- **[PE-Analysis](https://github.com/alexwems1/PE-Analysis)**

  **Pay equity analysis pipeline in Python.** Includes `__pycache__` with a pipeline and outputs . **Early-stage project** for pay equity analysis workflows.



### Compensation Planning Frameworks (AI Agent Skills)



- **[afrexai-compensation-planner](https://lobehub.com/skills/openclaw-skills-afrexai-compensation-planner)**

  **Comprehensive compensation planning framework for AI agents.** **3,729 GitHub stars** . Covers **base salary bands, equity/bonus frameworks, geographic differentials, and total rewards packaging** . **When to use**: Building/revising salary bands, preparing for hiring sprints, conducting annual compensation reviews, designing equity/bonus/commission structures, benchmarking against competitors . **Framework components**: **Role architecture** (leveled titles with base ranges, equity percentages, bonus targets from L1 Associate to L6 VP/C-level) ; **Geographic differentials** (cost-of-labor multipliers by market tier — Tier 1 SF/NYC/London baseline, Tier 5 Eastern Europe/LATAM/SEA at 0.40-0.60x) ; **Total compensation package** (cash compensation, equity compensation, benefits & perks typically 20-35% on top of base) ; **Pay equity audit** (quarterly compa-ratio checks, gender pay gap analysis, tenure compression detection, band penetration flags) ; **Annual review cycle** framework . **Installation**: `npx skillsauth add openclaw/skills 1kalin/afrexai-compensation-planner` — works with Claude Code, Cursor, and Windsurf .



- **[team-composition-analysis](https://skills.rest/skill/team-composition-analysis-p-o-ke-nae)**

  **Startup hiring and compensation planning skill.** Helps founders decide who to hire, when, how much to pay, and how to structure ownership . **Core features**: Hiring plan design by stage (pre-seed through Series A); compensation planning with salary benchmarks, fully loaded costs, and geographic adjustments; equity allocation with founder/employee equity ranges and option pool sizing; org chart design . **Use case**: A seed-stage SaaS founder can decide whether to hire an engineering lead, first sales rep, or product manager first, then estimate budget and equity impact .



### Compensation Benchmarking



- **[FairPay](https://github.com/kcngkc/FairPay)**

  **Autonomous HR compensation benchmarking agent** (Google Cloud Rapid Agent Hackathon 2026) . **Architecture**: Google ADK v2.1.0 with `SequentialAgent` for deterministic orchestration; **Dual-model strategy** (Gemini 2.5 Flash for tool-calling, Gemini 2.5 Pro for reasoning) . **Data sources**: BLS OEWS May 2025 (830+ occupations × 400+ metros), synthetic HRIS data, position-to-SOC mapping . **Key features**: Data gap detector, benchmarking (computes compa-ratio, confidence), narrative executive report with **HITL escalation gate** when compa-ratio < 0.85 . **Fivetran MCP integration** for data health checks . **Educational/research-grade**, demonstrates agent-based compensation analysis.



- **[Compshop](https://beta.mcp.so/servers/compshop)**

  **Independent directory of 350+ compensation surveys** . Aggregates and searches **17+ vendors** including Mercer, WTW, Aon Radford, SullivanCotter, Gallagher, Pearl Meyer, Empsight, Culpepper, Croner, and more . **Search by**: Job title, industry, geography, or publisher . **Tech stack**: Next.js 14, TypeScript, Tailwind CSS, SQLite (bundled) . **Deployment**: Vercel or local. **~3,500 statically-generated SEO-optimized pages** . **MCP server** for AI assistant integration.



### Total Rewards & Benefits



- **[Total Rewards Statement Template](https://peopleopsclub.com/resources/total-rewards-statement-template)**

  **Free template for creating total rewards statements.** Shows employees the full value of their package — salary, bonus, equity, benefits, and perks — in one clear summary . **Sections**: Employee details; Direct compensation (base salary, annual bonus, equity annualized, sign-on/retention bonus); Benefits & employer contributions (health/medical premium, retirement match, life & disability insurance, PTO cash value); Total rewards summary . **Key insight**: Employees consistently underestimate benefits value; showing total rewards often **20-40% above base salary** is one of the cheapest retention tools . **Includes**: Employer-cost column so true package value is visible .



- **[hr-compensation-benefits Skill](https://www.skills.sh/tuanductran/hr-skills/hr-compensation-benefits)**

  **AI Agent Skill for compensation and benefits support.** **57 GitHub stars, 13 installs** . **Supported tasks**: Analyzing compensation data and market pay trends; calculating pay rates and job evaluations; designing bonus plans, variable pay, and incentive programs; creating equity compensation programs; developing health/wellness programs; managing benefits and FSAs; designing PTO/leave policies; creating total rewards statements; writing compensation philosophy statements; developing retention strategies .



- **[PE-Analysis](https://github.com/alexwems1/PE-Analysis)**

  Pay equity analysis pipeline with Python-based workflows .



### Additional Strong Open-Source Options



- **Pay Equity Analysis**: **GapVision** (comprehensive platform, AGPL 3.0, full-stack) , **logib** (Swiss official methodology, CRAN, GPL-3) .

- **Compensation Planning**: **afrexai-compensation-planner** (3,729 stars, full framework) , **team-composition-analysis** (startup hiring/equity planning) .

- **Benchmarking**: **FairPay** (agent-based, BLS OEWS data) , **Compshop** (350+ survey directory, MCP server) .

- **Total Rewards**: **Total Rewards Statement Template** (free PDF/CSV) , **hr-compensation-benefits Skill** .



**Frameworks for building custom systems**: Combine **GapVision** for pay equity analysis and visualization, **logib** for rigorous gender pay gap methodology, **afrexai-compensation-planner** for salary band and geographic differential frameworks, **Compshop** for survey discovery, and **Total Rewards Statement Template** for employee communications. Add **PostgreSQL** for persistence and **R** for statistical analysis.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Compensation review platforms handle sensitive employee compensation data; ensure compliance with pay transparency regulations (EU Pay Transparency Directive, US state laws) and data protection requirements.

- **Open-source reality**: The open-source ecosystem for compensation review is **fragmented but useful for specific use cases**. **GapVision** provides a comprehensive pay equity analysis platform with full-stack deployment . **logib** delivers Switzerland's official equal pay methodology as a mature R package . **afrexai-compensation-planner** offers a detailed framework for salary bands and geographic differentials as an AI agent skill . **Compshop** provides survey discovery across 350+ reports . However, **commercial platforms** (Pave, OpenComp, beqom, Workday) provide **integrated merit cycle workflows, real-time market data at scale, and enterprise-grade reporting** that open-source alternatives cannot match without significant assembly and engineering investment. The open-source path is most viable for **pay equity analysis, statistical methodology, or organizations with strong data science capacity**.



---



**Made for HR leaders, compensation analysts, People Operations teams, and pay equity specialists.**

Let's make compensation review more open, transparent, and equitable.
