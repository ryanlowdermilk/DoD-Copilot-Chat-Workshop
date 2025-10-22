# USCG Copilot Chat Hands-On Workshop: Proctor Guide

## 6 Copilot Capabilities Across Real-World Coast Guard Scenarios (DoD Cloud, Web Grounding Disabled)

**Version:** October 22, 2025  
**Classification:** UNCLASSIFIED  
**Duration:** 3 hours (6 scenarios × 20-25 min each)

---

## Table of Contents

- [Workshop Overview](#workshop-overview)
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

## Workshop Overview

This guide provides facilitators with the structure and technical steps to facilitate a hands-on workshop for US Coast Guard personnel on using standalone Copilot Chat. The workshop demonstrates six independent scenarios, each highlighting a unique Copilot capability in authentic operational contexts at USCG installations like Base Cape Cod, Base Alameda, or Sector Commands.


### Training Objectives
- Demonstrate how to use Microsoft 365 Copilot Chat (with web grounding disabled by admin policy) to enhance productivity in Microsoft 365 applications.
- Build skills in progressive prompt building, meta-prompting, and chain of reasoning for effective Copilot interactions.
- Apply Copilot capabilities to real-world USCG tasks relevant to both Doer (E1-E4, O1-O2) and Leader (E5-E7, O3-O4) personas.
- Ensure participants can copy/paste and/or upload files between Copilot Chat and M365 apps in a secure DoD cloud environment.

### Target Audience Description
- **Personas:** Doers (junior Coast Guardsmen and officers performing operational tasks) and Leaders (Petty Officers and mid-grade officers overseeing operations).
- **Skill Level:** L100-L200 (beginner to intermediate familiarity with M365 apps and basic prompting).
- **Environment:** At USCG units, sectors, and bases, focusing on maritime safety, security, search and rescue, and operational duties.

### Workshop Structure
The workshop consists of six independent scenarios, each 20-25 minutes, allowing flexibility for breaks or Q&A. Scenarios do not build on each other and can be reordered if needed.

### Facilitation Approach
- Guide participants through technical steps without scripts.
- Emphasize hands-on practice with progressive prompts.
- Monitor for compliance with standalone Copilot Chat usage (no in-app integrations).
- Encourage discussion on meta-prompting and chain of reasoning.


### Required Materials/Setup
- Laptops with Microsoft 365 E5 **plus Microsoft 365 Copilot add-on licenses** (DoD-compliant).
- Access to Microsoft 365 Copilot Chat via web browser (web-only for DoD cloud tenants).
- Sample data files (e.g., mock emails, spreadsheets) pre-loaded in M365 apps.
- Venue with good connectivity both for participants and facilitator.
- Projector for demonstrating steps.

### Timing Breakdown
- Introduction: 10 minutes
- Each Scenario: 20-25 minutes (setup 2 min, hands-on 15 min, discussion 5 min)
- Breaks: 10 minutes total
- Wrap-up: 10 minutes  
⏱️ **Total:** 3 hours

---

## Prerequisites & Setup.

### For Facilitator
- Verify DoD environment: Standalone Copilot Chat enabled, no web grounding or M365 Copilot integrations.
- Prepare sample datasets: Mock USCG documents (e.g., emails, operations plans, incident reports) compliant with UNCLASSIFIED handling.
- Test workflows: Copy/paste between Copilot Chat and M365 apps.
- Setup attendee accounts: Ensure participants have access to required apps.
- Change mouse pointer size and color.


### Technical Environment Verification
- Confirm **web search grounding is disabled**: Copilot Chat is configured by admin policy to not use web search.
- Verify DoD cloud environment: Confirm GCC High or DoD tenant (web-only Copilot Chat experience).
- Check Copilot license assignments: All participants have Microsoft 365 Copilot add-on licenses.
- Check app versions: Outlook, Word, Excel, Power Automate, Power BI, Teams (latest DoD-approved).
- Validate security: All activities in NIPRNet or equivalent.


### Required Attendee Access/Accounts
- Microsoft 365 accounts with Copilot Chat and Microsoft 365 Copilot add-on license access.
- Permissions for M365 apps in scenarios.
- Power BI desktop client installed.


### Pre-Work Attendees Should Complete
- Review basic Copilot Chat interface (5-10 min tutorial).
- Familiarize with M365 apps used in scenarios.
- Review DoD cloud limitations for Copilot features (web-only, some features may be restricted).


### Expected Baseline Knowledge for Attendees
- Basic navigation in M365 apps.
- Understanding of USCG operational specialties and ratings.
- Familiarity with ranks and terminology (e.g., SAR, OPNOTE, Sector Command, Station Operations).

---

## Scenario Modules

### Introduction

- Team Introduction
    - Bonus points: Use M365 Copilot to introduce yourself with this prompt and play the response on the room's speakers:  
    ```
    "Hi Copilot, I'm giving a workshop on Copilot Chat to Coast Guard members at Sector San Francisco. Please introduce me to the participants in 100 words or less."
    ```
- Administrative Topics
- Rules of Engagement:
  - This is meant to be hands-on and immersive.  We learn by doing.  Dive in.
  - If you fall behind or you miss something, don't be bashful, let me know.
  - Ask questions.  A ton of them!

### Lead an AI Discussion
Start by getting a gauge for your audience and their thoughts on AI.  This can be done by asking open-ended questions and giving your participants room to speak. Rather than answering them directly, open it up to the rest of the room, "Yeah, that's a great comment.  Does anyone have any thoughts on that?"  

Another great way is by using Microsoft Forms and having folks submit answers to, "What are your thoughts on AI in three words or less?"

Some talking points that will most likely be discussed:
- AI is bad for society
- AI hallucinations
- AI increases productivity and efficiency
- AI makes it easier for bad actors to do bad things

In the end, the conversation should lead to this:  
```
No matter your viewpoint on AI, our adversaries are using it. If we don't want to bring outdated tools to the next challenge, then we need to use AI as well. This session is designed to give you hands-on experience into six AI functions and hopefully some insight how you can use AI in your day-to-day work.
```
Let's dive right in...

### Scenario 1: Language Understanding & Generation
**Application:** Outlook | **USCG Focus:** Administration/Personnel | **Duration:** 20-25 min

#### Scenario Context
At Sector Boston, a Seaman (E-3) processes quarterly award nominations, while a Chief Petty Officer (E-7) oversees submissions. Use Copilot to handle email correspondence on awards, evaluations, and leave authorizations. This demonstrates efficient communication in administrative tasks at a Sector Command.

#### Copilot Capability Focus
- Primary: Language Understanding & Generation for summarization and drafting.
- Sub-capabilities: Tone adjustment, content rewriting, action item extraction.
- Application to USCG: Streamlines personnel actions, ensuring professional military tone aligned with chain of command.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this email thread about award nominations.
```
- What this prompt does: Provides a simple overview of the thread.
- Output example: A short paragraph listing key points.
- Limitations: Lacks USCG context, may miss deadlines or ranks.

##### Iteration 2: Add Context
```
Summarize this email thread about quarterly award nominations for Coast Guard members at Sector Boston, including ranks and deadlines.
```
- How context improves output: Incorporates USCG specifics like ranks (e.g., E-3 to O-2), making it relevant.
- Comparison to iteration 1: More detailed, identifies action items like submission deadlines.

##### Iteration 3: Add Specificity
```
Summarize this email thread about quarterly award nominations in a structured format: Key participants (with ranks), main action items, deadlines, and draft a response email to the Sector Commander using professional military tone.
```
- Why specificity matters: Ensures formatted output for easy pasting into Outlook.
- Improved output quality: Includes bullet points and a drafted response.

##### Iteration 4: Final Optimized Prompt
```
As a Yeoman at Sector Boston, summarize this email thread on award nominations: List participants by rank, extract action items and deadlines, then draft a response email to the Commander with formal USCG language, ensuring compliance with Coast Guard Awards Manual COMDTINST M1650.25.
```
- Final refinements: Adds regulatory reference for authenticity.
- Complete output example: Structured list plus full email draft.


#### Technical Steps
1. Open the [sample email thread](/USMC/sample%20data/scenario1_email_thread.txt) on award nominations and review the contents.
2. Either upload the [sample email file](/USMC/sample%20data/scenario1_email_thread.txt) to Copilot Chat or copy and paste the thread content into the chat interface.
3. Enter progressive prompts (iterations 1-4) one by one, observing improvements with each iteration.
4. Review Copilot's output (summary and draft response). Note that in a real-world scenario, this output could be used to reply to the actual email thread.
5. Verify tone adjustment for junior vs. senior ranks.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for copy/paste errors between windows.
> - Checkpoint: Ask participants to share one improved action item.
> - Troubleshooting: If output is vague, remind to add USCG context.
> - Explain benefits: Progressive prompts reduce revisions in admin workflows.

#### Expected Outcomes
- ✅ Deliverable: Summarized thread and drafted email in Outlook.
- ✅ Verification: Output matches USCG tone and includes deadlines.
- ✅ Capability demonstration: Clear language generation for personnel correspondence.
- ✅ Prompt building: Participants iterate prompts 3-4 times.

#### Discussion Points

**Meta-Prompting**
- Enhance by asking Copilot to refine prompts: "Help me create an effective prompt to summarize award emails. What USCG details should I include?"
- Valuable when starting complex tasks like evaluation processing.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Identify key emails, 2) Extract ranks and actions, 3) Generate summary, 4) Draft response."
- Improves quality for detailed personnel reports.

**When to Use**
- Use complex prompts for high-stakes comms like transfer orders.
- Trade-offs: Simple prompts for quick tasks; complex for accuracy in personnel duties.
- Real-world: Drafting leave authorizations or change of command invites.

---

### Scenario 2: Reasoning & Decision Support
**Application:** Word | **USCG Focus:** Operations | **Duration:** 20-25 min

#### Scenario Context
At Sector San Diego, a Petty Officer Second Class (E-5) drafts training schedules for boat crew qualifications, while a Lieutenant (O-3) reviews operational plans. Use Copilot to structure documents and resolve conflicts in operational planning.

#### Copilot Capability Focus
- Primary: Reasoning & Decision Support for analysis and recommendations.
- Sub-capabilities: Conflict identification, priority frameworks, comparative options.
- Application to USCG: Aids in efficient operational coordination, ensuring readiness for SAR and law enforcement missions.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Draft a training schedule for a unit.
```
- What this prompt does: Generates a generic outline.
- Output example: Basic calendar layout.
- Limitations: Ignores USCG specifics like boat availability.

##### Iteration 2: Add Context
```
Draft a training schedule for Sector San Diego, including boat crew drills and weapons qualifications for E1-O4 personnel.
```
- How context improves output: Adds location and rank relevance.
- Comparison to iteration 1: Includes realistic events like coxswain training.

##### Iteration 3: Add Specificity
```
Draft a training schedule in operational plan format: Include sections for situation, mission, execution; analyze potential scheduling conflicts; recommend adjustments for resource allocation.
```
- Why specificity matters: Structures output per USCG standards.
- Improved output quality: Provides reasoned recommendations.

##### Iteration 4: Final Optimized Prompt
```
As an Operations Specialist at Sector San Diego, draft a training operations plan: Structure with standard USCG operational plan format, analyze conflicts in boat availability and personnel, recommend priorities based on mission requirements, and suggest risk mitigations.
```
- Final refinements: Incorporates operational references.
- Complete output example: Full operations plan with decision framework.


#### Technical Steps
1. Open [sample document](/USMC/sample%20data/scenario2_training_data.txt) for the OPORD.
2. Upload the sample data file or paste sample training data (e.g., event list) into Copilot Chat.
3. Input progressive prompts, refining based on outputs.
4. Optional: Copy recommendations and structure into a new Word document.
5. Edit for final formatting, demonstrating reasoning application.

#### Facilitation Notes
> 💡 **Tips:**
> - Monitor for prompt overload; break into steps.
> - Checkpoint: Verify conflict analysis in output.
> - Troubleshooting: If recommendations are off, add more data.
> - Explain benefits: Builds logical decision-making in ops planning.

#### Expected Outcomes
- ✅ Deliverable: Structured operations plan in Word with recommendations.
- ✅ Verification: Includes conflict resolutions and priorities.
- ✅ Capability demonstration: Reasoning for operational decisions.
- ✅ Prompt building: 3-4 iterations showing progressive logic.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to analyze training conflicts. What operational details to include?"
- Valuable for mission order development.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) List events, 2) Identify overlaps, 3) Evaluate priorities, 4) Recommend changes."
- Improves for readiness reports.

