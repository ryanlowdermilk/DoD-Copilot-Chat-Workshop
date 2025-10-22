# Department of State Copilot Chat Hands-On Workshop: Proctor Guide

## 6 Copilot Capabilities Across Real-World Department of State Scenarios (GCC-High Cloud, Web Grounding Disabled)

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

This guide provides facilitators with the structure and technical steps to facilitate a hands-on workshop for U.S. Department of State personnel on using standalone Copilot Chat. The workshop demonstrates six independent scenarios, each highlighting a unique Copilot capability in authentic diplomatic and administrative contexts at embassies, consulates, and domestic offices.


### Training Objectives
- Demonstrate how to use Microsoft 365 Copilot Chat (with web grounding disabled by admin policy) to enhance productivity in Microsoft 365 applications.
- Build skills in progressive prompt building, meta-prompting, and chain of reasoning for effective Copilot interactions.
- Apply Copilot capabilities to real-world Department of State tasks relevant to both Entry-level (FSO-6/FSO-5, GS-7/GS-9) and Mid-level (FSO-4/FSO-3, GS-11/GS-13) personas.
- Ensure participants can copy/paste and/or upload files between Copilot Chat and M365 apps in a secure government cloud environment.

### Target Audience Description
- **Personas:** Entry-level (junior Foreign Service Officers and civil service employees) and Mid-level (experienced diplomats and managers overseeing operations).
- **Skill Level:** L100-L200 (beginner to intermediate familiarity with M365 apps and basic prompting).
- **Environment:** Embassy, consulate, and domestic State Department offices, focusing on diplomatic, consular, administrative, and policy work.

### Workshop Structure
The workshop consists of six independent scenarios, each 20-25 minutes, allowing flexibility for breaks or Q&A. Scenarios do not build on each other and can be reordered if needed.

### Facilitation Approach
- Guide participants through technical steps without scripts.
- Emphasize hands-on practice with progressive prompts.
- Monitor for compliance with standalone Copilot Chat usage (no in-app integrations).
- Encourage discussion on meta-prompting and chain of reasoning.


### Required Materials/Setup
- Laptops with Microsoft 365 E5 **plus Microsoft 365 Copilot add-on licenses** (GCC-High compliant).
- Access to Microsoft 365 Copilot Chat via web browser (web-only for government cloud tenants).
- Sample data files (e.g., mock diplomatic cables, consular data, policy documents) pre-loaded in M365 apps.
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
- Verify GCC-High environment: Standalone Copilot Chat enabled, no web grounding or M365 Copilot integrations.
- Prepare sample datasets: Mock Department of State documents (e.g., diplomatic cables, visa processing data, policy briefs) compliant with UNCLASSIFIED handling.
- Test workflows: Copy/paste between Copilot Chat and M365 apps.
- Setup attendee accounts: Ensure participants have access to required apps.
- Change mouse pointer size and color.


### Technical Environment Verification
- Confirm **web search grounding is disabled**: Copilot Chat is configured by admin policy to not use web search.
- Verify GCC-High cloud environment: Confirm government tenant (web-only Copilot Chat experience).
- Check Copilot license assignments: All participants have Microsoft 365 Copilot add-on licenses.
- Check app versions: Outlook, Word, Excel, Power Automate, Power BI, Teams (latest government-approved).
- Validate security: All activities in OpenNet or equivalent.


### Required Attendee Access/Accounts
- Microsoft 365 accounts with Copilot Chat and Microsoft 365 Copilot add-on license access.
- Permissions for M365 apps in scenarios.
- Power BI desktop client installed.


### Pre-Work Attendees Should Complete
- Review basic Copilot Chat interface (5-10 min tutorial).
- Familiarize with M365 apps used in scenarios.
- Review government cloud limitations for Copilot features (web-only, some features may be restricted).


### Expected Baseline Knowledge for Attendees
- Basic navigation in M365 apps.
- Understanding of Department of State organizational structure (bureaus and offices).
- Familiarity with diplomatic terminology (e.g., diplomatic notes, demarches, consular affairs).

---

## Scenario Modules

### Introduction

