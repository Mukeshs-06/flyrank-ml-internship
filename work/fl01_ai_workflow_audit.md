# FL-01 — AI Workflow Audit and Tool Setup

**Track:** General AI Fluency  
**Phase:** Onboarding / Setup  
**Date:** July 2026  

---

## 1. Recurring Weekly Task Classification Audit

This workflow audit maps 12 recurring tasks from my machine learning study, research, and coding routine. Tasks are classified based on Ethan Mollick's task-delegation framework (*Just Me*, *Delegate with Review*, *Collaborate*, or *Fully Automate*).

| # | Recurring Task | Classification | Rationale & Delegation Boundary |
|---|---|---|---|
| 1 | **Writing core mathematical loss functions & logic** | **Just me** | Requires deep first-principles intuition and mathematical ownership; delegating risks subtle edge-case errors that undermine learning. |
| 2 | **Strategic decision-making & final trade-off choices** | **Just me** | Choosing project direction and evaluation criteria requires personal judgment and domain accountability that cannot be outsourced. |
| 3 | **Debugging Python tracebacks in pandas/DuckDB pipelines** | **Collaborate with AI** | I provide error logs and context; AI suggests potential causes, syntax fixes, or edge-case handling. |
| 4 | **Refactoring messy notebook code into modular `ml_utils.py`** | **Collaborate with AI** | I define module boundaries and function signatures; AI drafts clean PEP 8 refactored implementations. |
| 5 | **Checking feature leakage in data preprocessing pipelines** | **Collaborate with AI** | I outline temporal boundaries; AI assists in auditing feature timestamps and column derivation logic. |
| 6 | **Drafting initial EDA plotting scripts (matplotlib/seaborn)** | **Delegate to AI with review** | AI generates standard boilerplate visualization scripts, which I inspect and tweak for clarity and labels. |
| 7 | **Summarizing complex ML documentation & data dictionaries** | **Delegate to AI with review** | AI extracts key schemas and constraints into executive summaries, which I verify against official documentation. |
| 8 | **Writing function docstrings & inline unit test boilerplate** | **Delegate to AI with review** | AI auto-generates NumPy-style docstrings and test cases, which I review for completeness and accuracy. |
| 9 | **Drafting weekly internship progress reports & commit messages** | **Delegate to AI with review** | AI drafts bulleted summaries from git logs, which I refine for professional tone and exact metrics. |
| 10 | **Formatting Markdown tables and reference lists** | **Fully automate** | Deterministic formatting tasks are best handled automatically by AI/linters without human manual effort. |
| 11 | **Converting raw data dictionaries into JSON/YAML schemas** | **Fully automate** | Structural data conversions follow fixed rules and can be safely automated end-to-end. |
| 12 | **Generating starter skeleton templates for new assignment reports** | **Fully automate** | Creating standardized skeleton files with pre-filled headers and checklist metadata requires zero creative intervention. |

---

## 2. Tool Stack & Academy Enrollment Evidence

### Account Setup Status
- **ChatGPT (Free Tier):** Account active and configured for quick ideation and general syntax checks.
- **Claude (Free Tier):** Account active, configured with dedicated project instructions for machine learning workflows.
- **Anthropic Academy:** Registered account verified.

### Course Enrollment Evidence
- **Course:** *AI Fluency: Framework & Foundations* (Anthropic Academy)
- **Status:** Enrolled & Module 1 (*Collaborating with AI Effectively & Safely*) Completed.
- **Key Takeaway:** AI is an operational multiplier when used with human-in-the-loop validation; task delegation requires clear boundaries based on error cost and domain risk.

---

## 3. Claude Project Configuration

### Project Details
- **Project Name:** `FlyRank ML Internship Assistant`
- **Custom System Instructions:**

> You are acting as my technical AI pair-programmer and research mentor for the FlyRank Machine Learning Internship.
>
> **Who I am:** Machine Learning Intern working on search intelligence, content decay modeling, and ranking optimization.
>
> **Tone & Communication Preferences:**
> - Keep explanations concise, structured, and beginner-friendly.
> - Use careful, rigorous scientific language (*"observed"*, *"suggests"*, *"may indicate"*, *"within this dataset"*).
> - Never invent numbers, metrics, or dataset values—always rely on actual output logs provided.
> - Explain the reasoning behind code changes before writing or modifying code.
>
> **Current Goals:**
> - Build transparent, honest machine learning models to detect content decay.
> - Maintain strict data safety and feature leakage checks.
> - Produce clear, actionable content refresh priority queues.

---

## 4. Target Tasks for FL-02 through FL-04 & Success Metrics

The following three tasks from the audit matrix have been selected for iterative optimization during assignments **FL-02**, **FL-03**, and **FL-04**:

### Target Task 1: Drafting Initial EDA & Visualization Code (FL-02)
- **Task Description:** Using AI to generate initial exploratory data analysis plots (histograms, trend lines, correlation matrices) from structured dataset schemas.
- **"Done Well" Success Metric:** 
  - Generated Python script runs without syntax errors on the first execution.
  - All plots include proper title tags, labeled axes, and readable legends.
  - Reduces boilerplate visualization setup time from 20 minutes to under 3 minutes.

### Target Task 2: Technical Documentation Summarization (FL-03)
- **Task Description:** Utilizing AI to summarize multi-page dataset guides, data dictionaries, and technical specifications into concise operational cheat-sheets.
- **"Done Well" Success Metric:**
  - Summary accurately captures all column data types, gotchas (e.g., rate scaling x100), and missingness patterns with zero hallucinations.
  - Condenses 10+ pages of documentation into a 1-page structured reference card.

### Target Task 3: Code Refactoring into Modular Utilities (FL-04)
- **Task Description:** Collaborating with AI to refactor ad-hoc exploratory notebook code into reusable functions inside `scripts/ml_utils.py`.
- **"Done Well" Success Metric:**
  - Refactored functions adhere to strict PEP 8 formatting and include complete docstrings with type hints.
  - Code passes unit testing with zero regressions and eliminates duplicated logic across notebooks.

---

## 5. Verification Checklist

- [x] 12 recurring tasks listed with clear one-line rationales
- [x] At least two tasks explicitly marked **"Just me"** with domain justification
- [x] Tool setup & Anthropic Academy enrollment documented
- [x] Claude Project custom system instructions defined
- [x] 3 specific target tasks chosen for FL-02 to FL-04 with measurable success metrics
