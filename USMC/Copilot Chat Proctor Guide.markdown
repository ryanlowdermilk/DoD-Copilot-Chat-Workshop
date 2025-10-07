# USMC Copilot Chat Hands-On Lab: Proctor Guide
## 6 Copilot Capabilities Across Real-World Marine Corps Scenarios

**Version:** October 07, 2025  
**Classification:** UNCLASSIFIED  
**Duration:** 3 hours (6 scenarios × 20-25 min each)

---

## Table of Contents

- [Lab Overview](#lab-overview)
- [Prerequisites & Setup](#prerequisites--setup)
- [Scenario Modules](#scenario-modules)
  - [Scenario 1: Language Understanding & Generation](#scenario-1-language-understanding--generation)
  - [Scenario 2: Reasoning & Decision Support](#scenario-2-reasoning--decision-support)
  - [Scenario 3: Data Analysis & Visualization](#scenario-3-data-analysis--visualization)
  - [Scenario 4: Automation & Orchestration](#scenario-4-automation--orchestration)
  - [Scenario 5: Search & Retrieval](#scenario-5-search--retrieval)
  - [Scenario 6: Personalization & Context Awareness](#scenario-6-personalization--context-awareness)
- [Quick Reference](#quick-reference)

---

## Lab Overview

This guide provides proctors with the structure and technical steps to facilitate a hands-on lab for US Marine Corps personnel on using standalone Copilot Chat. The lab demonstrates six independent scenarios, each highlighting a unique Copilot capability in authentic "in garrison" contexts at USMC installations like Camp Lejeune, Camp Pendleton, or Quantico.

### Training Objectives
- Demonstrate how to use standalone Copilot Chat to enhance productivity in Microsoft 365 applications without integrated features or web grounding.
- Build skills in progressive prompt building, meta-prompting, and chain of reasoning for effective Copilot interactions.
- Apply Copilot capabilities to real-world USMC tasks relevant to both Doer (E1-E4, O1-O2) and Manager (E5-E7, O3-O4) personas.
- Ensure participants can copy/paste between Copilot Chat and M365 apps in a secure DoD environment.

### Target Audience Description
- **Personas:** Doers (junior Marines and officers performing tactical tasks) and Managers (NCOs and mid-grade officers overseeing operations).
- **Skill Level:** L100-L200 (beginner to intermediate familiarity with M365 apps and basic prompting).
- **Environment:** In garrison at USMC bases, focusing on administrative, operational, and logistical duties.

### Lab Structure
The lab consists of six independent scenarios, each 20-25 minutes, allowing flexibility for breaks or Q&A. Scenarios do not build on each other and can be reordered if needed.

### Facilitation Approach
- Guide participants through technical steps without scripts.
- Emphasize hands-on practice with progressive prompts.
- Monitor for compliance with standalone Copilot Chat usage (no in-app integrations).
- Encourage discussion on meta-prompting and chain of reasoning.

### Required Materials/Setup
- Laptops with Microsoft 365 E5 licenses (DoD-compliant).
- Access to standalone Copilot Chat via web browser or app.
- Sample data files (e.g., mock emails, spreadsheets) pre-loaded in M365 apps.
- Projector for demonstrating steps.

### Timing Breakdown
- Introduction: 10 minutes
- Each Scenario: 20-25 minutes (setup 2 min, hands-on 15 min, discussion 5 min)
- Breaks: 10 minutes total
- Wrap-up: 10 minutes
⏱️ **Total:** 3 hours

---

## Prerequisites & Setup

### For Proctor
- Verify DoD  environment: Standalone Copilot Chat enabled, no web grounding or M365 Copilot integrations.
- Prepare sample datasets: Mock USMC documents (e.g., emails, OPORD templates, spreadsheets) compliant with UNCLASSIFIED handling.
- Test workflows: Copy/paste between Copilot Chat and M365 apps.
- Setup attendee accounts: Ensure E1-O4 personnel have access to required apps.

### Technical Environment Verification
- Confirm offline functionality: Copilot Chat operates without internet search.
- Check app versions: Outlook, Word, Excel, Power Automate, Power BI, Teams (latest DoD-approved).
- Validate security: All activities in NIPRNet or equivalent.

### Required Attendee Access/Accounts
- Microsoft 365 accounts with Copilot Chat access.
- Permissions for M365 apps in scenarios.

### Pre-Work Attendees Should Complete
- Review basic Copilot Chat interface (5-10 min tutorial).
- Familiarize with M365 apps used in scenarios.

### Expected Baseline Knowledge for Attendees
- Basic navigation in M365 apps.
- Understanding of USMC staff sections (S-1 through S-6).
- Familiarity with ranks and terminology (e.g., FITREP, OPORD, INTSUM).

---

## Scenario Modules

### Scenario 1: Language Understanding & Generation
**Application:** Outlook | **USMC Focus:** S-1 (Administration/Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Camp Lejeune, a Lance Corporal (E-3) processes quarterly award nominations, while a Staff Sergeant (E-6) oversees submissions. Use Copilot to handle email correspondence on awards, FITREPs, and leave authorizations. This demonstrates efficient communication in garrison admin tasks.

#### Copilot Capability Focus
- Primary: Language Understanding & Generation for summarization and drafting.
- Sub-capabilities: Tone adjustment, content rewriting, action item extraction.
- Application to USMC: Streamlines personnel actions, ensuring professional military tone aligned with chain of command.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this email thread about award nominations.
```
- What this prompt does: Provides a simple overview of the thread.
- Output example: A short paragraph listing key points.
- Limitations: Lacks USMC context, may miss deadlines or ranks.

##### Iteration 2: Add Context
```
Summarize this email thread about quarterly award nominations for Marines at Camp Lejeune, including ranks and deadlines.
```
- How context improves output: Incorporates USMC specifics like ranks (e.g., E-3 to O-2), making it relevant.
- Comparison to iteration 1: More detailed, identifies action items like submission deadlines.

##### Iteration 3: Add Specificity
```
Summarize this email thread about quarterly award nominations in a structured format: Key participants (with ranks), main action items, deadlines, and draft a response email to the company commander using professional military tone.
```
- Why specificity matters: Ensures formatted output for easy pasting into Outlook.
- Improved output quality: Includes bullet points and a drafted response.

##### Iteration 4: Final Optimized Prompt
```
As an S-1 clerk at Camp Lejeune, summarize this email thread on award nominations: List participants by rank, extract action items and deadlines, then draft a response email to the CO with formal USMC language, ensuring compliance with MCO 1650.19.
```
- Final refinements: Adds regulatory reference for authenticity.
- Complete output example: Structured list plus full email draft.

#### Technical Steps
1. Open Outlook and select a sample email thread on award nominations.
2. Copy the thread content and paste into standalone Copilot Chat.
3. Enter progressive prompts (iterations 1-4) one by one, observing improvements.
4. Copy Copilot's output (summary and draft) back to Outlook to create a new email.
5. Verify tone adjustment for junior vs. senior ranks.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for copy/paste errors between windows.
> - Checkpoint: Ask participants to share one improved action item.
> - Troubleshooting: If output is vague, remind to add USMC context.
> - Explain benefits: Progressive prompts reduce revisions in admin workflows.

#### Expected Outcomes
- ✅ Deliverable: Summarized thread and drafted email in Outlook.
- ✅ Verification: Output matches USMC tone and includes deadlines.
- ✅ Capability demonstration: Clear language generation for personnel correspondence.
- ✅ Prompt building: Participants iterate prompts 3-4 times.

#### Discussion Points

**Meta-Prompting**
- Enhance by asking Copilot to refine prompts: "Help me create an effective prompt to summarize award emails. What USMC details should I include?"
- Valuable when starting complex tasks like FITREP processing.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Identify key emails, 2) Extract ranks and actions, 3) Generate summary, 4) Draft response."
- Improves quality for detailed personnel reports.

**When to Use**
- Use complex prompts for high-stakes comms like promotion warrants.
- Trade-offs: Simple prompts for quick tasks; complex for accuracy in S-1 duties.
- Real-world: Drafting leave authorizations or ceremony invites.

---

### Scenario 2: Reasoning & Decision Support
**Application:** Word | **USMC Focus:** S-3 (Operations) | **Duration:** 20-25 min

#### Scenario Context
At Camp Pendleton, a Sergeant (E-5) drafts training schedules, while a Captain (O-3) reviews OPORDs. Use Copilot to structure documents and resolve conflicts in garrison operations planning.

#### Copilot Capability Focus
- Primary: Reasoning & Decision Support for analysis and recommendations.
- Sub-capabilities: Conflict identification, priority frameworks, comparative options.
- Application to USMC: Aids in efficient training coordination, ensuring readiness per T&R manual.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Draft a training schedule for a battalion.
```
- What this prompt does: Generates a generic outline.
- Output example: Basic calendar layout.
- Limitations: Ignores USMC specifics like range availability.

##### Iteration 2: Add Context
```
Draft a battalion training schedule at Camp Pendleton, including rifle range and PT sessions for E1-O4 personnel.
```
- How context improves output: Adds location and rank relevance.
- Comparison to iteration 1: Includes realistic events like marksmanship quals.

##### Iteration 3: Add Specificity
```
Draft a battalion training schedule in OPORD format: Include sections for situation, mission, execution; analyze potential scheduling conflicts; recommend adjustments for resource allocation.
```
- Why specificity matters: Structures output per USMC standards.
- Improved output quality: Provides reasoned recommendations.

##### Iteration 4: Final Optimized Prompt
```
As an S-3 planner at Camp Pendleton, draft a training OPORD: Structure with 5-paragraph format, analyze conflicts in range requests and manpower, recommend priorities based on T&R manual, and suggest risk mitigations.
```
- Final refinements: Incorporates doctrinal references.
- Complete output example: Full OPORD with decision framework.

#### Technical Steps
1. Open Word and create a new document for the OPORD.
2. Paste sample training data (e.g., event list) into Copilot Chat.
3. Input progressive prompts, refining based on outputs.
4. Copy recommendations and structure back to Word.
5. Edit for final formatting, demonstrating reasoning application.

#### Facilitation Notes
> 💡 **Tips:**
> - Monitor for prompt overload; break into steps.
> - Checkpoint: Verify conflict analysis in output.
> - Troubleshooting: If recommendations are off, add more data.
> - Explain benefits: Builds logical decision-making in ops planning.

#### Expected Outcomes
- ✅ Deliverable: Structured OPORD in Word with recommendations.
- ✅ Verification: Includes conflict resolutions and priorities.
- ✅ Capability demonstration: Reasoning for operational decisions.
- ✅ Prompt building: 3-4 iterations showing progressive logic.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to analyze training conflicts. What S-3 details to include?"
- Valuable for FRAGO development.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) List events, 2) Identify overlaps, 3) Evaluate priorities, 4) Recommend changes."
- Improves for readiness reports.

**When to Use**
- Complex prompts for multi-factor decisions like range requests.
- Trade-offs: Simple for outlines; complex for in-depth analysis.
- Real-world: Updating battalion readiness metrics.

---

### Scenario 3: Data Analysis & Visualization
**Application:** Excel | **USMC Focus:** S-4 (Logistics) | **Duration:** 20-25 min

#### Scenario Context
At Quantico, a Corporal (E-4) tracks equipment readiness, while a 1stLt (O-2) analyzes supply data. Use Copilot to interpret maintenance logs in garrison logistics management.

#### Copilot Capability Focus
- Primary: Data Analysis & Visualization for insights and chart suggestions.
- Sub-capabilities: Pattern detection, bottleneck identification, visualization recommendations.
- Application to USMC: Enhances CMR accountability and supply efficiency.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Analyze this equipment readiness data.
```
- What this prompt does: Gives basic summary.
- Output example: Average rates.
- Limitations: No patterns or visuals.

##### Iteration 2: Add Context
```
Analyze this battalion equipment readiness data from Quantico, including serviceability rates for vehicles and gear.
```
- How context improves output: Ties to USMC logistics.
- Comparison to iteration 1: Identifies specific issues like vehicle downtime.

##### Iteration 3: Add Specificity
```
Analyze this data: Identify patterns in maintenance issues, calculate readiness rates, suggest visualizations like pie charts for bottlenecks.
```
- Why specificity matters: Directs to actionable insights.
- Improved output quality: Includes chart types and explanations.

##### Iteration 4: Final Optimized Prompt
```
As an S-4 logistician at Quantico, analyze this CMR data: Detect patterns in shortages, provide insights on supply chain issues, recommend Excel visualizations (e.g., bar charts) for leadership briefs.
```
- Final refinements: Adds brief context.
- Complete output example: Insights plus chart descriptions.

#### Technical Steps
1. Open Excel with sample maintenance dataset.
2. Copy data range and paste into Copilot Chat.
3. Use progressive prompts to generate insights.
4. Copy suggestions back to Excel to create charts.
5. Verify patterns match data.

#### Facilitation Notes
> 💡 **Tips:**
> - Ensure data is pasted accurately.
> - Checkpoint: Participants create one recommended chart.
> - Troubleshooting: If insights miss, add row/column details.
> - Explain benefits: Visuals aid quick logistics decisions.

#### Expected Outcomes
- ✅ Deliverable: Analyzed data with charts in Excel.
- ✅ Verification: Insights highlight bottlenecks.
- ✅ Capability demonstration: Data interpretation for logistics.
- ✅ Prompt building: Iterations refine analysis depth.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to analyze supply data. What metrics to include?"
- Valuable for shortage reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Calculate rates, 2) Spot patterns, 3) Identify causes, 4) Suggest visuals."
- Improves for maintenance tracking.

**When to Use**
- Complex prompts for trend analysis.
- Trade-offs: Simple for summaries; complex for visuals.
- Real-world: Equipment accountability audits.

---

### Scenario 4: Automation & Orchestration
**Application:** Power Automate | **USMC Focus:** S-6 (Communications) | **Duration:** 20-25 min

#### Scenario Context
At Camp Lejeune, a Lance Corporal (E-3) processes help desk tickets, while a Captain (O-3) designs network workflows. Use Copilot to build automations for SIPR/NIPR access in garrison comms ops.

#### Copilot Capability Focus
- Primary: Automation & Orchestration for workflow design.
- Sub-capabilities: Logic optimization, decision branching, process troubleshooting.
- Application to USMC: Streamlines MCEN ticket resolution.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Design a workflow for help desk tickets.
```
- What this prompt does: Basic flow outline.
- Output example: Simple steps.
- Limitations: No USMC specifics.

##### Iteration 2: Add Context
```
Design a workflow for NMCI help desk tickets at Camp Lejeune, including routing to S-6 techs.
```
- How context improves output: Adds DoD network elements.
- Comparison to iteration 1: Includes notifications.

##### Iteration 3: Add Specificity
```
Design a Power Automate flow: Trigger on new ticket, route based on issue type (SIPR/NIPR), send notifications, track resolution times.
```
- Why specificity matters: Defines triggers and actions.
- Improved output quality: Step-by-step logic.

##### Iteration 4: Final Optimized Prompt
```
As an S-6 admin at Camp Lejeune, design a Power Automate flow for help desk: Trigger on email ticket, branch logic for access requests, optimize for compliance with COMMPLAN, troubleshoot potential errors.
```
- Final refinements: Adds compliance.
- Complete output example: Full flow description.

#### Technical Steps
1. Open Power Automate and start a new flow.
2. Paste ticket sample data into Copilot Chat.
3. Use prompts to generate flow logic.
4. Copy steps to Power Automate and build.
5. Test basic automation.

#### Facilitation Notes
> 💡 **Tips:**
> - Guide on flow connectors.
> - Checkpoint: Verify branching logic.
> - Troubleshooting: If logic fails, refine prompt with errors.
> - Explain benefits: Reduces manual comms tasks.

#### Expected Outcomes
- ✅ Deliverable: Working flow in Power Automate.
- ✅ Verification: Routes tickets correctly.
- ✅ Capability demonstration: Orchestration for comms processes.
- ✅ Prompt building: Iterations optimize automation.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to design ticket workflows. What branches to include?"
- Valuable for SOP automation.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Define trigger, 2) Add conditions, 3) Set actions, 4) Test logic."
- Improves for network ops.

**When to Use**
- Complex prompts for branched flows.
- Trade-offs: Simple for basics; complex for optimization.
- Real-world: Access request processing.

---

### Scenario 5: Search & Retrieval
**Application:** Power BI | **USMC Focus:** S-2 (Intelligence) | **Duration:** 20-25 min

#### Scenario Context
At Camp Pendleton, a Corporal (E-4) compiles threat data, while a 1stLt (O-2) organizes INTSUMs. Use Copilot to extract info from intelligence dashboards in garrison intel prep.

#### Copilot Capability Focus
- Primary: Search & Retrieval for data extraction.
- Sub-capabilities: Information organization, key point consolidation, content finding.
- Application to USMC: Supports IPB and threat assessments without classified access.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Find threat indicators in this data.
```
- What this prompt does: Lists basic items.
- Output example: Unstructured list.
- Limitations: No organization.

##### Iteration 2: Add Context
```
Find specific threat indicators from this intelligence dashboard data at Camp Pendleton, focusing on regional assessments.
```
- How context improves output: Ties to USMC intel.
- Comparison to iteration 1: Groups by type.

##### Iteration 3: Add Specificity
```
Extract threat indicators: Organize into categories (e.g., cyber, physical), include sources and dates, create a structured brief.
```
- Why specificity matters: Formats for easy use.
- Improved output quality: Tabular extraction.

##### Iteration 4: Final Optimized Prompt
```
As an S-2 analyst at Camp Pendleton, search this Power BI dashboard data: Retrieve threat indicators from INTSUMs, organize by priority, extract critical points for a battalion brief per IPB standards.
```
- Final refinements: Adds priority.
- Complete output example: Structured summary.

#### Technical Steps
1. Open Power BI with sample intel dataset.
2. Copy dashboard metrics or visuals description into Copilot Chat.
3. Use prompts to extract data.
4. Copy organized output back to Power BI notes or report.
5. Verify extraction accuracy.

#### Facilitation Notes
> 💡 **Tips:**
> - Describe visuals if not copyable.
> - Checkpoint: Check organized threats.
> - Troubleshooting: Add more data details if missed.
> - Explain benefits: Speeds intel consolidation.

#### Expected Outcomes
- ✅ Deliverable: Extracted brief from dashboard.
- ✅ Verification: Includes key indicators.
- ✅ Capability demonstration: Retrieval for intel tasks.
- ✅ Prompt building: Iterations enhance organization.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to extract intel data. What categories to include?"
- Valuable for after-action reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Scan data, 2) Identify indicators, 3) Categorize, 4) Organize brief."
- Improves for threat assessments.

**When to Use**
- Complex prompts for large datasets.
- Trade-offs: Simple for quick finds; complex for structure.
- Real-world: Recon report compilation.

---

### Scenario 6: Personalization & Context Awareness
**Application:** Teams | **USMC Focus:** S-1 (Administration/Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Quantico, a Staff Sergeant (E-6) summarizes promotion meetings, while a Captain (O-3) generates agendas. Use Copilot to adapt comms to ranks in garrison personnel planning.

#### Copilot Capability Focus
- Primary: Personalization & Context Awareness for adaptive content.
- Sub-capabilities: Terminology adjustment, role-specific suggestions, chain of command awareness.
- Application to USMC: Ensures appropriate language in admin meetings.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this meeting notes.
```
- What this prompt does: General overview.
- Output example: Plain summary.
- Limitations: No USMC adaptation.

##### Iteration 2: Add Context
```
Summarize these promotion board meeting notes from Quantico, including key decisions.
```
- How context improves output: Adds location and focus.
- Comparison to iteration 1: Mentions ranks vaguely.

##### Iteration 3: Add Specificity
```
Summarize notes: Use USMC terminology, adapt language for E5-O4 audience, generate follow-up messages with chain of command.
```
- Why specificity matters: Personalizes tone.
- Improved output quality: Rank-appropriate phrasing.

##### Iteration 4: Final Optimized Prompt
```
As an S-1 manager at Quantico, summarize promotion board notes: Incorporate MARADMIN references, personalize follow-ups by rank (e.g., formal for officers), demonstrate context awareness of unit structure.
```
- Final refinements: Adds references.
- Complete output example: Adapted summary and messages.

#### Technical Steps
1. Open Teams and access sample meeting transcript.
2. Copy notes into Copilot Chat.
3. Apply progressive prompts for refinements.
4. Paste personalized output back to Teams chat or agenda.
5. Check context alignment.

#### Facilitation Notes
> 💡 **Tips:**
> - Focus on rank sensitivity.
> - Checkpoint: Verify tone in follow-ups.
> - Troubleshooting: Add more context if generic.
> - Explain benefits: Enhances collaboration.

#### Expected Outcomes
- ✅ Deliverable: Personalized summary in Teams.
- ✅ Verification: Adapts to ranks.
- ✅ Capability demonstration: Context-aware generation.
- ✅ Prompt building: Iterations build personalization.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt for rank-appropriate summaries. What context to include?"
- Valuable for FITREP meetings.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Review notes, 2) Identify actions, 3) Adapt tone, 4) Generate messages."
- Improves for personnel comms.

**When to Use**
- Complex prompts for audience-specific tasks.
- Trade-offs: Simple for basics; complex for personalization.
- Real-world: Leave coordination meetings.

---

## Quick Reference

### Summary Table of All 6 Scenarios

| Scenario | Capability | Application | USMC Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | S-1 (Administration/Personnel) | 20-25 min |
| 2 | Reasoning & Decision Support | Word | S-3 (Operations) | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | S-4 (Logistics) | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | S-6 (Communications) | 20-25 min |
| 5 | Search & Retrieval | Power BI | S-2 (Intelligence) | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | S-1 (Administration/Personnel) | 20-25 min |

### Progressive Prompt Building Tips
- Start basic, add context, then specificity.
- Use 3-4 iterations to show improvements.
- Include USMC terms for relevance.

### Key Talking Points for Each Copilot Capability
- Language Understanding: Focus on tone and drafting.
- Reasoning: Emphasize decisions and frameworks.
- Data Analysis: Highlight insights and visuals.
- Automation: Stress logic and optimization.
- Search: Prioritize extraction and organization.
- Personalization: Adapt to context and ranks.

### Meta-Prompting and Chain of Reasoning Quick Reference
- **Meta-Prompting Example:** "Help me build a prompt for [task]. Suggest improvements."
- **Chain of Reasoning Example:** "Step by step: 1) Analyze, 2) Recommend, 3) Output."
- Use when outputs need structure or depth.

### Common Questions with Answers
- Q: Why no web search? A: DoD environment restricts grounding.
- Q: How to handle vague outputs? A: Iterate prompts with more details.

### Troubleshooting Common Issues
- Copy/paste fails: Check windows focus.
- Generic outputs: Add USMC context.
- App access: Verify licenses.

### Additional Learning Resources
- [Microsoft Learn: Copilot Fundamentals](https://learn.microsoft.com/en-us/microsoft-copilot/)
- [Microsoft Learn: Prompt Engineering](https://learn.microsoft.com/en-us/training/modules/engineer-copilot-prompts/)
- USMC-specific: Internal MCTIMS modules on M365 (if available).