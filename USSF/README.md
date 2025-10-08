# USSF Copilot Chat Hands-On Lab: Proctor Guide
## 6 Copilot Capabilities Across Real-World Space Force Scenarios

**Version:** October 08, 2025  
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

This guide provides proctors with a structured approach to facilitate a hands-on lab for US Space Force (USSF) personnel on leveraging standalone Copilot Chat. The lab emphasizes practical application in a DoD environment, focusing on copy/paste workflows between Copilot Chat and Microsoft 365 applications.

### Training Objectives
- Demonstrate six unique Copilot capabilities through independent, real-world USSF scenarios.
- Teach progressive prompt building, meta-prompting, and chain of reasoning techniques.
- Enable Guardians to apply Copilot in classified/sensitive environments without web grounding or integrated features.
- Build confidence in using Copilot for operational tasks across S-staff functions.

### Target Audience Description
- Primary personas: Junior Guardians (E1-E4, O1-O2) and NCOs/Officers (E5-E7, O3-O4).
- Skill level: L100-L200 (beginner to intermediate in Microsoft 365 and AI tools).
- Context: Participants operate at Space Force installations like Peterson SFB, Schriever SFB, Buckley SFB, or Los Angeles AFB, supporting Space Deltas in personnel, operations, logistics, communications, cyber, and intelligence roles.

### Lab Structure (6 Independent Scenarios Overview)
The lab consists of six standalone scenarios, each focusing on one Copilot capability, one USSF focus area, and one Microsoft 365 application. Scenarios do not build on each other and can be facilitated in any order. Each includes progressive prompt building to show refinement techniques.

### Facilitation Approach
- Lead attendees through technical steps with live demonstrations.
- Encourage hands-on practice; pause for questions after each iteration.
- Use discussion points to explore meta-prompting and chain of reasoning.
- Monitor for compliance with DoD restrictions (no web grounding, standalone Copilot only).

### Required Materials/Setup
- Attendees: DoD-issued laptops with Microsoft 365 access (Outlook, Teams, Word, Excel, Power Automate, Power BI).
- Standalone Copilot Chat: Accessed via web browser or separate app (no M365 integrations).
- Sample data files: Pre-loaded email threads, spreadsheets, documents, etc., simulating USSF scenarios (UNCLASSIFIED).
- Classroom: Projector for proctor demos, stable network for internal tools (no internet required).

### Timing Breakdown
- Introduction: 10 minutes
- Each Scenario: 20-25 minutes (setup 2 min, prompts/steps 10-15 min, discussion 5-8 min)
- Breaks: 10 minutes every two scenarios
- Wrap-up: 10 minutes
- Total: 3 hours

---

## Prerequisites & Setup

### Pre-Session Preparation Checklist
- Verify standalone Copilot Chat access for all attendees (browser-based or app).
- Distribute sample data files via secure share (e.g., email threads for Outlook, datasets for Excel).
- Test copy/paste functionality between Copilot Chat and M365 apps.
- Prepare demo accounts with USSF-themed sample content.
- Confirm no web grounding or integrated Copilot features are enabled.

### Technical Environment Verification
- Ensure DoD-compliant environment: Classified/sensitive setup with no internet access.
- Validate M365 apps: Outlook, Teams, Word, Excel, Power Automate, Power BI.
- Check browser compatibility for Copilot Chat (e.g., Edge in DoD mode).
- Test offline functionality; all scenarios must work without real-time search.

### Required Attendee Access/Accounts
- USSF CAC-enabled Microsoft 365 accounts.
- Access to standalone Copilot Chat (not M365 Copilot).
- Permissions for creating/editing files in relevant apps.

### Pre-Work Attendees Should Complete (If Any)
- Review basic Microsoft 365 navigation (5-10 minutes self-study).
- Familiarize with Copilot Chat interface via a quick tutorial (no hands-on required).

### Expected Baseline Knowledge for Attendees
- Basic proficiency in Microsoft 365 apps (e.g., sending emails in Outlook, creating spreadsheets in Excel).
- Understanding of USSF terminology (e.g., Guardian ranks, Space Deltas, S-staff functions).
- No prior AI experience needed; lab starts from beginner level.

---

## Scenario Modules

