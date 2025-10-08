# US Army Copilot Chat Hands-On Lab: Proctor Guide
## 6 Copilot Capabilities Across Real-World Army Scenarios

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

This proctor guide provides a structured framework for facilitating a 3-hour instructor-led hands-on lab focused on leveraging standalone Copilot Chat in US Army environments. The lab emphasizes practical application through six independent scenarios, each highlighting a unique Copilot capability in authentic Army operational contexts.

### Training Objectives
- Demonstrate how to use standalone Copilot Chat to enhance productivity in Microsoft 365 applications via copy/paste workflows.
- Teach progressive prompt building techniques to optimize Copilot outputs for Army-specific tasks.
- Illustrate Copilot's value in supporting G-staff functions without relying on web grounding or integrated features.
- Build confidence in applying Copilot capabilities to real-world Army scenarios at tactical levels.

### Target Audience Description
- Primary personas: Junior Soldiers (E1-E4, O1-O2) and NCOs/Officers (E5-E7, O3-O4).
- Skill level: L100-L200 (beginner to intermediate in Microsoft 365 and AI tools).
- Attendees should have basic familiarity with Army terminology, rank structure, and operational environments at installations like Fort Bragg, Fort Hood, Fort Benning, or Joint Base Lewis-McChord.

### Lab Structure (6 Independent Scenarios Overview)
The lab consists of six standalone scenarios, each lasting 20-25 minutes. Scenarios do not build on each other and can be facilitated in any order. Each focuses on one Copilot capability, one Army focus area, and one Microsoft 365 application.

### Facilitation Approach
- Lead attendees through technical steps with live demonstrations.
- Encourage hands-on practice with progressive prompt iterations.
- Use discussion points to explore meta-prompting and chain of reasoning.
- Monitor for compliance with DoD restrictions (no web grounding, standalone Copilot only).
- Adapt pacing based on group skill level, allocating time for Q&A within each scenario.

### Required Materials/Setup
- Laptops with access to standalone Copilot Chat (web browser or app) in a DoD-approved environment.
- Microsoft 365 accounts with Outlook, Word, Excel, Power Automate, Power BI, and Teams installed.
- Sample data files (e.g., mock email threads, datasets, dashboards) pre-loaded on attendee devices.
- Projector/screen for proctor demonstrations.
- No internet required beyond local network for M365 apps.

### Timing Breakdown
- Introduction: 10 minutes
- Each Scenario: 20-25 minutes (5 min context/setup, 10-15 min hands-on, 5 min discussion)
- Breaks: 10 minutes total (as needed)
- Wrap-up: 10 minutes
- Total: 180 minutes

---

## Prerequisites & Setup

### For Proctor
- Verify all attendee devices meet DoD security standards (e.g., CAC authentication, no unauthorized plugins).
- Test standalone Copilot Chat access in the training environment.
- Prepare sample datasets: Mock emails for Outlook, templates for Word, spreadsheets for Excel, etc.
- Ensure room setup supports group collaboration (e.g., shared screens for troubleshooting).
- Review Army-specific terminology to address questions authentically.

### Technical Environment Verification
- Confirm standalone Copilot Chat is accessible without M365 integration.
- Disable any web grounding features in Copilot settings.
- Test copy/paste functionality between Copilot Chat and M365 apps.
- Validate applications: Outlook, Word, Excel, Power Automate, Power BI, Teams.

### Required Attendee Access/Accounts
- Active DoD Microsoft 365 accounts with E1 or higher licensing.
- CAC-enabled login for secure access.
- Pre-installed M365 apps on government-furnished equipment (GFE).

### Pre-Work Attendees Should Complete (If Any)
- Review basic Copilot Chat interface (5-10 minute self-guided tour).
- Familiarize with assigned Army focus areas relevant to their MOS.

### Expected Baseline Knowledge for Attendees
- Basic navigation in Microsoft 365 apps.
- Understanding of Army G-staff functions and terminology (e.g., OPORDs, NCOERs).
- No prior AI experience required.

---

## Scenario Modules