**When to Use**
- Complex prompts for multi-factor decisions like boat scheduling.
- Trade-offs: Simple for outlines; complex for in-depth analysis.
- Real-world: Updating sector readiness metrics.

---

### Scenario 3: Data Analysis & Visualization
**Application:** Excel | **USCG Focus:** Logistics/Engineering | **Duration:** 20-25 min

#### Scenario Context
At Base Cape Cod, a Machinery Technician Third Class (E-4) tracks cutter readiness, while an Ensign (O-1) analyzes maintenance data. Use Copilot to interpret maintenance logs for vessel logistics management.

#### Copilot Capability Focus
- Primary: Data Analysis & Visualization for insights and chart suggestions.
- Sub-capabilities: Pattern detection, bottleneck identification, visualization recommendations.
- Application to USCG: Enhances cutter readiness accountability and maintenance efficiency.

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
Analyze this cutter readiness data from Base Cape Cod, including serviceability rates for boats and cutters.
```
- How context improves output: Ties to USCG logistics.
- Comparison to iteration 1: Identifies specific issues like engine downtime.

##### Iteration 3: Add Specificity
```
Analyze this data: Identify patterns in maintenance issues, calculate readiness rates, suggest visualizations like pie charts for bottlenecks.
```
- Why specificity matters: Directs to actionable insights.
- Improved output quality: Includes chart types and explanations.

##### Iteration 4: Final Optimized Prompt
```
As an Engineering Petty Officer at Base Cape Cod, analyze this cutter readiness data: Detect patterns in maintenance shortages, provide insights on parts supply issues, recommend Excel visualizations (e.g., bar charts) for command briefs.
```
- Final refinements: Adds brief context.
- Complete output example: Insights plus chart descriptions.


#### Technical Steps
1. Open Excel with [sample maintenance dataset](/USMC/sample%20data/scenario3_equipment_readiness.csv) and review the data.
2. Create a table in Excel: Select the data range, then click **Insert > Table** (or press Ctrl+T) and confirm the range includes headers.
3. **Option A - Copy/Paste:** Copy the table data range and paste into Copilot Chat.
   **Option B - Drag/Drop:** First save the file as an Excel workbook (.xlsx) with **File > Save As**, then drag and drop the .xlsx file into Copilot Chat.
4. Use progressive prompts to generate insights.
5. Copy suggestions back to Excel to create charts.
6. Verify patterns match data.

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
**Application:** Power Automate | **USCG Focus:** IT/Communications | **Duration:** 20-25 min

#### Scenario Context
At Sector Charleston, an Information Systems Technician Third Class (E-4) processes help desk tickets, while a Lieutenant (O-3) designs network workflows. Use Copilot to build automations for system access and IT support.

#### Copilot Capability Focus
- Primary: Automation & Orchestration for workflow design.
- Sub-capabilities: Logic optimization, decision branching, process troubleshooting.
- Application to USCG: Streamlines IT ticket resolution and system access requests.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Design a workflow for help desk tickets.
```
- What this prompt does: Basic flow outline.
- Output example: Simple steps.
- Limitations: No USCG specifics.