### Scenario 1: Language Understanding & Generation
**Application:** Outlook | **USSF Focus:** S-1 (Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Peterson Space Force Base, a Specialist 3 (E-3) in the S-1 shop processes quarterly Guardian of the Quarter nominations. This scenario uses Copilot to handle email correspondence, ensuring efficient awards processing for Space Delta personnel. Attendees will accomplish summarizing threads and drafting responses, highlighting why this capability streamlines personnel actions in a fast-paced installation environment.

#### Copilot Capability Focus
- Primary: Language Understanding & Generation (summarization, drafting, tone adjustment).
- Sub-capabilities: Extract action items, rewrite for professional tone.
- Application to USSF: Reduces administrative burden on Guardians, ensuring clear communication in chain of command for promotions and certifications.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this email thread about quarterly award nominations.
```
- What this prompt does: Provides a simple overview of the thread.
- Output example: A short paragraph listing key points from emails.
- Limitations: Lacks detail on action items or USSF-specific tone.

##### Iteration 2: Add Context
```
Summarize this email thread about quarterly Guardian of the Quarter nominations at Peterson SFB, including nominations from Space Delta 4 and 8.
```
- How context improves output: Incorporates USSF terminology and base-specific details for relevance.
- Comparison to iteration 1: More accurate to operational context, identifies Delta-specific nominees.

##### Iteration 3: Add Specificity
```
Summarize this email thread about quarterly Guardian of the Quarter nominations at Peterson SFB: extract action items, deadlines, and nominees from Space Delta 4 and 8. Use professional military tone suitable for a Sergeant briefing.
```
- Why specificity matters: Ensures output includes structured elements like deadlines.
- Improved output quality: Bullet-point list with clear actions, better for quick review.

##### Iteration 4: Final Optimized Prompt
```
Summarize this email thread about quarterly Guardian of the Quarter nominations at Peterson SFB: extract action items, deadlines, nominees from Space Delta 4 and 8, and draft a response email to the squadron commander in professional military tone, addressing E-4 and below ranks.
```
- Final refinements: Adds drafting element for complete workflow.
- Complete output example: Summary bullets + drafted email body.

#### Technical Steps
1. Open Outlook and locate the sample email thread on award nominations.
2. Copy the thread content and paste into standalone Copilot Chat.
3. Enter Iteration 1 prompt; review basic summary.
4. Refine to Iteration 2-4, copying outputs back to Outlook to draft responses.
5. Verify extracted action items match sample data.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for paste formatting issues; advise clearing format in Copilot.
> - Checkpoint: After Iteration 3, confirm attendees see improved structure.
> - Troubleshooting: If output is vague, remind to add USSF context.
> - Explain prompt iteration benefits: Builds from basic to optimized for better results in time-sensitive personnel tasks.

#### Expected Outcomes
- ✅ Deliverable: Summarized thread with drafted response email.
- ✅ Verification: Output includes action items like "Submit nominations by 15 Oct."
- ✅ Capability demonstration: Clear language generation in military tone.
- ✅ Prompt building: Attendees iterate 3-4 times successfully.

#### Discussion Points

**Meta-Prompting**
- Enhances by guiding prompt creation: "Help me create an effective prompt to summarize award emails. What USSF details should I include?"
- Valuable when starting new tasks, like processing unfamiliar personnel reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Identify key emails, 2) Extract nominees and deadlines, 3) Draft response based on chain of command."
- Improves quality in complex threads, ensuring no missed actions.

**When to Use**
- Use for routine S-1 correspondence; simple prompts for quick tasks, complex for detailed reports.
- Trade-offs: Basic is faster but less precise; optimized saves time long-term in USSF admin.

---

### Scenario 2: Reasoning & Decision Support
**Application:** Word | **USSF Focus:** S-3 (Operations) | **Duration:** 20-25 min

#### Scenario Context
At Schriever Space Force Base, a 1st Lt (O-2) in S-3 coordinates Delta training plans. This scenario drafts operations orders, resolving conflicts in crew schedules and orbital windows. Attendees accomplish structured documents with recommendations, showing value in supporting mission readiness without external data.

#### Copilot Capability Focus
- Primary: Reasoning & Decision Support (analysis, recommendations, frameworks).
- Sub-capabilities: Conflict resolution, priority frameworks.
- Application to USSF: Aids in operational planning, ensuring safe crew rotations and mission directives in Space Deltas.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Draft a training plan for Space Delta 9.
```
- What this prompt does: Generates a generic outline.
- Output example: Basic sections like objectives and schedule.
- Limitations: Ignores USSF specifics like orbital conflicts.

##### Iteration 2: Add Context
```
Draft a training plan for Space Delta 9 at Schriever SFB, including crew rest requirements and orbital window considerations.
```
- How context improves output: Adds operational realism.
- Comparison to iteration 1: Includes Delta-specific elements like rest mandates.

##### Iteration 3: Add Specificity
```
Draft a training plan for Space Delta 9 at Schriever SFB: analyze scheduling conflicts for orbital windows, recommend adjustments for crew rest, and structure as a formal operations order with sections for priorities and resources.
```
- Why specificity matters: Prompts detailed reasoning.
- Improved output quality: Includes comparative analysis of options.

##### Iteration 4: Final Optimized Prompt
```
Draft a training plan for Space Delta 9 at Schriever SFB: step-by-step analyze conflicts in orbital windows and crew schedules, provide decision frameworks for priorities, recommend resource allocation, and format as a Word document outline suitable for Captain review.
```
- Final refinements: Emphasizes step-by-step logic.
- Complete output example: Structured order with recommendations.

#### Technical Steps
1. Open Word and create a new document for the training plan.
2. Paste sample schedule data into Copilot Chat.
3. Enter Iteration 1 prompt; copy basic draft to Word.
4. Iterate to 2-4, pasting refined outputs and editing in Word.
5. Verify recommendations align with sample conflicts.

#### Facilitation Notes
> 💡 **Tips:**
> - Monitor for over-reliance on Copilot; encourage manual edits.
> - Checkpoint: After Iteration 3, check for reasoning in outputs.
> - Troubleshooting: If recommendations are off, add more data context.
> - Explain iteration benefits: Refines decision support for accurate ops planning.

#### Expected Outcomes
- ✅ Deliverable: Drafted operations order with recommendations.
- ✅ Verification: Includes frameworks like "Priority 1: Crew safety."
- ✅ Capability demonstration: Logical reasoning in schedules.
- ✅ Prompt building: 3-4 iterations show progressive refinement.

#### Discussion Points

**Meta-Prompting**
- Enhances: "Help me create a prompt to draft ops orders. What reasoning elements should I include for USSF missions?"
- Valuable for complex decisions, like multi-Delta coordination.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Analyze windows, 2) Consider rest, 3) Recommend adjustments."
- Improves in ambiguous ops, reducing errors in readiness reporting.

