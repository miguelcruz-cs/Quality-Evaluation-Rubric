# Quality Evaluation Rubric

**QA scoring rubric with behavioral anchors, weighted dimensions, and calibration system**
Case study for [mpascualcruz.com](https://mpascualcruz.com)

---

## Overview

A 10-tab Google Sheets QA operations playbook built for customer support teams. Covers seven scoring dimensions with 1–4 behavioral anchors, channel flags (email, live chat, voice), composite scoring, root cause tagging, dispute process, stakeholder reporting, AI integration, and a training response matrix.

**Full case study →** [miguelcruz-cs.github.io/Quality-Evaluation-Rubric](https://miguelcruz-cs.github.io/Quality-Evaluation-Rubric)

---

## The Artifact

![Quality Evaluation Rubric Scorecard](https://github.com/miguelcruz-cs/Quality-Evaluation-Rubric/blob/main/quality-evaluation-rubric.png?raw=true)

---

## Scoring Dimensions

| Dimension | Weight | Scale | Channel |
|---|---|---|---|
| Greeting / Opening | 0.50 | 7% | Email, Chat, Voice |
| Accuracy | 1.75 | 26% | Email, Chat, Voice |
| Efficiency | 1.50 | 22% | Email, Chat, Voice |
| Empathy & Tone | 1.50 | 22% | Email, Chat, Voice |
| Categorization | 1.00 | 15% | Email, Chat, Voice |
| Process Adherence | 0.25 | 4% | Pass/Fail | Email, Chat, Voice |
| Documentation Quality | 0.25 | 4% | Pass/Fail | Email, Chat, Voice |

**Composite score** = SUMPRODUCT(scores × weights) / SUM(weights), displayed as a percentage.

**Thresholds:** 90–100% Strong Performance · 75–89% Meets Standard · Below 75% Coaching Trigger

---

## Playbook Structure (10 Tabs)

1. **Framework Overview** — Executive summary, three-layer model
2. **Scorecard** *(portfolio screenshot)* — Full rubric with behavioral anchors and channel flags
3. **Root Cause Tagging Reference** — Dimension-level failure tags
4. **Cadence & Sampling Guide** — Evaluation frequency by team size, calibration structure
5. **Dispute & Misalignment Process** — 72-hour dispute window, blind re-review protocol
6. **Stakeholder Reporting Guide** — Team Lead (weekly), Manager (monthly), Leadership (quarterly)
7. **AI Integration Layer** — QA as training input; AutoQA scope and limits
8. **Voice of Customer Integration** — CSAT/NPS correlation matrix
9. **Training Response Matrix** — Pattern thresholds → specific interventions
10. **KB Feedback Loop** — QA failure → knowledge base update triggers

**View the full 10 sheet artifact →** [Google Sheets](https://docs.google.com/spreadsheets/d/1a47JSev0P5-KJnrg6OXglB925rBhOPPfSLM-qFOWAgM/edit?usp=sharing)

---

## Connected Case Studies

| Case Study | Connection |
|---|---|
| CS 3 — Support Onboarding Program | Day 30/60/90 evaluation criteria sourced from this rubric |
| CS 4 — Sona AI Voice Agent | Same rubric dimensions applied to AI agent quality benchmarking |
| CS 5 — Knowledge Management Architecture | Accuracy failures in QA trigger KB review lifecycle |
| CS 1 — Customer Service Flow | Resolution flow maps directly to Empathy, Accuracy, Documentation dimensions |

---

## Tools Used

Google Sheets · CleanShot X · ElevenLabs · GitHub Pages · Claude · Perplexity 

---

*Miguel Cruz · [mpascualcruz.com](https://mpascualcruz.com) · May 2026*