### Scenario 1: Language Understanding & Generation
**Application:** Outlook | **Army Focus:** G1 (Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Fort Bragg, a G1 section processes personnel actions for a brigade. Attendees act as a Specialist (E-4) or Captain (O-3) handling email correspondence on quarterly award packets. This scenario demonstrates summarizing and drafting emails to streamline NCOER/OER submissions and award recommendations. Copilot's language capabilities save time on routine communications, ensuring compliance with Army Regulation (AR) 600-8-19.

#### Copilot Capability Focus
- Primary: Language Understanding & Generation
- Sub-capabilities: Summarization of threads, drafting responses, tone adjustment for rank-appropriate language
- Application to Army: Enhances efficiency in processing DA Forms 638 (awards) and iPERMS updates by extracting key details from high-volume emails.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this email thread about award nominations.
```
- What this prompt does: Provides a basic overview of the thread.
- Output example: A short paragraph listing main points like nomination deadlines.
- Limitations: Lacks Army-specific context, may miss deadlines or action items.

##### Iteration 2: Add Context
```
Summarize this email thread about quarterly award nominations for a brigade at Fort Bragg, including key action items and deadlines from the battalion commander.
```
- How context improves output: Incorporates location and role-specific details for relevance.
- Comparison to iteration 1: More focused, identifies Army elements like chain of command.

##### Iteration 3: Add Specificity
```
Summarize this email thread about quarterly award nominations, extract action items and deadlines, and draft a professional response email to the battalion commander using formal Army tone suitable for a Captain.
```
- Why specificity matters: Ensures structured output with tone alignment to rank structure.
- Improved output quality: Includes formatted response ready for copy/paste.

##### Iteration 4: Final Optimized Prompt
```
Summarize the following email thread on brigade award packets: Extract all action items, deadlines, and responsible parties. Then, draft a response email to the battalion commander confirming receipt and next steps, using formal military language appropriate for an O-3 officer.
```
- Final refinements: Adds comprehensive extraction and confirmation phrasing.
- Complete output example: Structured summary list plus full email draft.

#### Technical Steps
1. Open Outlook and navigate to a sample email thread on award nominations.
2. Copy the thread content and paste into standalone Copilot Chat.
3. Enter Iteration 1 prompt; review basic summary.
4. Refine to Iteration 2, copy improved summary back to Outlook notes.
5. Use Iteration 3 to generate draft response; paste into new email.
6. Apply Iteration 4 for final polished draft, focusing on language generation.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for copy/paste formatting issues between Copilot and Outlook.
> - Verify outputs include Army terms like "NCOER" or "DA Form 638".
> - Troubleshoot: If output is vague, remind attendees to add specificity.
> - Explain prompt iteration benefits: Builds from simple to complex for better accuracy.

#### Expected Outcomes
- ✅ Deliverable: Summarized thread and drafted email response.
- ✅ Verification: Check for extracted action items and formal tone.
- ✅ Capability demonstration: Clear use of language generation for military correspondence.
- ✅ Prompt building: Attendees complete 3-4 iterations independently.

#### Discussion Points

**Meta-Prompting**
- Enhance by asking Copilot to refine prompts: "Help me create an effective prompt to summarize award emails. What Army-specific details should I include?"
- Valuable when starting new tasks, ensuring prompts align with DoD context.

**Chain of Reasoning**
- Apply by structuring: "Let's work through this step by step: 1) Identify key emails in the thread. 2) Extract action items. 3) Draft response based on chain of command."
- Improves quality for complex personnel actions requiring logical flow.

**When to Use**
- Use complex prompts for high-stakes communications like OERs.
- Trade-offs: Simple prompts for quick tasks; complex for precision.
- Real-world: Processing leave requests (DA Form 31) or assignment actions in eMILPO.

---

### Scenario 2: Reasoning & Decision Support
**Application:** Word | **Army Focus:** G3 (Operations) | **Duration:** 20-25 min

#### Scenario Context
At Fort Hood, a G3 operations cell develops training schedules for an armored brigade. Attendees role-play as a Sergeant (E-5) or 1st Lieutenant (O-2) drafting an OPORD for range training. This scenario shows how Copilot aids in structuring documents and resolving scheduling conflicts, aligning with FM 7-0 (Training) for operational readiness.

#### Copilot Capability Focus
- Primary: Reasoning & Decision Support
- Sub-capabilities: Analyzing conflicts, generating recommendations, creating decision frameworks
- Application to Army: Supports mission planning by evaluating resource constraints and prioritizing tasks.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Draft a training schedule for a brigade.
```
- What this prompt does: Generates a generic outline.
- Output example: Simple list of events without details.
- Limitations: Ignores Army-specific elements like range requests.

##### Iteration 2: Add Context
```
Draft a training schedule for an armored brigade at Fort Hood, considering range availability and unit readiness.
```
- How context improves output: Adds installation-specific details for realism.
- Comparison to iteration 1: Includes operational context like vehicle maintenance.

##### Iteration 3: Add Specificity
```
Draft an OPORD for brigade training, analyze potential scheduling conflicts with range requests, and provide recommendations for risk mitigation in a structured format.
```
- Why specificity matters: Directs output to include analysis and frameworks.
- Improved output quality: Structured sections with pros/cons.

##### Iteration 4: Final Optimized Prompt
```
Draft a FRAGO to the brigade OPORD: Step 1 - List training events. Step 2 - Identify conflicts with resources. Step 3 - Recommend adjustments based on priorities per FM 7-0.
```
- Final refinements: Incorporates step-by-step reasoning.
- Complete output example: Full OPORD draft with recommendation table.

#### Technical Steps
1. Open Word and create a new document for the OPORD template.
2. Copy sample training data (e.g., event list) into Copilot Chat.
3. Enter Iteration 1 prompt; paste basic draft into Word.
4. Refine to Iteration 2, update document with context.
5. Use Iteration 3 for conflict analysis; insert recommendations.
6. Apply Iteration 4 for final structure, emphasizing decision support.

#### Facilitation Notes
> 💡 **Tips:**
> - Monitor for Word formatting retention during paste.
> - Verification: Ensure outputs reference Army docs like FRAGOs.
> - Troubleshoot: If recommendations are off, add more data to prompts.
> - Explain iterations: Shows how reasoning evolves with added logic.

#### Expected Outcomes
- ✅ Deliverable: Structured OPORD with recommendations.
- ✅ Verification: Check for conflict analysis and frameworks.
- ✅ Capability demonstration: Effective use of reasoning for operations.
- ✅ Prompt building: 3-4 iterations showing progressive refinement.

#### Discussion Points

**Meta-Prompting**
- Use: "Help me build a prompt to analyze training conflicts. What decision factors from Army doctrine should I include?"
- Valuable for unfamiliar tasks like readiness reporting.

**Chain of Reasoning**
- Apply: "Let's reason step by step: 1) Review events. 2) Assess risks. 3) Prioritize based on METL."
- Improves for decision-heavy tasks like OPORD revisions.

**When to Use**
- Complex prompts for multi-factor decisions; simple for basic drafts.
- Trade-offs: Time vs. depth in analysis.
- Real-world: Coordinating range requests or updating training calendars.

---

### Scenario 3: Data Analysis & Visualization
**Application:** Excel | **Army Focus:** G4 (Logistics) | **Duration:** 20-25 min

#### Scenario Context
At Fort Benning, a G4 logistics team tracks equipment readiness for an infantry battalion. Attendees simulate a Staff Sergeant (E-6) or Captain (O-3) analyzing maintenance data. This scenario highlights identifying patterns in supply issues, supporting AR 750-1 (Maintenance) for property accountability.

#### Copilot Capability Focus
- Primary: Data Analysis & Visualization
- Sub-capabilities: Pattern identification, insight generation, visualization recommendations
- Application to Army: Aids in spotting logistics bottlenecks like hand receipt shortages.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Analyze this equipment data.
```
- What this prompt does: Gives simple stats.
- Output example: Average readiness rates.
- Limitations: No insights or visuals.

##### Iteration 2: Add Context
```
Analyze this battalion equipment maintenance data from Fort Benning, focusing on readiness rates and supply issues.
```
- How context improves output: Ties to Army logistics terms.
- Comparison to iteration 1: Adds specific patterns like recurring faults.

##### Iteration 3: Add Specificity
```
Analyze the data: Identify patterns in maintenance issues, generate insights on supply chain bottlenecks, and recommend Excel charts to visualize readiness trends.
```
- Why specificity matters: Directs to actionable outputs.
- Improved output quality: Includes chart types like pivot tables.

##### Iteration 4: Final Optimized Prompt
```
Step-by-step analysis of equipment data: 1) Calculate readiness rates. 2) Identify top issues. 3) Suggest visualizations like bar charts for leadership briefs.
```
- Final refinements: Structured for clarity.
- Complete output example: Insights list plus chart descriptions.

#### Technical Steps
1. Open Excel with sample maintenance spreadsheet (e.g., readiness rates).
2. Copy data range and paste into Copilot Chat.
3. Enter Iteration 1 prompt; note basic analysis.
4. Refine to Iteration 2, copy insights back to Excel comments.
5. Use Iteration 3 for visualization recommendations; apply in Excel.
6. Apply Iteration 4 for comprehensive output, focusing on data analysis.

#### Facilitation Notes
> 💡 **Tips:**
> - Ensure data is anonymized for DoD compliance.
> - Verification: Outputs should mention terms like "hand receipts".
> - Troubleshoot: If patterns missed, paste more data rows.
> - Explain iterations: Demonstrates how specificity enhances insights.

#### Expected Outcomes
- ✅ Deliverable: Analyzed data with visualization suggestions.
- ✅ Verification: Patterns identified and charts recommended.
- ✅ Capability demonstration: Core data analysis in logistics.
- ✅ Prompt building: Iterative refinement for better results.

#### Discussion Points

**Meta-Prompting**
- Example: "Help me craft a prompt to analyze logistics data. What visualization details should I specify?"
- Valuable for large datasets requiring targeted insights.

**Chain of Reasoning**
- Apply: "Think step by step: 1) Review data columns. 2) Spot trends. 3) Recommend fixes."
- Improves accuracy in identifying maintenance patterns.

**When to Use**
- Complex for detailed analysis; simple for quick stats.
- Trade-offs: Depth vs. speed in reporting.
- Real-world: Tracking property accountability or shortage reports.

---

### Scenario 4: Automation & Orchestration
**Application:** Power Automate | **Army Focus:** G6 (Signal/Communications) | **Duration:** 20-25 min

#### Scenario Context
At Joint Base Lewis-McChord, a G6 team manages network operations for a division. Attendees portray a Private First Class (E-3) or 1st Lieutenant (O-2) designing workflows for help desk tickets. This scenario optimizes processes for NIPR/SIPR access requests, per AR 25-2 (Information Assurance).

#### Copilot Capability Focus
- Primary: Automation & Orchestration
- Sub-capabilities: Workflow design, logic optimization, decision point creation
- Application to Army: Streamlines IT support, reducing resolution times for comms issues.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Design a workflow for help desk tickets.
```
- What this prompt does: Outlines simple steps.
- Output example: Basic flow like receive-route-resolve.
- Limitations: No Army-specific logic.