**When to Use**
- For S-3 planning; simple for outlines, complex for conflicts.
- Trade-offs: Basic quick for juniors; optimized for NCOs in high-stakes missions.

---

### Scenario 3: Data Analysis & Visualization
**Application:** Excel | **USSF Focus:** S-4 (Logistics) | **Duration:** 20-25 min

#### Scenario Context
At Buckley Space Force Base, a Technical Sergeant (E-6) in S-4 tracks satellite health and ground equipment. This scenario analyzes sustainment data, identifying patterns and suggesting visuals. Attendees accomplish insights for briefs, valuable for maintaining orbital asset readiness.

#### Copilot Capability Focus
- Primary: Data Analysis & Visualization (interpretation, patterns, chart suggestions).
- Sub-capabilities: Insight generation, visualization recommendations.
- Application to USSF: Supports logistics decisions, optimizing maintenance in Space Deltas.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Analyze this satellite health data.
```
- What this prompt does: Basic summary of metrics.
- Output example: Average uptime stats.
- Limitations: No patterns or visuals.

##### Iteration 2: Add Context
```
Analyze this satellite health data from Buckley SFB, focusing on ground station maintenance for Space Delta 6.
```
- How context improves output: Ties to USSF logistics.
- Comparison to iteration 1: Identifies Delta-specific issues.

##### Iteration 3: Add Specificity
```
Analyze this satellite health data from Buckley SFB: identify patterns in equipment readiness for Space Delta 6, generate insights on logistics challenges, and recommend visualizations like charts for leadership briefs.
```
- Why specificity matters: Prompts targeted analysis.
- Improved output quality: Includes pattern details and chart types.

##### Iteration 4: Final Optimized Prompt
```
Analyze this satellite health data from Buckley SFB: step-by-step identify patterns in equipment readiness for Space Delta 6, generate insights on sustainment challenges, recommend Excel visualizations (e.g., bar charts for downtime), and suggest formulas for metrics.
```
- Final refinements: Adds step-by-step for depth.
- Complete output example: Patterns list + chart recommendations.

#### Technical Steps
1. Open Excel with sample satellite data spreadsheet.
2. Copy data range and paste into Copilot Chat.
3. Enter Iteration 1 prompt; review basic analysis.
4. Iterate to 2-4, copying suggestions back to Excel to create charts.
5. Implement recommended visualizations.

#### Facilitation Notes
> 💡 **Tips:**
> - Ensure data is pasted as text; avoid formulas initially.
> - Checkpoint: After Iteration 3, verify pattern identification.
> - Troubleshooting: If insights are generic, add more data specifics.
> - Explain iteration benefits: Enhances visualization for clear briefs.

#### Expected Outcomes
- ✅ Deliverable: Analyzed data with charts in Excel.
- ✅ Verification: Insights like "Downtime pattern in Q3."
- ✅ Capability demonstration: Pattern and viz recommendations.
- ✅ Prompt building: Iterations improve analysis depth.

#### Discussion Points

**Meta-Prompting**
- Enhances: "Help me create a prompt to analyze logistics data. What visualization details should I specify?"
- Valuable for large datasets in sustainment tracking.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Interpret metrics, 2) Identify patterns, 3) Recommend visuals."
- Improves accuracy in identifying logistics bottlenecks.

**When to Use**
- For S-4 reports; simple for overviews, complex for insights.
- Trade-offs: Basic fast for juniors; optimized for detailed NCO briefs.

---

### Scenario 4: Automation & Orchestration
**Application:** Power Automate | **USSF Focus:** S-6 (Communications & Cyber) | **Duration:** 20-25 min

#### Scenario Context
At Los Angeles AFB, a Specialist 4 (E-4) in S-6 manages SFN help desk tickets. This scenario designs workflows for routing and notifications. Attendees accomplish automated processes, valuable for cybersecurity compliance and network ops in DoD environments.

#### Copilot Capability Focus
- Primary: Automation & Orchestration (workflow design, logic optimization).
- Sub-capabilities: Decision points, troubleshooting.
- Application to USSF: Streamlines access requests (SIPR/NIPR), reducing manual errors in cyber operations.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Design a workflow for help desk tickets.
```
- What this prompt does: Simple flow outline.
- Output example: Basic steps like receive and assign.
- Limitations: No USSF specifics or logic.