##### Iteration 2: Add Context
```
Design a workflow for IT help desk tickets at Sector Charleston, including routing to IT specialists.
```
- How context improves output: Adds USCG network elements.
- Comparison to iteration 1: Includes notifications.

##### Iteration 3: Add Specificity
```
Design a Power Automate flow: Trigger on new ticket, route based on issue type (hardware/software), send notifications, track resolution times.
```
- Why specificity matters: Defines triggers and actions.
- Improved output quality: Step-by-step logic.

##### Iteration 4: Final Optimized Prompt
```
As an IT admin at Sector Charleston, design a Power Automate flow for help desk: Trigger on email ticket, branch logic for access requests, optimize for compliance with USCG IT policies, troubleshoot potential errors.
```
- Final refinements: Adds compliance.
- Complete output example: Full flow description.


#### Technical Steps
1. Open Power Automate and start a new flow.
2. Upload or paste [ticket sample data](/USMC/sample%20data/scenario4_helpdesk_tickets.csv) into Copilot Chat.
3. Use prompts to generate flow logic and step-by-step pseudocode (Copilot does not directly automate Power Automate flows; users must implement logic manually).
4. Copy Copilot's suggested steps to Power Automate and build the flow.
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
- Improves for IT operations.

**When to Use**
- Complex prompts for branched flows.
- Trade-offs: Simple for basics; complex for optimization.
- Real-world: System access request processing.