##### Iteration 2: Add Context
```
Design an automated workflow for processing Army network help desk tickets at Joint Base Lewis-McChord, including routing to G6 sections.
```
- How context improves output: Incorporates DoD environment.
- Comparison to iteration 1: Adds notifications for SIPR issues.

##### Iteration 3: Add Specificity
```
Design the workflow: Include logic for ticket routing based on type (NIPR/SIPR), send notifications, and track resolution times with decision branches.
```
- Why specificity matters: Ensures executable logic.
- Improved output quality: Detailed steps for Power Automate.

##### Iteration 4: Final Optimized Prompt
```
Orchestrate a workflow: 1) Receive ticket. 2) Classify by urgency. 3) Route with branches. 4) Notify and track per AR 25-2.
```
- Final refinements: Step-by-step orchestration.
- Complete output example: Full flow description with branches.

#### Technical Steps
1. Open Power Automate and start a new flow.
2. Describe desired workflow in Copilot Chat using sample ticket data.
3. Enter Iteration 1 prompt; sketch basic flow.
4. Refine to Iteration 2, add context to flow triggers.
5. Use Iteration 3 for logic branches; implement in Power Automate.
6. Apply Iteration 4 for optimization, testing automation steps.

#### Facilitation Notes
> 💡 **Tips:**
> - Watch for flow connector issues in DoD networks.
> - Verification: Include terms like "help desk tickets".
> - Troubleshoot: If logic fails, refine prompts with examples.
> - Explain iterations: Builds robust automation from basics.