##### Iteration 2: Add Context
```
Design a workflow for SFN help desk tickets at Los Angeles AFB, including routing for SIPR access requests.
```
- How context improves output: Incorporates cyber terminology.
- Comparison to iteration 1: Adds SFN-relevant branches.

##### Iteration 3: Add Specificity
```
Design a workflow for SFN help desk tickets at Los Angeles AFB: include automation logic for routing SIPR requests, send notifications, track resolution times, and optimize decision points for compliance.
```
- Why specificity matters: Details logic and optimization.
- Improved output quality: Step-by-step flow with conditions.

##### Iteration 4: Final Optimized Prompt
```
Design a workflow for SFN help desk tickets at Los Angeles AFB: step-by-step create automation logic for routing SIPR requests, add notifications and resolution tracking, optimize for cybersecurity compliance, and suggest Power Automate steps.
```
- Final refinements: Emphasizes orchestration.
- Complete output example: Detailed flow diagram text.

#### Technical Steps
1. Open Power Automate and start a new flow.
2. Paste sample ticket data into Copilot Chat.
3. Enter Iteration 1 prompt; map basic steps.
4. Iterate to 2-4, copying logic to build the flow.
5. Test and troubleshoot with Copilot suggestions.

#### Facilitation Notes
> 💡 **Tips:**
> - Guide on mapping text to Power Automate actions.
> - Checkpoint: After Iteration 3, confirm decision points.
> - Troubleshooting: If logic fails, refine prompt with errors.
> - Explain iteration benefits: Builds robust automations for cyber tasks.

#### Expected Outcomes
- ✅ Deliverable: Functional workflow in Power Automate.
- ✅ Verification: Includes branches like "If SIPR, route to cyber lead."
- ✅ Capability demonstration: Orchestrated logic.
- ✅ Prompt building: Iterations optimize process.

#### Discussion Points

**Meta-Prompting**
- Enhances: "Help me create a prompt to design cyber workflows. What logic details to include?"
- Valuable for new automations in S-6.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Receive ticket, 2) Check type, 3) Route and notify."
- Improves in troubleshooting complex flows.