---

### Scenario 5: Search & Retrieval
**Application:** Power BI | **USCG Focus:** Intelligence | **Duration:** 20-25 min

#### Scenario Context
At Sector San Francisco, a Maritime Enforcement Specialist Second Class (E-5) compiles maritime domain awareness data, while an Intelligence Officer (O-2) organizes intelligence reports. Use Copilot to extract info from intelligence dashboards.

#### Copilot Capability Focus
- Primary: Search & Retrieval for data extraction.
- Sub-capabilities: Information organization, key point consolidation, content finding.
- Application to USCG: Supports maritime intelligence and threat assessments.

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
Find specific threat indicators from this maritime intelligence dashboard data at Sector San Francisco, focusing on vessel tracking and port security.
```
- How context improves output: Ties to USCG intelligence.
- Comparison to iteration 1: Groups by type.

##### Iteration 3: Add Specificity
```
Extract threat indicators: Organize into categories (e.g., smuggling, illegal fishing), include sources and dates, create a structured brief.
```
- Why specificity matters: Formats for easy use.
- Improved output quality: Tabular extraction.

##### Iteration 4: Final Optimized Prompt
```
As an Intelligence Specialist at Sector San Francisco, search this Power BI dashboard data: Retrieve threat indicators from intelligence reports, organize by priority, extract critical points for a command brief per Coast Guard Intelligence standards.
```
- Final refinements: Adds priority.
- Complete output example: Structured summary.


#### Technical Steps
1. Open Power BI with [sample intel dataset](/USMC/sample%20data/scenario5_intelligence_data.csv).
2. Copy dashboard metrics or visual descriptions into Copilot Chat (Copilot does not directly extract data from Power BI dashboards; users must manually describe or export data).
3. Use prompts to extract and organize data.
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
- Enhance: "Help me create a prompt to extract intelligence data. What categories to include?"
- Valuable for after-action reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Scan data, 2) Identify indicators, 3) Categorize, 4) Organize brief."
- Improves for maritime threat assessments.

**When to Use**
- Complex prompts for large datasets.
- Trade-offs: Simple for quick finds; complex for structure.
- Real-world: Port security report compilation.

---

### Scenario 6: Personalization & Context Awareness
**Application:** Teams | **USCG Focus:** Administration/Personnel | **Duration:** 20-25 min

#### Scenario Context
At Base Alameda, a Chief Petty Officer (E-7) uses a Team Meeting transcript to summarize evaluation meetings, while a Lieutenant Commander (O-4) generates agendas. Use Copilot to adapt comms to ranks in personnel planning.

#### Copilot Capability Focus
- Primary: Personalization & Context Awareness for adaptive content.
- Sub-capabilities: Terminology adjustment, role-specific suggestions, chain of command awareness.
- Application to USCG: Ensures appropriate language in administrative meetings.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this meeting notes.
```
- What this prompt does: General overview.
- Output example: Plain summary.
- Limitations: No USCG adaptation.