- Team Introduction
    - Bonus points: Use M365 Copilot to introduce yourself with this prompt and play the response on the room's speakers:  
    ```
    "Hi Copilot, I'm giving a workshop on Copilot Chat to Department of State personnel. Please introduce me to the participants in 100 words or less."
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
No matter your viewpoint on AI, our enemies are using it.  If we don't want to bring bows and arrows to the next battle, then we need to use AI as well.  This session is designed to give you ahnds-on experience into six AI functions and hopefully some insight how you can use AI in your day-to-day work.
```
Let's dive right in...

### Scenario 1: Language Understanding & Generation
**Application:** Outlook | **DOS Focus:** Consular Affairs (CA) | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in Warsaw, Poland, a consular associate (GS-9) processes visa applications and responds to inquiries, while a consular officer (FSO-4) oversees case management. Use Copilot to handle email correspondence on visa applications, passport services, and American citizen assistance. This demonstrates efficient communication in consular operations.

#### Copilot Capability Focus
- Primary: Language Understanding & Generation for summarization and drafting.
- Sub-capabilities: Tone adjustment, content rewriting, action item extraction.
- Application to DOS: Streamlines consular services, ensuring professional diplomatic tone aligned with Department protocols.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this email thread about visa applications.
```
- What this prompt does: Provides a simple overview of the thread.
- Output example: A short paragraph listing key points.
- Limitations: Lacks DOS context, may miss deadlines or regulatory references.

##### Iteration 2: Add Context
```
Summarize this email thread about visa applications at U.S. Embassy Warsaw, including applicant details and processing deadlines.
```
- How context improves output: Incorporates DOS specifics like visa categories and applicant information.
- Comparison to iteration 1: More detailed, identifies action items like interview scheduling.

##### Iteration 3: Add Specificity
```
Summarize this email thread about visa applications in a structured format: Key applicants and case numbers, main action items, deadlines, and draft a response email to the applicant using professional consular tone.
```
- Why specificity matters: Ensures formatted output for easy pasting into Outlook.
- Improved output quality: Includes bullet points and a drafted response.

##### Iteration 4: Final Optimized Prompt
```
As a consular officer at U.S. Embassy Warsaw, summarize this email thread on visa applications: List applicants by case number and visa category, extract action items and processing deadlines, then draft a response email with formal diplomatic language, ensuring compliance with 9 FAM (Foreign Affairs Manual) guidance.
```
- Final refinements: Adds regulatory reference for authenticity.
- Complete output example: Structured list plus full email draft.


#### Technical Steps
1. Open the [sample email thread](/DOS/sample%20data/scenario1_email_thread.txt) on visa applications and review the contents.
2. Either upload the [sample email file](/DOS/sample%20data/scenario1_email_thread.txt) to Copilot Chat or copy and paste the thread content into the chat interface.
3. Enter progressive prompts (iterations 1-4) one by one, observing improvements with each iteration.
4. Review Copilot's output (summary and draft response). Note that in a real-world scenario, this output could be used to reply to the actual email thread.
5. Verify tone adjustment for internal vs. external communications.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for copy/paste errors between windows.
> - Checkpoint: Ask participants to share one improved action item.
> - Troubleshooting: If output is vague, remind to add DOS context.
> - Explain benefits: Progressive prompts reduce revisions in consular workflows.

#### Expected Outcomes
- ✅ Deliverable: Summarized thread and drafted email in Outlook.
- ✅ Verification: Output matches diplomatic tone and includes deadlines.
- ✅ Capability demonstration: Clear language generation for consular correspondence.
- ✅ Prompt building: Participants iterate prompts 3-4 times.

#### Discussion Points

**Meta-Prompting**
- Enhance by asking Copilot to refine prompts: "Help me create an effective prompt to summarize visa inquiry emails. What DOS details should I include?"
- Valuable when starting complex tasks like citizenship documentation processing.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Identify key emails, 2) Extract case numbers and actions, 3) Generate summary, 4) Draft response."
- Improves quality for detailed consular reports.

**When to Use**
- Use complex prompts for high-stakes communications like diplomatic notes or formal demarches.
- Trade-offs: Simple prompts for quick tasks; complex for accuracy in consular duties.
- Real-world: Drafting visa refusal letters or emergency assistance responses.

---

### Scenario 2: Reasoning & Decision Support
**Application:** Word | **DOS Focus:** Political Affairs | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in Berlin, Germany, a political officer (FSO-5) drafts policy briefs and situation reports, while a senior political officer (FSO-3) reviews diplomatic cables. Use Copilot to structure documents and resolve conflicts in policy analysis and reporting.

#### Copilot Capability Focus
- Primary: Reasoning & Decision Support for analysis and recommendations.
- Sub-capabilities: Conflict identification, priority frameworks, comparative options.
- Application to DOS: Aids in efficient policy development, ensuring alignment with Department guidance.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Draft a policy brief on regional developments.
```
- What this prompt does: Generates a generic outline.
- Output example: Basic document structure.
- Limitations: Ignores DOS specifics like cable format or policy priorities.