**When to Use**
- For S-6 processes; simple for basics, complex for compliance.
- Trade-offs: Basic quick; optimized reduces errors in network ops.

---

### Scenario 5: Search & Retrieval
**Application:** Power BI | **USSF Focus:** S-2 (Intelligence) | **Duration:** 20-25 min

#### Scenario Context
At Peterson SFB, a Sergeant (E-5) in S-2 reviews space domain awareness dashboards. This scenario extracts threat indicators and organizes briefs. Attendees accomplish consolidated summaries, valuable for orbital threat assessments without external search.

#### Copilot Capability Focus
- Primary: Search & Retrieval (finding info, extraction, organization).
- Sub-capabilities: Data point extraction, structuring scattered info.
- Application to USSF: Enhances intelligence prep, supporting Delta leadership with quick retrieval.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Find threat indicators in this dashboard data.
```
- What this prompt does: Lists basic elements.
- Output example: Key threats mentioned.
- Limitations: Unstructured, misses context.

##### Iteration 2: Add Context
```
Find orbital threat indicators in this space domain awareness dashboard from Peterson SFB for Space Delta 2.
```
- How context improves output: Focuses on USSF intelligence.
- Comparison to iteration 1: Ties to specific threats like debris.

##### Iteration 3: Add Specificity
```
Extract specific orbital threat indicators from this space domain awareness dashboard for Space Delta 2 at Peterson SFB: organize into a structured brief with key data points, priorities, and summaries.
```
- Why specificity matters: Ensures organized format.
- Improved output quality: Bullet-point brief.

##### Iteration 4: Final Optimized Prompt
```
Extract orbital threat indicators from this space domain awareness dashboard for Space Delta 2 at Peterson SFB: step-by-step find critical data, organize into a structured intelligence summary with priorities, and format for Power BI integration.
```
- Final refinements: Adds step-by-step retrieval.
- Complete output example: Structured brief with extracts.

#### Technical Steps
1. Open Power BI with sample dashboard.
2. Copy dashboard text/metrics into Copilot Chat.
3. Enter Iteration 1 prompt; review extracts.
4. Iterate to 2-4, pasting organized output back to Power BI notes.
5. Verify extracted points match data.

#### Facilitation Notes
> 💡 **Tips:**
> - Paste visuals as text descriptions.
> - Checkpoint: After Iteration 3, check structure.
> - Troubleshooting: If misses data, add descriptors.
> - Explain iteration benefits: Improves retrieval accuracy for intel.

#### Expected Outcomes
- ✅ Deliverable: Structured brief from dashboard.
- ✅ Verification: Includes indicators like "Debris risk high."
- ✅ Capability demonstration: Efficient info retrieval.
- ✅ Prompt building: Iterations enhance organization.

#### Discussion Points

**Meta-Prompting**
- Enhances: "Help me create a prompt to extract intel data. What structure to specify?"
- Valuable for dense dashboards in S-2.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Scan metrics, 2) Extract threats, 3) Organize by priority."
- Improves in comprehensive threat assessments.

**When to Use**
- For S-2 summaries; simple for basics, complex for briefs.
- Trade-offs: Basic fast; optimized for detailed Delta reports.

---

### Scenario 6: Personalization & Context Awareness
**Application:** Teams | **USSF Focus:** S-1 (Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Schriever SFB, a Captain (O-3) in S-1 leads promotion board meetings. This scenario summarizes discussions and generates follow-ups. Attendees accomplish context-aware communications, valuable for adapting to ranks and chain of command in personnel matters.

#### Copilot Capability Focus
- Primary: Personalization & Context Awareness (contextual adaptation, role-specific).
- Sub-capabilities: Terminology adjustment, rank-appropriate language.
- Application to USSF: Ensures respectful, precise comms in Guardian promotions and certifications.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this meeting about promotion boards.
```
- What this prompt does: General overview.
- Output example: Key topics listed.
- Limitations: No USSF personalization.

##### Iteration 2: Add Context
```
Summarize this promotion board planning meeting at Schriever SFB, using USSF terminology for Space Delta personnel.
```
- How context improves output: Adds Guardian-specific terms.
- Comparison to iteration 1: Includes ranks like E-5 promotions.

##### Iteration 3: Add Specificity
```
Summarize this promotion board planning meeting at Schriever SFB: generate context-aware agendas, follow-up messages adapted to USSF ranks, and ensure chain of command language.
```
- Why specificity matters: Prompts personalization.
- Improved output quality: Rank-tailored messages.