##### Iteration 2: Add Context
```
Summarize these evaluation board meeting notes from Base Alameda, including key decisions.
```
- How context improves output: Adds location and focus.
- Comparison to iteration 1: Mentions ranks vaguely.

##### Iteration 3: Add Specificity
```
Summarize notes: Use USCG terminology, adapt language for E5-O4 audience, generate follow-up messages with chain of command.
```
- Why specificity matters: Personalizes tone.
- Improved output quality: Rank-appropriate phrasing.

##### Iteration 4: Final Optimized Prompt
```
As a Yeoman Chief at Base Alameda, summarize evaluation board notes: Incorporate COMDTINST references, personalize follow-ups by rank (e.g., formal for officers), demonstrate context awareness of unit structure.
```
- Final refinements: Adds references.
- Complete output example: Adapted summary and messages.


#### Technical Steps
1. Open the [sample meeting transcript](/USMC/sample%20data/scenario6_meeting_transcript.txt) and review.
2. Copy or upload sample meeting transcript into Copilot Chat.
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
- Valuable for evaluation meetings.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Review notes, 2) Identify actions, 3) Adapt tone, 4) Generate messages."
- Improves for personnel comms.

**When to Use**
- Complex prompts for audience-specific tasks.
- Trade-offs: Simple for basics; complex for personalization.
- Real-world: Transfer coordination meetings.

---

## Quick Reference

### Summary Table of All 6 Scenarios

| Scenario | Capability | Application | USCG Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | Administration/Personnel | 20-25 min |
| 2 | Reasoning & Decision Support | Word | Operations | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | Logistics/Engineering | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | IT/Communications | 20-25 min |
| 5 | Search & Retrieval | Power BI | Intelligence | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | Administration/Personnel | 20-25 min |

### Progressive Prompt Building Tips
- Start basic, add context, then specificity.
- Use 3-4 iterations to show improvements.
- Include USCG terms for relevance.

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
- File upload fails: Use copy/paste as fallback.
- Generic outputs: Add USCG context.
- App access: Verify licenses (Microsoft 365 E5 + Copilot add-on).


### Additional Learning Resources
- [Microsoft Learn: Copilot Fundamentals](https://learn.microsoft.com/en-us/microsoft-copilot/)
- [Microsoft Learn: Prompt Engineering](https://learn.microsoft.com/en-us/training/modules/engineer-copilot-prompts/)
- [Microsoft Learn: Copilot for DoD and Government Cloud](https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-platform-service-description/microsoft-365-copilot#feature-availability)
- USCG-specific: Internal DirectAccess or Coast Guard Portal resources on M365 (if available).