##### Iteration 2: Add Context
```
Draft a policy brief on European regional developments for U.S. Embassy Berlin, including key political trends and bilateral relationship impacts.
```
- How context improves output: Adds location and focus area.
- Comparison to iteration 1: Includes realistic diplomatic considerations.

##### Iteration 3: Add Specificity
```
Draft a policy brief in standard State Department format: Include sections for background, analysis, recommendations; identify potential policy conflicts; suggest prioritization based on U.S. foreign policy objectives.
```
- Why specificity matters: Structures output per DOS standards.
- Improved output quality: Provides reasoned recommendations.

##### Iteration 4: Final Optimized Prompt
```
As a political officer at U.S. Embassy Berlin, draft a policy brief: Structure with standard cable format matching Foreign Affairs Manual guidance, analyze conflicts between competing policy priorities, recommend courses of action based on National Security Strategy objectives, and suggest risk mitigations for diplomatic engagement.
```
- Final refinements: Incorporates doctrinal references.
- Complete output example: Full policy brief with decision framework.


#### Technical Steps
1. Open [sample document](/DOS/sample%20data/scenario2_training_data.txt) for the policy brief.
2. Upload the sample data file or paste sample policy data (e.g., regional developments list) into Copilot Chat.
3. Input progressive prompts, refining based on outputs.
4. Optional: Copy recommendations and structure into a new Word document.
5. Edit for final formatting, demonstrating reasoning application.

#### Facilitation Notes
> 💡 **Tips:**
> - Monitor for prompt overload; break into steps.
> - Checkpoint: Verify policy analysis in output.
> - Troubleshooting: If recommendations are off, add more context.
> - Explain benefits: Builds logical decision-making in policy development.

#### Expected Outcomes
- ✅ Deliverable: Structured policy brief in Word with recommendations.
- ✅ Verification: Includes policy analysis and priorities.
- ✅ Capability demonstration: Reasoning for diplomatic decisions.
- ✅ Prompt building: 3-4 iterations showing progressive logic.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to analyze policy conflicts. What diplomatic considerations should I include?"
- Valuable for developing talking points and demarches.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) List developments, 2) Identify policy implications, 3) Evaluate priorities, 4) Recommend actions."
- Improves for situation reports and cable drafting.

**When to Use**
- Complex prompts for multi-factor decisions like bilateral negotiations.
- Trade-offs: Simple for outlines; complex for in-depth analysis.
- Real-world: Updating country strategic plans or Congressional testimony prep.

---

### Scenario 3: Data Analysis & Visualization
**Application:** Excel | **DOS Focus:** Management Affairs | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in Tokyo, Japan, a management analyst (GS-11) tracks facility assets and equipment inventory, while a management officer (FSO-4) analyzes resource allocation data. Use Copilot to interpret facility management logs and budget tracking.

