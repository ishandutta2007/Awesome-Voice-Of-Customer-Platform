# Awesome-Voice-Of-Customer-Platform

# Top Voice of Customer (VoC) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Customer Feedback, Experience Management, Surveys, NPS/CSAT, Text Analytics & Closed-Loop Insights*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Voice of Customer (VoC)**. These tools capture, analyze, and act on customer feedback across surveys, reviews, social, support tickets, speech, and digital channels — enabling experience management (XM), journey insights, sentiment analysis, and closed-loop action.

**Examples** include Medallia, Qualtrics, XM Institute Platform, Forsta (Press Ganey Forsta), Alchemer, SurveyMonkey Enterprise, NICE Satmetrix, QuestionPro CX, Verint Experience Management, and InMoment (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, privacy-first survey/experience management, feedback boards, text analytics, and transparent VoC workflows — ideal for product teams, CX researchers, developers, and organizations that want full data ownership without enterprise lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Medallia](https://www.medallia.com/)**  
  Enterprise experience management platform that unifies direct, indirect, and inferred signals (surveys, speech, video, social, digital, IoT) into Total Experience Profiles for omnichannel VoC and operational action.
- **[Qualtrics](https://www.qualtrics.com/)**  
  Leading Experience Management (XM) platform and Gartner Leader for VoC. Combines sophisticated survey design, Text iQ analytics, journey orchestration, and multi-experience (CX, EX, product, brand) programs.
- **[XM Institute Platform](https://www.qualtrics.com/)** (Qualtrics ecosystem)  
  Research and best-practice resources plus platform capabilities supporting enterprise XM/VoC maturity models and continuous listening programs.
- **[Forsta](https://www.forsta.com/)** (Press Ganey Forsta)  
  Combined research + VoC platform (following InMoment acquisition) focused on customer and employee experience measurement, advanced analytics, and multi-channel feedback programs.
- **[Alchemer](https://www.alchemer.com/)**  
  Flexible mid-market survey and feedback platform known for ease of use, strong support, and evolving capabilities around unified data views, AI automation, and compliance.
- **[SurveyMonkey Enterprise](https://www.surveymonkey.com/)**  
  Scalable survey and VoC solution with advanced collaboration, security, analytics, and integrations suited for enterprise feedback programs.
- **[NICE Satmetrix](https://www.nice.com/)**  
  NPS-centric Voice of Customer platform with benchmarking, closed-loop workflows, and experience measurement tools for customer loyalty programs.
- **[QuestionPro CX](https://www.questionpro.com/)**  
  Affordable enterprise-grade CX and survey platform offering feedback collection, journey analytics, and experience management capabilities.
- **[Verint Experience Management](https://www.verint.com/)**  
  Omnichannel experience management and VoC solution that integrates speech, text, surveys, and operational data for insight-to-action workflows.
- **[InMoment](https://www.inmoment.com/)**  
  Experience intelligence platform combining surveys, reviews, social listening, conversational analytics, and predictive insights (now part of the broader Forsta/Press Ganey ecosystem).

## Open-Source GitHub Projects
- **[Formbricks](https://github.com/formbricks/formbricks)**  
  Leading open-source Qualtrics / Medallia alternative (AGPLv3). Privacy-first experience management platform with in-app, website, link, and email surveys, no-code editor, targeting, templates, integrations (Slack, Notion, Zapier, n8n), and full self-hosting. Strong focus on actionable feedback at every user journey point.
- **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)**  
  Mature, powerful open-source survey platform (long-standing alternative to SurveyMonkey/Qualtrics). Supports unlimited surveys/questions, 30+ question types, complex branching/skip logic, multilingual surveys, templates, and extensive customization. Fully self-hostable.
- **[ABC User Feedback](https://github.com/line/abc-user-feedback)**  
  Standalone open-source VoC application from LINE for gathering, tagging, and organizing customer feedback. Features include customizable tags, Kanban mode, issue tracking, RBAC, dashboards, and AI-powered analysis (summarization, translation, sentiment, issue recommendations). Battle-tested at scale.
- **[Quackback](https://github.com/)** (and similar feedback platforms)  
  Comprehensive open-source customer feedback platform with voting boards, public roadmap, changelogs, AI (duplicate detection, sentiment, summaries), SSO, REST API, and broad integrations (Slack, Linear, Jira, GitHub, Intercom, Zendesk, etc.).
- **[Fider](https://github.com/getfider/fider)**  
  Popular open-source feedback board and idea management tool. Customers submit, vote, and comment on ideas; teams manage status and public roadmaps. Lightweight and self-hostable.
- **[ClearFlask](https://github.com/clearflask/clearflask)** / **[Astuto](https://github.com/astuto/astuto)** / **[LogChimp](https://github.com/logchimp/logchimp)**  
  Feature-rich open-source alternatives for feedback collection, voting, roadmaps, and changelogs with varying levels of complexity and self-hosting support.
- **[Vox](https://github.com/ElliotJLT/vox)**  
  Open-source Voice of Customer research agent. Connects to customer conversations (Gong, Granola, CSV/JSON, etc.) and produces structured, evidence-based research briefs using thematic analysis, Jobs-to-be-Done, and opportunity mapping methodologies.
- **[SurveyJS](https://github.com/surveyjs)**  
  Open-source JavaScript library for building fully customizable surveys, forms, and quizzes that can be embedded or self-hosted as part of larger VoC systems.

### Additional Strong Open-Source Options
- **Feedback boards & idea management tools** (Fider, Astuto, ClearFlask, LogChimp, Refyyn, etc.) for public voting, roadmaps, and changelogs.
- **Self-hosted form/survey builders** such as OpnForm, HeyForm, OhMyForm, Nextcloud Forms, and Yakforms.
- **Text analytics & NLP notebooks** for sentiment analysis, topic modeling, and thematic coding of open-ended feedback.
- **VoC research agents and scripts** that apply structured methodologies (thematic analysis, JTBD) to conversation or survey data.
- Community **integrations with n8n, Zapier alternatives, Slack bots, and BI tools** (Metabase, Grafana, Superset) for closed-loop workflows.
- Many smaller **Python/R analysis packages**, **sentiment libraries**, and **survey response processors** available on GitHub.

**Frameworks for building custom systems**: Combine **Formbricks** or **LimeSurvey** for collection with **ABC User Feedback** / feedback boards for organization, open-source NLP/LLM pipelines for analysis, and workflow tools (n8n, Temporal, Inngest) for closed-loop action. Pair with privacy-focused analytics stacks for full data ownership.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Voice of Customer programs must comply with data privacy, consent, and research ethics regulations (GDPR, CCPA, etc.).
- Self-hosted open-source solutions require proper security, access controls, backup, and operational practices, especially when handling sensitive customer feedback.

---
**Made for CX leaders, product teams, researchers, and developers.**  
Let's make Voice of Customer programs more open, privacy-respecting, and actionable.