#### Expected Outcomes
- ✅ Deliverable: Designed workflow with routing logic.
- ✅ Verification: Branches and notifications functional.
- ✅ Capability demonstration: Automation for G6 tasks.
- ✅ Prompt building: 3-4 iterations for refined logic.

#### Discussion Points

**Meta-Prompting**
- Example: "Help me create a prompt for workflow design. What logic elements for Army IT should I add?"
- Valuable for complex orchestrations like access requests.

**Chain of Reasoning**
- Apply: "Reason step by step: 1) Define inputs. 2) Build branches. 3) Optimize outputs."
- Improves for troubleshooting workflow errors.

**When to Use**
- Complex prompts for branched flows; simple for linear.
- Trade-offs: Customization vs. setup time.
- Real-world: Automating compliance tracking or system access.

---

### Scenario 5: Search & Retrieval
**Application:** Power BI | **Army Focus:** G2 (Intelligence) | **Duration:** 20-25 min

#### Scenario Context
At Fort Bragg, a G2 intelligence section reviews threat assessments for a special forces group. Attendees act as a Sergeant (E-5) or Captain (O-3) extracting data from dashboards. This scenario organizes IPB (Intelligence Preparation of the Battlefield) info, supporting FM 2-0 (Intelligence).

#### Copilot Capability Focus
- Primary: Search & Retrieval
- Sub-capabilities: Information finding, data extraction, content organization
- Application to Army: Quickly retrieves key indicators from classified reports.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Find threat indicators in this dashboard data.
```
- What this prompt does: Lists basic items.
- Output example: Bullet points of threats.
- Limitations: No structure or context.

##### Iteration 2: Add Context
```
Search this intelligence dashboard for threat indicators relevant to operations at Fort Bragg, extracting key data points from summaries.
```
- How context improves output: Focuses on Army intelligence.
- Comparison to iteration 1: Organizes by threat type.

##### Iteration 3: Add Specificity
```
Retrieve specific threat indicators: Extract critical data points, organize into a structured brief with categories like regional risks and timelines.
```
- Why specificity matters: Ensures organized format.
- Improved output quality: Table-like structure for briefs.

##### Iteration 4: Final Optimized Prompt
```
Systematically search the data: 1) Identify indicators. 2) Extract details. 3) Organize into a consolidated summary for brigade leadership.
```
- Final refinements: Step-by-step retrieval.
- Complete output example: Structured brief with extracted points.

#### Technical Steps
1. Open Power BI with sample intelligence dashboard.
2. Copy dashboard metrics/text into Copilot Chat.
3. Enter Iteration 1 prompt; review basic extraction.
4. Refine to Iteration 2, organize output in Power BI notes.
5. Use Iteration 3 for structured brief; paste back.
6. Apply Iteration 4 for final consolidation, emphasizing retrieval.

#### Facilitation Notes
> 💡 **Tips:**
> - Ensure data is unclassified mockups.
> - Verification: Outputs reference "threat assessments".
> - Troubleshoot: If extraction misses items, add more descriptors.
> - Explain iterations: Enhances precision in search.

#### Expected Outcomes
- ✅ Deliverable: Organized intelligence summary.
- ✅ Verification: Key data points extracted accurately.
- ✅ Capability demonstration: Search for G2 tasks.
- ✅ Prompt building: Iterative for better organization.

#### Discussion Points

**Meta-Prompting**
- Example: "Help me build a prompt to extract intelligence data. What search criteria for threats should I include?"
- Valuable for voluminous dashboards.

**Chain of Reasoning**
- Apply: "Step by step: 1) Scan for keywords. 2) Extract context. 3) Organize logically."
- Improves retrieval from scattered data.

**When to Use**
- Complex for detailed searches; simple for quick finds.
- Trade-offs: Thoroughness vs. brevity.
- Real-world: Compiling daily intelligence briefs or IPB.

---

### Scenario 6: Personalization & Context Awareness
**Application:** Teams | **Army Focus:** G1 (Personnel) | **Duration:** 20-25 min

#### Scenario Context
At Fort Hood, a G1 team coordinates promotion boards via Teams meetings. Attendees simulate a Staff Sergeant (E-6) or 2nd Lieutenant (O-1) summarizing discussions on personnel matters. This scenario adapts outputs to rank and chain of command, per AR 600-8-29 (Promotions).

#### Copilot Capability Focus
- Primary: Personalization & Context Awareness
- Sub-capabilities: Contextual suggestions, terminology adaptation, role-specific messaging
- Application to Army: Tailors communications for efficient follow-ups in personnel actions.

#### Progressive Prompt Building

##### Iteration 1: Basic Prompt
```
Summarize this meeting discussion.
```
- What this prompt does: General overview.
- Output example: Key points list.
- Limitations: No Army adaptation.

##### Iteration 2: Add Context
```
Summarize this promotion board planning meeting at Fort Hood, using Army terminology like NCOERs and chain of command.
```
- How context improves output: Incorporates military specifics.
- Comparison to iteration 1: Adds rank references.

##### Iteration 3: Add Specificity
```
Summarize the meeting: Generate a context-aware agenda follow-up, adapt language for junior Soldiers vs Officers, and include tasks by staff section.
```
- Why specificity matters: Ensures personalization.
- Improved output quality: Rank-appropriate phrasing.

##### Iteration 4: Final Optimized Prompt
```
Personalize summary: 1) Recap discussion. 2) Adapt to context (e.g., E-6 tone). 3) Create follow-up messages respecting chain of command.
```
- Final refinements: Emphasizes awareness.
- Complete output example: Adapted summary and messages.

#### Technical Steps
1. Open Teams and access sample meeting transcript.
2. Copy transcript into Copilot Chat.
3. Enter Iteration 1 prompt; paste basic summary to Teams chat.
4. Refine to Iteration 2, add context for agenda.
5. Use Iteration 3 for personalized follow-ups; post in Teams.
6. Apply Iteration 4 for final outputs, focusing on context awareness.

#### Facilitation Notes
> 💡 **Tips:**
> - Check Teams permissions in DoD setup.
> - Verification: Outputs use "promotion boards" etc.
> - Troubleshoot: If tone off, specify ranks explicitly.
> - Explain iterations: Shows adaptation improvements.

#### Expected Outcomes
- ✅ Deliverable: Personalized summary and follow-ups.
- ✅ Verification: Rank-appropriate language confirmed.
- ✅ Capability demonstration: Context for G1 communications.
- ✅ Prompt building: 3-4 iterations for refinement.

#### Discussion Points

**Meta-Prompting**
- Example: "Help me create a prompt for meeting summaries. How to include personalization for Army ranks?"
- Valuable for role-specific tasks.

**Chain of Reasoning**
- Apply: "Think step by step: 1) Analyze notes. 2) Adapt to context. 3) Generate tailored outputs."
- Improves for nuanced communications.

**When to Use**
- Complex for personalized outputs; simple for basics.
- Trade-offs: Customization vs. generality.
- Real-world: Follow-ups on awards or leave requests.

---

## Quick Reference

### Summary Table of All 6 Scenarios

| Scenario | Capability | Application | Army Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | G1 (Personnel) | 20-25 min |
| 2 | Reasoning & Decision Support | Word | G3 (Operations) | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | G4 (Logistics) | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | G6 (Signal/Communications) | 20-25 min |
| 5 | Search & Retrieval | Power BI | G2 (Intelligence) | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | G1 (Personnel) | 20-25 min |

### Progressive Prompt Building Tips
- Start basic: Focus on core task.
- Add context: Include Army details (e.g., installation, ranks).
- Add specificity: Specify format, tone, structure.
- Optimize: Use steps for reasoning.
- 🔄 Iterate 3-4 times for best results.

### Key Talking Points for Each Copilot Capability
- Language Understanding & Generation: Emphasize tone for military comms.
- Reasoning & Decision Support: Highlight frameworks for ops planning.
- Data Analysis & Visualization: Stress insights for logistics.
- Automation & Orchestration: Focus on logic for IT workflows.
- Search & Retrieval: Note extraction for intel.
- Personalization & Context Awareness: Adapt to ranks in teams.

### Meta-Prompting and Chain of Reasoning Quick Reference
- **Meta-Prompting:** "Help me build a prompt for [task]. What details to include?" – Use for prompt optimization.
- **Chain of Reasoning:** "Step by step: 1) [Step]. 2) [Step]." – Apply for logical tasks.

### Common Questions with Answers
- Q: Why no web search? A: DoD environment restricts grounding; use standalone Copilot.
- Q: How to handle errors? A: Refine prompts with more context.
- Q: Can scenarios connect? A: No, they are independent.

### Troubleshooting Common Issues
- Copy/paste fails: Check clipboard permissions.
- Vague outputs: Add specificity/iterations.
- App access: Verify CAC login.
- ⚠️ Warning: Ensure no integrated Copilot features used.

### Additional Learning Resources
- [Microsoft Learn: Copilot Fundamentals](https://learn.microsoft.com/en-us/microsoft-copilot/)
- [Microsoft Learn: Power Automate](https://learn.microsoft.com/en-us/power-automate/)
- [Microsoft Learn: Power BI](https://learn.microsoft.com/en-us/power-bi/)