#### Copilot Capability Focus
- Primary: Data Analysis & Visualization for insights and chart suggestions.
- Sub-capabilities: Pattern detection, bottleneck identification, visualization recommendations.
- Application to DOS: Enhances resource management accountability and operational efficiency.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Analyze this facility equipment data.
```
- What this prompt does: Gives basic summary.
- Output example: Average utilization rates.
- Limitations: No patterns or visuals.

##### Iteration 2: Add Context
```
Analyze this embassy facility equipment data from U.S. Embassy Tokyo, including asset conditions and replacement schedules.
```
- How context improves output: Ties to DOS facility management.
- Comparison to iteration 1: Identifies specific issues like equipment lifecycle concerns.

##### Iteration 3: Add Specificity
```
Analyze this data: Identify patterns in maintenance issues, calculate operational readiness rates, suggest visualizations like bar charts for resource allocation bottlenecks.
```
- Why specificity matters: Directs to actionable insights.
- Improved output quality: Includes chart types and explanations.

##### Iteration 4: Final Optimized Prompt
```
As a management officer at U.S. Embassy Tokyo, analyze this facility asset data: Detect patterns in equipment failures, provide insights on procurement needs, recommend Excel visualizations (e.g., pie charts) for management briefings and budget justifications.
```
- Final refinements: Adds briefing context.
- Complete output example: Insights plus chart descriptions.


#### Technical Steps
1. Open Excel with [sample facility dataset](/DOS/sample%20data/scenario3_equipment_readiness.csv) and review the data.
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
> - Explain benefits: Visuals aid quick management decisions.

#### Expected Outcomes
- ✅ Deliverable: Analyzed data with charts in Excel.
- ✅ Verification: Insights highlight resource gaps.
- ✅ Capability demonstration: Data interpretation for facility management.
- ✅ Prompt building: Iterations refine analysis depth.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to analyze facility data. What metrics to include?"
- Valuable for budget execution reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Calculate utilization rates, 2) Spot patterns, 3) Identify causes, 4) Suggest visuals."
- Improves for asset tracking and procurement planning.

**When to Use**
- Complex prompts for trend analysis across multiple facilities.
- Trade-offs: Simple for summaries; complex for visuals.
- Real-world: Annual facility inventory audits and budget justifications.

---

### Scenario 4: Automation & Orchestration
**Application:** Power Automate | **DOS Focus:** Information Management (IM) | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in London, UK, an information management specialist (GS-9) processes IT service tickets, while an information management officer (FSO-4) designs workflow improvements. Use Copilot to build automations for IT support and classified system access requests.

#### Copilot Capability Focus
- Primary: Automation & Orchestration for workflow design.
- Sub-capabilities: Logic optimization, decision branching, process troubleshooting.
- Application to DOS: Streamlines IT service delivery and classified system administration.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Design a workflow for IT help desk tickets.
```
- What this prompt does: Basic flow outline.
- Output example: Simple steps.
- Limitations: No DOS specifics.

##### Iteration 2: Add Context
```
Design a workflow for embassy IT help desk tickets at U.S. Embassy London, including routing to IM specialists.
```
- How context improves output: Adds diplomatic environment elements.
- Comparison to iteration 1: Includes notification protocols.

##### Iteration 3: Add Specificity
```
Design a Power Automate flow: Trigger on new ticket submission, route based on issue type (OpenNet/ClassNet), send notifications, track resolution times.
```
- Why specificity matters: Defines triggers and actions.
- Improved output quality: Step-by-step logic.

##### Iteration 4: Final Optimized Prompt
```
As an IM specialist at U.S. Embassy London, design a Power Automate flow for IT helpdesk: Trigger on email ticket, branch logic for classified system access requests, optimize for compliance with IRM policies, troubleshoot potential errors.
```
- Final refinements: Adds compliance reference.
- Complete output example: Full flow description.


#### Technical Steps
1. Open Power Automate and start a new flow.
2. Upload or paste [ticket sample data](/DOS/sample%20data/scenario4_helpdesk_tickets.csv) into Copilot Chat.
3. Use prompts to generate flow logic and step-by-step pseudocode (Copilot does not directly automate Power Automate flows; users must implement logic manually).
4. Copy Copilot's suggested steps to Power Automate and build the flow.
5. Test basic automation.

#### Facilitation Notes
> 💡 **Tips:**
> - Guide on flow connectors.
> - Checkpoint: Verify branching logic.
> - Troubleshooting: If logic fails, refine prompt with errors.
> - Explain benefits: Reduces manual IT service tasks.

#### Expected Outcomes
- ✅ Deliverable: Working flow in Power Automate.
- ✅ Verification: Routes tickets correctly.
- ✅ Capability demonstration: Orchestration for IT processes.
- ✅ Prompt building: Iterations optimize automation.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to design IT ticket workflows. What decision branches to include?"
- Valuable for Standard Operating Procedure automation.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Define trigger, 2) Add conditions, 3) Set actions, 4) Test logic."
- Improves for IT service management.

**When to Use**
- Complex prompts for branched flows with multiple approval levels.
- Trade-offs: Simple for basics; complex for optimization.
- Real-world: Classified system access request processing.

