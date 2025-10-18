# Learn Agentic AI:Low-Code to Code
*Build production-grade agents with OpenAI AgentKit*

This Free Course is Offered by: [Panaversity](https://panaversity.org/)

**Register in this Free Panaversity Course:** [Click to Register](https://panaversity.org/flagship-program/courses/AI-100)

**Live YouTube Classes [@panaversity channel](https://www.youtube.com/@panaversity) on Wednesday and Thursday and 8:00 pm - 10:00 pm:** Class starting from Oct 15, 2025. Recording Also Available on [@Panaversity YouTube Channel](https://www.youtube.com/@panaversity)

**[YouTube Recording Playlist](https://www.youtube.com/playlist?list=PLY-fvIYzjXhcRku9CQnMKSWPQpRhEPqy_)**

**All-Pakistan and All-Star Faculty:**
Qasim (Karachi), Ameen (Saudi Arabia), Wania (Wah Cantt.), Junaid (Lahore), Aneeq (Karachi), Hammad (Peshawar), Rehan (Islamabad) and Zia (Karachi).


Here’s a practical, non-coding syllabus which we are running as a 5-week cohort (8 x 2–3h sessions) or we will also offer it as a 2-day intensive in Companies and Universities. It stays hands-on with AgentKit’s visual tools—no programming required.

## No-Code Agents with OpenAI AgentKit — Course Syllabus

## Course overview

Build, test, and ship a production-ready AI agent using OpenAI’s new AgentKit—focusing on the visual Agent Builder, governance & guardrails, built-in evals, and one-click chat UI embedding with ChatKit. By the end, learners publish a working agent and a simple plan to measure impact and iterate. ([OpenAI][1])

### Who it’s for

Non-programmers (general managers, accountants, engineers, doctors, financial managers, product managers, ops, Customer Experience (CX), Human Resources / Learning & Development (HR/L&D), consultants, educators, everyone) who can define workflows and business outcomes, but don’t want to write code.

### What you’ll build

A capstone agent of your choice—for example:

* Customer support triage & answer bot
* Research & brief generator for sales/BD
* Internal knowledge assistant (policies/SOPs)
* Classroom co-teacher / onboarding guide

---

## Learning outcomes

By the end, participants can:

1. Understand the concepts of Agentic Web and Agentic Organizations
2. Describe core agent concepts (agents, tools, handoffs, sessions, guardrails) in plain language and map them to business workflows. ([OpenAI GitHub][2])
3. Use **Agent Builder** to design multi-step workflows on a visual canvas, version them, and add approvals/guardrails without code. ([OpenAI][1])
4. Connect knowledge safely (files/connectors) and set up the **Connector Registry** with admins. ([OpenAI][1])
5. Deploy a branded chat experience with **ChatKit** and share it with test users. ([OpenAI][3])
6. Measure and improve quality with **Evals** (datasets, trace grading, prompt optimization), and understand when to consider reinforcement fine-tuning. ([OpenAI][1])
7. Apply **Guardrails** for safety (PII masking, jailbreak detection, hallucination checks) using the wizard and presets. ([OpenAI GitHub][4])

---

## Format & pacing

* **6 weeks** · **2 sessions/week** · **2–3 hours/session** (+ extra Question/Answer Sessions)
* **Alt**: **2-day bootcamp** covering the same modules with condensed labs to be offered in Companies and Universities
* Delivery: live workshop or flipped classroom (short videos + guided labs)

---

## Detailed Schedule

### Week 1 — Agentic Web and Organizations 

**Session 1: [Agentic Web](./00_agentic_web/readme.md) (2h)**

**Session 2: [Agentic Organizations](./01_agentic_org/readme.md) (2h)**

### Week 2 — Foundations & first workflow

**Session 1: [What is an “agent” (no code)?](./03_no_code_agents/readme.md) (2h)**

* The AgentKit stack at a glance: Agent Builder (visual), Connector Registry (admin), ChatKit (UI), Evals (quality), Guardrails (safety).
* Concepts in human terms: tasks, tools, multi-step flows, agent handoffs, memory/sessions.
* Demo tour of Agent Builder: canvases, nodes, versions, templates; publish/preview lifecycle.
  
  **Lab:** Clone a template, customize instructions, add an approval step, run test conversations. ([OpenAI][1])

**Session 2: Connecting knowledge safely (2–3h)**

* What to put in vs. link to; file search basics; connector options (e.g., Drive, SharePoint, Teams) and MCP servers.
* Admin view of **Connector Registry**; roles & governance; enabling connectors for a workspace.
* Data handling patterns: least-privilege, redaction, auditability.
  
  **Lab:** Attach a small policy pack (PDFs/Docs), configure retrieval, and test relevance safely. ([OpenAI][1])

### Week 3 — Designing, deploying, and branding the chat UI

**Session 3: Visual design patterns (2–3h)**

* Drag-and-drop nodes: tools, file search, guardrails, decision/branching, human-in-the-loop.
* Multi-agent patterns via handoffs—when and why to split responsibilities.
* Versioning & change logs; rollback and safe launches.
  
  **Lab:** Build a 5–7 node workflow from a blank canvas; add a human approval and a fallback path. ([OpenAI][1])

**Session 4: Deploy with ChatKit (2h)**

* Shipping a usable interface without front-end work: embed options and theme/brand tweaks.
* Sharing with pilot users; capturing transcripts and feedback for iteration.
  
  **Lab:** Deploy your agent’s chat UI, set a custom name/avatar, and invite 3 pilot testers. ([OpenAI][3])

### Week 4 — Quality: evaluate, observe, and iterate

**Session 5: Evals you’ll actually use (2–3h)**

* Designing a simple eval dataset from real tickets/prompts.
* **Trace grading**: grading whole runs to spot brittle steps.
* **Prompt optimization**: generate improved prompts from grader + human annotations.
* Third-party model comparisons (what, why, when).
  
  **Lab:** Create a 20-case eval, run it, and apply one optimization round. Re-run and compare. ([OpenAI][1])

**Session 6: Observability & cost control (2h)**

* Reading traces; identifying tool-call loops and dead ends.
* Lightweight A/Bs: instruction tweaks and guardrail thresholds.
* When RFT helps (conceptual only) and how to scope an RFT request with your tech team.
  
  **Lab:** Use traces to remove one redundant step and reduce tokens/time per task. ([OpenAI][1])

### Week 5 — Safety, governance, and capstone

**Session 7: Guardrails & governance (2–3h)**

* The **Guardrails Wizard**: select checks (moderation, jailbreak, PII, hallucinations) and set policies—no code.
* Human approvals & audit trails; rollout controls and change management.
  
  **Lab:** Add PII masking + jailbreak detection to your agent, document your policy, and re-test. ([OpenAI GitHub][4])

**Session 8: Capstone build & publish (2–3h)**

* Finalize workflow, run evals, harden guardrails, and polish the ChatKit UI.
* Write a one-page “launch note”: scope, metrics, SLAs, rollback plan.
  
  **Capstone demo:** 5-minute live run + Q&A; submit your Launch Note and a 14-day iteration plan.

---

## Assessments & deliverables

* **Checkpoints (30%)**: Session labs (Builder, connectors, evals, guardrails).
* **Capstone (50%)**: Working agent, embedded chat UI, eval results, safety config.
* **Launch Note (20%)**: Clear goals, success metrics, and iteration plan.

---

## Tools & accounts (no coding needed)

* **Agent Builder** (visual canvas, versioning, preview/publish)
* **Connector Registry** (admin-managed app & data connections across orgs)
* **ChatKit** (embedded chat UI with branding controls)
* **Evals** (datasets, trace grading, prompt optimization, optional third-party models)
* **Guardrails** (wizard + presets for PII/jailbreak/hallucination checks)
  Availability: as of **Oct 6–8, 2025**, Agent Builder is in beta; ChatKit and new Evals features are generally available; Connector Registry is rolling out in beta via the Global Admin Console. All are included under standard API model pricing. ([OpenAI][1])

---

## Instructor prep & room setup

* Learners need: laptop, browser, sample documents (FAQs, policies, SOPs), and access granted to AgentKit features in your org.
* Create an org sandbox + test connectors; prepare three Builder templates per track (support, research, internal knowledge).

---

## Optional 2-day bootcamp agenda (condensed) to be offered in Universities and Companies

**Day 1 AM:** Foundations + first workflow (Sessions 1–3)
**Day 1 PM:** Data connections + ChatKit deploy (Session 4)
**Day 2 AM:** Evals + optimization (Sessions 5–6)
**Day 2 PM:** Guardrails + capstone launch (Sessions 7–8)


---

## Four learning levels

After completing this course (Level 1) you will be at Learning Level 1, after that you will be ready for Levels 2, 3, and 4.

* **Learning Level 1: No-Code Agent Development** — build end-to-end in AgentKit (This Course)
* **Learning Level 2: Code-First Chat GPT Apps SDK** — [Learn Python](https://github.com/panaversity/learn-modern-ai-python/tree/main/00_python_colab) and start in Apps SDK, then import visual flows where helpful (This course will be offered by Panaversity later). 
* **Learning Level 3: Full-Code Agents SDK** - [Learn Agentic AI using OpenAI Agents SDK and MCP](https://github.com/panaversity/learn-agentic-ai)
* **Learning Level 4: Full-Code AI Assisted: Spec-Driven Vibe-Coding** - [Spec-Kit Plus](https://github.com/panaversity/spec-kit-plus)


---


### References

* OpenAI **Introducing AgentKit** (features, availability, pricing). ([OpenAI][1])
* OpenAI **Agent platform overview** (Builder, ChatKit, Evals). ([OpenAI][3])
* **Agents SDK** docs (background on agents/handoffs/guardrails—used conceptually here). ([OpenAI GitHub][2])
* **Guardrails** docs (wizard & presets). ([OpenAI GitHub][4])
* Launch coverage & context. ([TechCrunch][5])

If you want, I can tailor this to a specific audience (e.g., support orgs, schools, or consulting firms) and pre-fill the Builder templates for that track.

[1]: https://openai.com/index/introducing-agentkit/ "Introducing AgentKit | OpenAI"
[2]: https://openai.github.io/openai-agents-python/ "OpenAI Agents SDK"
[3]: https://openai.com/agent-platform/ "API Agents | OpenAI"
[4]: https://openai.github.io/openai-guardrails-python/ "OpenAI Guardrails Python"
[5]: https://techcrunch.com/2025/10/06/openai-launches-agentkit-to-help-developers-build-and-ship-ai-agents/?utm_source=chatgpt.com "OpenAI launches AgentKit to help developers build and ship AI agents"


