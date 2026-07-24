# SEO OS – Product Requirements Document (PRD)

**Version:** 1.0.0
**Status:** Active
**Owner:** Ahmad
**Project Type:** AI-Powered SEO Operating System
**Last Updated:** July 2026

---

# 1. Project Vision

SEO OS is a production-ready AI-powered SEO Operating System designed to automate and improve every major aspect of modern SEO.

Unlike traditional SEO tools that only report data, SEO OS collects data from multiple sources, analyzes it using AI, compares it against competitors, and generates prioritized, evidence-based recommendations.

The system is designed to work for any website and should become a reusable platform for client projects as well as internal websites.

---

# 2. Mission

Build an intelligent SEO platform that answers:

- Why isn't this page ranking?
- What exactly is missing?
- Which competitors are outperforming us?
- What should be improved first?
- What is the estimated SEO impact?
- What is the estimated AI Search impact?
- How can the website become the authority in its niche?

Instead of displaying raw metrics, SEO OS should generate actionable decisions.

---

# 3. Objectives

The system must:

- Automate repetitive SEO tasks.
- Continuously monitor website health.
- Compare pages against competitors.
- Detect ranking opportunities.
- Improve Local SEO.
- Improve Technical SEO.
- Improve Content SEO.
- Improve E-E-A-T.
- Improve AEO (Answer Engine Optimization).
- Improve GEO (Generative Engine Optimization).
- Improve authority and trust.
- Generate prioritized recommendations.

---

# 4. Project Scope

SEO OS Version 1 includes:

- Website Discovery
- Website Crawling
- Technical SEO Audits
- Content Audits
- Search Console Integration
- Google Analytics 4 Integration
- Microsoft Clarity Integration
- Competitor Analysis
- Keyword Analysis
- Entity Analysis
- Internal Link Analysis
- Schema Analysis
- AI Recommendation Engine
- Reporting Dashboard

---

# 5. Out of Scope (Version 1)

The following are NOT included in Version 1:

- Automatic content publishing
- Automatic backlink creation
- Automatic keyword tracking using paid APIs
- CRM
- Billing
- Client Portal
- White-label features

These may be added in future versions.

---

# 6. Target Users

Primary Users:

- SEO Professionals
- Local SEO Agencies
- Website Owners
- Marketing Teams

Secondary Users:

- Content Writers
- Developers
- Business Owners

---

# 7. Technology Stack

Core Platform

- n8n
- Supabase
- PostgreSQL

AI

- Claude
- OpenAI

Google APIs

- Search Console API
- Google Analytics 4 API
- PageSpeed Insights API

Other Integrations

- Microsoft Clarity
- Google Business Profile (Future)
- Website Crawler

Version Control

- GitHub

---

# 8. Architecture

Architecture Style:

Microservices

Rules:

- One workflow = One responsibility
- Reusable workflows
- Modular design
- Independent execution
- Scalable architecture
- Error isolation
- API-first approach

---

# 9. Core Modules

001 Project Management

002 Website Discovery

003 Website Crawler

004 Search Console Integration

005 Google Analytics Integration

006 Microsoft Clarity Integration

007 Competitor Discovery

008 Competitor Crawler

009 Technical SEO Engine

010 Content SEO Engine

011 Local SEO Engine

012 Keyword Engine

013 Entity Engine

014 Internal Linking Engine

015 Schema Engine

016 Authority Engine

017 AI Recommendation Engine

018 Reporting Engine

019 Notification Engine

020 Dashboard

---

# 10. Workflow Standards

Every workflow must:

- Have one responsibility only.
- Be reusable.
- Be modular.
- Include error handling.
- Include retry logic where appropriate.
- Log execution.
- Use environment variables.
- Be production-ready.
- Be fully documented.

No workflow should depend directly on another workflow unless explicitly defined.

---

# 11. Database Standards

The database must:

- Support multiple projects.
- Use UUID primary keys.
- Use foreign keys.
- Be normalized.
- Support millions of rows.
- Include created_at and updated_at timestamps.
- Be optimized for indexing.

---

# 12. AI Standards

AI should NEVER guess.

AI recommendations must be based on collected data.

Every recommendation should include:

- Problem
- Evidence
- Recommendation
- Expected Impact
- Priority
- Confidence Score

The AI must distinguish between:

- Confirmed facts
- Industry best practices
- AI-generated assumptions

---

# 13. Development Rules

- Never build large monolithic workflows.
- Build one module at a time.
- Test every workflow before building the next.
- Reuse existing workflows whenever possible.
- Do not duplicate logic.
- Maintain backward compatibility.
- Document every workflow.

---

# 14. Naming Conventions

Workflow Names

001 - Website Discovery

002 - Website Crawler

003 - Search Console Import

004 - GA4 Import

005 - Clarity Import

006 - Competitor Discovery

007 - Competitor Crawl

008 - Technical Audit

009 - Content Audit

010 - Local SEO Audit

011 - AI Recommendation Engine

012 - Reporting

Table Names

projects

pages

crawl_jobs

search_console

analytics

clarity

competitors

keywords

entities

recommendations

tasks

reports

---

# 15. Success Metrics

The project is considered successful when it can:

- Crawl any website.
- Store structured SEO data.
- Analyze technical SEO.
- Analyze content quality.
- Compare against competitors.
- Generate AI recommendations.
- Produce actionable reports.
- Scale to multiple websites.

---

# 16. Long-Term Vision

SEO OS should evolve into a complete AI SEO platform capable of:

- Acting as an AI SEO Consultant
- Detecting ranking issues automatically
- Predicting ranking opportunities
- Improving AI search visibility
- Monitoring Local SEO performance
- Providing daily SEO action plans
- Supporting agencies managing multiple clients

The long-term goal is to create a reusable, production-grade SEO platform that combines data engineering, automation, AI analysis, and decision support into a single operating system.