##### Iteration 4: Final Optimized Prompt
```
Summarize this promotion board planning meeting at Schriever SFB: step-by-step adapt to USSF context, generate agendas and follow-up messages with rank-appropriate language (e.g., for Sergeants vs Officers), respecting chain of command.
```
- Final refinements: Emphasizes awareness.
- Complete output example: Summary + personalized messages.

#### Technical Steps
1. Open Teams and access sample meeting transcript.
2. Copy transcript to Copilot Chat.
3. Enter Iteration 1 prompt; review summary.
4. Iterate to 2-4, pasting outputs to Teams for agendas/follow-ups.
5. Send sample messages in chat.

#### Facilitation Notes
> 💡 **Tips:**
> - Emphasize copy/paste for Teams integration.
> - Checkpoint: After Iteration 3, verify rank adaptation.
> - Troubleshooting: If tone off, add more context.
> - Explain iteration benefits: Builds awareness for effective comms.

#### Expected Outcomes
- ✅ Deliverable: Summarized notes with follow-ups.
- ✅ Verification: Messages like "Sergeant, per chain of command..."
- ✅ Capability demonstration: Contextual personalization.
- ✅ Prompt building: Iterations show adaptation.

#### Discussion Points

**Meta-Prompting**
- Enhances: "Help me create a prompt for personnel meetings. What context for ranks?"
- Valuable for varying audiences in S-1.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Summarize discussion, 2) Adapt to ranks, 3) Generate follow-ups."
- Improves in nuanced personnel communications.

**When to Use**
- For S-1 meetings; simple for summaries, complex for adaptations.
- Trade-offs: Basic general; optimized for rank-sensitive tasks.

---

## Quick Reference

### Summary Table of All 6 Scenarios

| Scenario | Capability | Application | USSF Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | S-1 (Personnel) | 20-25 min |
| 2 | Reasoning & Decision Support | Word | S-3 (Operations) | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | S-4 (Logistics) | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | S-6 (Communications & Cyber) | 20-25 min |
| 5 | Search & Retrieval | Power BI | S-2 (Intelligence) | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | S-1 (Personnel) | 20-25 min |

### Progressive Prompt Building Tips
- Start basic: Focus on core task.
- Add context: Include USSF details (e.g., base, Delta).
- Specify: Add format, tone, structure.
- Optimize: Use step-by-step for depth.
- 🔄 Iterate 3-4 times; compare outputs to show improvements.

### Key Talking Points for Each Copilot Capability
- Language Understanding & Generation: Great for comms; adjust tone for ranks.
- Reasoning & Decision Support: Supports ops; provides frameworks for priorities.
- Data Analysis & Visualization: Uncovers patterns; recommends charts for briefs.
- Automation & Orchestration: Builds workflows; optimizes cyber processes.
- Search & Retrieval: Extracts intel; organizes for summaries.
- Personalization & Context Awareness: Adapts to context; ensures rank-appropriate language.

### Meta-Prompting and Chain of Reasoning Quick Reference
- **Meta-Prompting:** "Help me craft a prompt for [task]. Suggest key elements." Use when unsure of structure.
- **Chain of Reasoning:** "Step by step: 1) [step], 2) [step]..." Use for complex analysis to improve accuracy.
- When: Meta for planning; chain for logic-heavy tasks. Trade-off: Adds length but boosts quality.

### Common Questions with Answers
- Q: Why no web search? A: DoD environment restricts to standalone Copilot.
- Q: How to handle vague outputs? A: Iterate prompts with more specificity.
- Q: Can I use in-app Copilot? A: No; only standalone with copy/paste.

### Troubleshooting Common Issues
- Issue: Poor output quality. Fix: Add context/iterations.
- Issue: Paste errors. Fix: Use plain text.
- Issue: No web grounding. Fix: Rely on pasted data only.
- ⚠️ Warning: Ensure all actions stay within UNCLASSIFIED samples.

### Additional Learning Resources
- [Microsoft Learn: Copilot Fundamentals](https://learn.microsoft.com/en-us/microsoft-copilot/)
- [Microsoft Learn: Prompt Engineering](https://learn.microsoft.com/en-us/training/modules/engineer-prompts-copilot-microsoft-365/)
- USSF-specific: Internal training portals for M365 in DoD.