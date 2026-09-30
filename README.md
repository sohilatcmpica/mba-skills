# mba-skills

# MBA AI Skills Library

> **Practical AI skills, workflows, and prompts for MBA students and business professionals.**

This repository is a growing collection of reusable **AI Skills and practical prompts** designed to help MBA students learn how to use AI for real-world business tasks.

The goal is not simply to teach students how to "prompt AI."

The goal is to teach them how to build **repeatable AI-powered business workflows**.

---

## 🎯 Why This Repository?

MBA students regularly work on tasks such as:

* Marketing campaigns
* Market research
* Business analysis
* Competitor analysis
* Customer segmentation
* SWOT analysis
* Business plans
* Financial analysis
* Product strategy
* Sales planning
* Presentation preparation
* Case-study analysis
* Operations planning
* HR analysis
* Strategic decision-making

Many of these tasks are repeated with different business situations.

Instead of writing a long prompt every time, an AI **Skill** can define a reusable methodology for completing the task.

This repository provides those reusable workflows.

---

# 🧠 What Is an AI Skill?

An AI Skill is a reusable set of instructions that teaches an AI agent **how to perform a particular type of task consistently**.

A simple way to understand it:

| Concept           | Meaning                                     |
| ----------------- | ------------------------------------------- |
| **Prompt**        | What you want the AI to do now              |
| **Skill**         | How the AI should perform this type of task |
| **Input**         | Information provided for the task           |
| **Workflow**      | Steps the AI follows                        |
| **Rules**         | Things the AI must and must not do          |
| **Output**        | Structure of the final result               |
| **Quality Check** | How the AI validates its own work           |

### Simple analogy

Think of a restaurant:

**Chef → AI Agent**

**Recipe → AI Skill**

**Ingredients → User Input**

**Dish → Final Output**

A prompt might say:

> "Create a marketing campaign for HealthyBite."

The Skill defines the methodology:

> Understand the product → analyze audience → define objective → develop strategy → select channels → create content → allocate budget → define KPIs → optimize → validate.

This makes the workflow reusable.

---

# 🏗️ Repository Philosophy

The repository follows a simple principle:

> **Prompt once. Build the methodology. Reuse many times.**

A good Skill should:

1. Have a clear purpose.
2. Have a clear trigger/use case.
3. Define required inputs.
4. Follow a logical workflow.
5. Make decision rules explicit.
6. Avoid unsupported assumptions.
7. Produce a consistent output structure.
8. Include quality checks.
9. Be practical enough for real business use.
10. Be reusable across different business cases.

---

# 📁 Repository Structure

The repository is designed to grow as more MBA Skills are created.

```text
mba-ai-skills/
│
├── README.md
│
├── skills/
│   │
│   ├── marketing-campaign/
│   │   ├── SKILL.md
│   │   ├── prompts/
│   │   │   ├── basic.md
│   │   │   └── example-healthybite.md
│   │   ├── references/
│   │   └── assets/
│   │
│   ├── market-research/
│   │   └── SKILL.md
│   │
│   ├── competitor-analysis/
│   │   └── SKILL.md
│   │
│   ├── customer-segmentation/
│   │   └── SKILL.md
│   │
│   ├── swot-analysis/
│   │   └── SKILL.md
│   │
│   ├── business-plan/
│   │   └── SKILL.md
│   │
│   ├── product-strategy/
│   │   └── SKILL.md
│   │
│   ├── sales-strategy/
│   │   └── SKILL.md
│   │
│   ├── financial-analysis/
│   │   └── SKILL.md
│   │
│   ├── case-study-analysis/
│   │   └── SKILL.md
│   │
│   ├── presentation-planning/
│   │   └── SKILL.md
│   │
│   ├── strategic-analysis/
│   │   └── SKILL.md
│   │
│   └── ...future-skills
│
├── prompts/
│   ├── marketing/
│   ├── strategy/
│   ├── finance/
│   ├── operations/
│   ├── hr/
│   └── general/
│
├── examples/
│   ├── marketing-campaign/
│   ├── market-research/
│   └── ...
│
├── CONTRIBUTING.md
├── LICENSE
└── CHANGELOG.md
```

The exact supporting folders can be added only when a Skill needs them. A basic Skill only requires its `SKILL.md`.

OpenAI's current Skills documentation similarly defines `SKILL.md` as the required manifest/instruction file and recommends `references/`, `scripts/`, and `assets/` for supporting material when needed.

---

# 📚 Current Skills

## 1. Marketing Campaign

**Status:** ✅ Available

**Location:**

```text
skills/marketing-campaign/SKILL.md
```

### Purpose

Create a complete, structured, measurable, and executable marketing campaign.

### Workflow

```text
Product
   ↓
Audience
   ↓
Market
   ↓
Objective
   ↓
Strategy
   ↓
Campaign Concept
   ↓
Content
   ↓
Channels
   ↓
Budget
   ↓
Timeline
   ↓
Execution
   ↓
CTA
   ↓
KPIs
   ↓
Measurement
   ↓
Optimization
   ↓
Quality Check
```

### Example use case

```text
Product:
HealthyBite

Product Type:
Ready-to-eat healthy snack

Target Audience:
Working professionals age
```