---

### Scenario 5: Search & Retrieval
**Application:** Power BI | **DOS Focus:** Intelligence & Research (INR) | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in Nairobi, Kenya, an intelligence analyst (GS-11) compiles open-source intelligence data, while a political officer (FSO-4) organizes regional analysis reports. Use Copilot to extract information from intelligence dashboards for analytical products.

#### Copilot Capability Focus
- Primary: Search & Retrieval for data extraction.
- Sub-capabilities: Information organization, key point consolidation, content finding.
- Application to DOS: Supports analytical reporting and situational awareness without classified access.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Find key indicators in this data.
```
- What this prompt does: Lists basic items.
- Output example: Unstructured list.
- Limitations: No organization.

##### Iteration 2: Add Context
```
Find specific political and security indicators from this open-source intelligence dashboard data at U.S. Embassy Nairobi, focusing on regional developments.
```
- How context improves output: Ties to DOS analytical work.
- Comparison to iteration 1: Groups by topic area.

##### Iteration 3: Add Specificity
```
Extract intelligence indicators: Organize into categories (e.g., political, economic, security), include sources and dates, create a structured analytical brief.
```
- Why specificity matters: Formats for easy use in reporting.
- Improved output quality: Tabular extraction.

##### Iteration 4: Final Optimized Prompt
```
As an intelligence analyst at U.S. Embassy Nairobi, search this Power BI dashboard data: Retrieve key indicators from open-source reports, organize by analytical priority, extract critical points for a situation report per INR analytical standards.
```
- Final refinements: Adds priority and analytical standards.
- Complete output example: Structured summary.


#### Technical Steps
1. Open Power BI with [sample intelligence dataset](/DOS/sample%20data/scenario5_intelligence_data.csv).
2. Copy dashboard metrics or visual descriptions into Copilot Chat (Copilot does not directly extract data from Power BI dashboards; users must manually describe or export data).
3. Use prompts to extract and organize data.
4. Copy organized output back to Power BI notes or report.
5. Verify extraction accuracy.

#### Facilitation Notes
> 💡 **Tips:**
> - Describe visuals if not copyable.
> - Checkpoint: Check organized indicators.
> - Troubleshooting: Add more data details if missed.
> - Explain benefits: Speeds analytical consolidation.

#### Expected Outcomes
- ✅ Deliverable: Extracted brief from dashboard.
- ✅ Verification: Includes key indicators.
- ✅ Capability demonstration: Retrieval for analytical tasks.
- ✅ Prompt building: Iterations enhance organization.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt to extract intelligence data. What categories to include?"
- Valuable for country-level analytical reports.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Scan data, 2) Identify indicators, 3) Categorize, 4) Organize brief."
- Improves for regional assessments and situation reports.

**When to Use**
- Complex prompts for large datasets across multiple sources.
- Trade-offs: Simple for quick finds; complex for structured analysis.
- Real-world: Quarterly regional report compilation or cable drafting.

---

### Scenario 6: Personalization & Context Awareness
**Application:** Teams | **DOS Focus:** Executive Office (EX) | **Duration:** 20-25 min

#### Scenario Context
At the U.S. Embassy in Paris, France, a staff assistant (GS-11) uses a Teams meeting transcript to summarize senior staff meetings, while a deputy chief of mission (FSO-2) generates agendas. Use Copilot to adapt communications to rank and role in embassy leadership coordination.

#### Copilot Capability Focus
- Primary: Personalization & Context Awareness for adaptive content.
- Sub-capabilities: Terminology adjustment, role-specific suggestions, organizational hierarchy awareness.
- Application to DOS: Ensures appropriate language in executive communications and country team coordination.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this meeting notes.
```
- What this prompt does: General overview.
- Output example: Plain summary.
- Limitations: No DOS adaptation.

##### Iteration 2: Add Context
```
Summarize these country team meeting notes from U.S. Embassy Paris, including key decisions and action items.
```
- How context improves output: Adds location and diplomatic focus.
- Comparison to iteration 1: Mentions sections vaguely.

##### Iteration 3: Add Specificity
```
Summarize notes: Use diplomatic terminology, adapt language for embassy section chiefs and DCM, generate follow-up messages aligned with organizational hierarchy.
```
- Why specificity matters: Personalizes tone.
- Improved output quality: Role-appropriate phrasing.

##### Iteration 4: Final Optimized Prompt
```
As a staff assistant at U.S. Embassy Paris, summarize country team meeting notes: Incorporate Department cable references, personalize follow-ups by position (e.g., formal for Ambassador and DCM), demonstrate context awareness of embassy organizational structure and reporting relationships.
```
- Final refinements: Adds cable references.
- Complete output example: Adapted summary and messages.


#### Technical Steps
1. Open the [sample meeting transcript](/DOS/sample%20data/scenario6_meeting_transcript.txt) and review.
2. Copy or upload sample meeting transcript into Copilot Chat.
3. Apply progressive prompts for refinements.
4. Paste personalized output back to Teams chat or meeting notes.
5. Check context alignment.

#### Facilitation Notes
> 💡 **Tips:**
> - Focus on role and rank sensitivity.
> - Checkpoint: Verify tone in follow-ups.
> - Troubleshooting: Add more context if generic.
> - Explain benefits: Enhances country team collaboration.

#### Expected Outcomes
- ✅ Deliverable: Personalized summary in Teams.
- ✅ Verification: Adapts to organizational hierarchy.
- ✅ Capability demonstration: Context-aware generation.
- ✅ Prompt building: Iterations build personalization.

#### Discussion Points

**Meta-Prompting**
- Enhance: "Help me create a prompt for role-appropriate summaries. What diplomatic context to include?"
- Valuable for Ambassador-level briefing preparation.

**Chain of Reasoning**
- Apply: "Let's work through this step by step: 1) Review notes, 2) Identify actions, 3) Adapt tone, 4) Generate messages."
- Improves for executive communications and country team coordination.

**When to Use**
- Complex prompts for audience-specific diplomatic tasks.
- Trade-offs: Simple for basics; complex for personalization.
- Real-world: Country team meeting coordination or Chief of Mission action requests.

---

## Quick Reference

### Summary Table of All 6 Scenarios

| Scenario | Capability | Application | DOS Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | Consular Affairs (CA) | 20-25 min |
| 2 | Reasoning & Decision Support | Word | Political Affairs | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | Management Affairs | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | Information Management (IM) | 20-25 min |
| 5 | Search & Retrieval | Power BI | Intelligence & Research (INR) | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | Executive Office (EX) | 20-25 min |

### Progressive Prompt Building Tips
- Start basic, add context, then specificity.
- Use 3-4 iterations to show improvements.
- Include DOS diplomatic terminology for relevance.

### Key Talking Points for Each Copilot Capability
- Language Understanding: Focus on tone and drafting for consular and diplomatic communications.
- Reasoning: Emphasize decisions and policy frameworks.
- Data Analysis: Highlight insights and visuals for management and budgeting.
- Automation: Stress logic and optimization for IT and administrative processes.
- Search: Prioritize extraction and organization for analytical products.
- Personalization: Adapt to organizational context and diplomatic protocols.

### Meta-Prompting and Chain of Reasoning Quick Reference
- **Meta-Prompting Example:** "Help me build a prompt for [task]. Suggest improvements."
- **Chain of Reasoning Example:** "Step by step: 1) Analyze, 2) Recommend, 3) Output."
- Use when outputs need structure or depth.

### Common Questions with Answers
- Q: Why no web search? A: Government cloud environment restricts external grounding for security.
- Q: How to handle vague outputs? A: Iterate prompts with more diplomatic and contextual details.


### Troubleshooting Common Issues
- Copy/paste fails: Check windows focus.
- File upload fails: Use copy/paste as fallback.
- Generic outputs: Add DOS context and diplomatic terminology.
- App access: Verify licenses (Microsoft 365 E5 + Copilot add-on).


### Additional Learning Resources
- [Microsoft Learn: Copilot Fundamentals](https://learn.microsoft.com/en-us/microsoft-copilot/)
- [Microsoft Learn: Prompt Engineering](https://learn.microsoft.com/en-us/training/modules/engineer-copilot-prompts/)
- [Microsoft Learn: Copilot for Government Cloud](https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-platform-service-description/microsoft-365-copilot#feature-availability)
- DOS-specific: Internal training modules on M365 and diplomatic communications (if available).