# USN Copilot Chat Hands-On Lab: Proctor Guide
## 6 Copilot Capabilities Across Real-World Navy Scenarios
Version: October 8, 2025  
Classification: UNCLASSIFIED  
Duration: 3 hours (6 scenarios × 20-25 min each)

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

This proctor guide provides a comprehensive framework for facilitating a 3-hour hands-on lab designed to train US Navy personnel on the effective use of standalone Copilot Chat. The lab emphasizes practical application in DoD-compliant environments, focusing on productivity enhancements for operational duties. Participants will engage in six independent scenarios, each highlighting a unique Copilot capability integrated with Microsoft 365 applications, tailored to Navy focus areas.

### Training Objectives
- Demonstrate proficiency in using standalone Copilot Chat for language generation, reasoning, data analysis, automation, search, and personalization tasks relevant to Navy operations.
- Build skills in progressive prompt engineering to optimize Copilot outputs without web grounding.
- Apply Copilot capabilities to real-world Navy scenarios, improving efficiency in manpower, operations, logistics, communications, and intelligence tasks.
- Understand meta-prompting and chain of reasoning techniques to enhance problem-solving in classified environments.
- Verify compliance with DoD security protocols, ensuring no reliance on internet access or integrated M365 Copilot features.

### Target Audience Description
This lab targets US Navy Sailors (E1-E4) and Petty Officers/Officers (E5-E7, O1-O4) at beginner to intermediate skill levels (L100-L200) with Microsoft 365. Participants include active duty personnel from installations like Naval Station Norfolk, Naval Base San Diego, and afloat units such as USS ships. They perform operational duties requiring professional communication, data management, and workflow optimization in sensitive environments.

### Lab Structure (6 Independent Scenarios Overview)
The lab consists of six standalone scenarios, each lasting 20-25 minutes. Scenarios do not build on each other, allowing flexibility in delivery. Each focuses on one Copilot capability, one Navy focus area, and one Microsoft 365 application:

- **Scenario 1**: Language Understanding & Generation (N1 Manpower & Personnel, Outlook)
- **Scenario 2**: Reasoning & Decision Support (N3 Operations, Word)
- **Scenario 3**: Data Analysis & Visualization (N4 Logistics, Excel)
- **Scenario 4**: Automation & Orchestration (N6 Communications & IT, Power Automate)
- **Scenario 5**: Search & Retrieval (N2 Intelligence, Power BI)
- **Scenario 6**: Personalization & Context Awareness (N1 Manpower & Personnel, Teams)

Proctors guide participants through technical steps, prompt iterations, and discussions without providing speaking scripts.

### Facilitation Approach
- **Progressive Prompt Building**: Start with basic prompts and refine iteratively to demonstrate improvements in output quality.
- **Hands-On Focus**: Participants copy/paste between standalone Copilot Chat (browser or app) and the target application.
- **Group Dynamics**: Support small groups (5-10 participants) with walkthroughs, checkpoints, and troubleshooting.
- **DoD Compliance**: Emphasize offline capabilities; prohibit any web-integrated features.
- **Discussion Integration**: Allocate time for meta-prompting and chain of reasoning to reinforce advanced techniques.

### Required Materials/Setup
- Laptops or workstations with Microsoft 365 (DoD tenant) and standalone Copilot Chat access.
- Pre-loaded sample data files (e.g., email threads, spreadsheets) in secure shared folders.
- Projector/screen for proctor demonstrations.
- Printed quick reference sheets for proctors.
- Secure lab environment (e.g., SCIF or unclassified training room) with no internet connectivity.

### Timing Breakdown
⏱️ **Total Duration**: 3 hours  
- Introduction & Setup: 15 minutes  
- Scenario 1-6: 20-25 minutes each (total ~2 hours 15 minutes)  
- Breaks: 10 minutes (mid-lab)  
- Wrap-Up & Q&A: 20 minutes  

---

## Prerequisites & Setup

### For Proctor: Pre-Session Preparation Checklist
- [x] Verify all workstations have standalone Copilot Chat installed or accessible via browser (e.g., copilot.microsoft.com in DoD-approved mode).
- [x] Test copy/paste workflows between Copilot Chat and M365 apps (Outlook, Word, Excel, Power Automate, Power BI, Teams).
- [x] Prepare sample datasets: Email threads for Outlook, templates for Word, spreadsheets for Excel, etc., stored in secure OneDrive or local folders.
- [x] Confirm no web grounding or integrated Copilot features are enabled (e.g., no M365 Copilot licenses).
- [x] Review Navy-specific terminology and scenarios for authenticity.
- [ ] Set up demo accounts simulating E3 Seaman to O3 Lieutenant roles.
- [ ] Print or distribute this guide for reference.

### Technical Environment Verification
- **OS & Software**: Windows 10/11 with Microsoft 365 E5 (DoD edition); standalone Copilot Chat v1.0+.
- **Security Settings**: FIPS compliance enabled; no external APIs or internet access.
- **Testing**: Run a sample prompt in Copilot Chat to confirm offline functionality.
- **Backup**: Have spare workstations ready for technical failures.

### Required Attendee Access/Accounts
- Active DoD CAC-enabled Microsoft 365 accounts.
- Access to standalone Copilot Chat (not integrated versions).
- Permissions for M365 apps: Read/write in Outlook, Word, Excel, Power Automate, Power BI, Teams.
- No additional licenses required beyond base M365.

### Pre-Work Attendees Should Complete (If Any)
- Review basic Microsoft 365 navigation (e.g., opening apps, copy/paste).
- Familiarize with Navy N-staff codes and terminology via NAVADMIN summaries.
- Complete Microsoft Learn module: "Get started with Copilot Chat" (offline version if available).

### Expected Baseline Knowledge for Attendees
- Basic proficiency in Microsoft 365 apps (e.g., creating emails in Outlook, spreadsheets in Excel).
- Understanding of Navy rank structure (E1-E9, O1-O6) and operational terms (EVALs, CASREPs, watch bills).
- Awareness of DoD compliance rules for AI tools (e.g., no classified data in prompts).

---

## Scenario Modules

### Scenario 1: Language Understanding & Generation
Application: Outlook | Navy Focus: N1 (Manpower & Personnel) | Duration: 20-25 min

#### Scenario Context
At Naval Station Norfolk, a Petty Officer Second Class (E-5) in the Admin Department processes personnel actions for a destroyer squadron. This scenario involves summarizing email threads about quarterly award nominations and drafting responses. Participants will accomplish drafting professional naval correspondence while extracting action items. This Copilot capability is valuable for N1 tasks as it streamlines communication in high-volume personnel environments, reducing administrative burden on Sailors and Officers.

#### Copilot Capability Focus
- Primary capability: Language Understanding & Generation.
- Specific sub-capabilities: Summarization, content rewriting for tone, action item extraction.
- Application to Navy operations: Enhances efficiency in handling EVALs, FITREPs, and NAVADMIN-related emails, ensuring clear, rank-appropriate language.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Summarize this email thread about award nominations.
```
- What this prompt does: Provides a high-level overview of the thread.
- Output example: "The thread discusses nominations for Sailor of the Quarter, including submissions from departments."
- Limitations: Lacks detail on action items or Navy-specific context, resulting in generic output.

##### Iteration 2: Add Context
```
Summarize this email thread about quarterly award nominations for Sailor of the Quarter at Naval Station Norfolk, including key personnel involved like department heads and the XO.
```
- How context improves output: Incorporates Navy ranks and locations for more relevant summaries.
- Comparison to iteration 1: Adds specificity, making the output actionable for N1 personnel.

##### Iteration 3: Add Specificity
```
Summarize this email thread about quarterly award nominations: Extract action items, deadlines, and responsible parties (e.g., Department Heads, CMC). Rewrite in professional naval tone suitable for an E-5 Petty Officer reporting to O-3 Lieutenant.
```
- Why specificity matters: Ensures structured output with deadlines and tones aligned to chain of command.
- Improved output quality: Includes bullet points for actions, reducing miscommunication.

##### Iteration 4: Final Optimized Prompt
```
Summarize the following email thread on Sailor of the Quarter nominations: List action items with deadlines (e.g., submission by 15 OCT), responsible ranks/parties (e.g., PO1 Smith, LCDR Jones), and draft a response email in formal Navy style acknowledging receipt and confirming next steps.
```
- Final refinements: Combines summarization with generation for complete workflow.
- Complete output example: Summary with bullets; drafted email: "Sir, Acknowledging receipt of nominations. Action items: PO2 compile packages by COB Friday."

#### Technical Steps
1. Open Outlook and navigate to a sample email thread on award nominations; copy the thread content.
2. Paste into standalone Copilot Chat and input Iteration 1 prompt; review basic summary.
3. Refine to Iteration 2-4, copying outputs back to Outlook for drafting responses.
4. Expected outputs: Summarized thread (Iteration 1: 1 paragraph), action list (Iteration 3: bullets), full draft (Iteration 4: email body).

#### Facilitation Notes
> 💡 Tips: Monitor for copy/paste errors in long threads; encourage participants to compare iterations verbally.
> ⚠️ Warning: Remind attendees to avoid pasting classified data.
> 💡 Tip: Explain how adding Navy terms like "XO" or "CMC" refines outputs for operational relevance.

#### Expected Outcomes
✅ Specific deliverables: Summarized email with action items; drafted response in Outlook.  
✅ Technical verification: Outputs match prompt refinements without errors.  
✅ Confirmation of Copilot capability: Clear demonstration of language generation for N1 correspondence.  
✅ Clear demonstration of progressive prompt building: 4 iterations showing quality progression.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: Use to build better prompts for complex threads.
- Example: "Help me create an effective prompt to summarize award nomination emails. What Navy-specific details should I include, like ranks and deadlines?"
- When most valuable: For junior Sailors new to prompt engineering in personnel tasks.

##### Chain of Reasoning
- How to apply: Break down summarization logically.
- Example: "Let's work through this step by step: 1) Identify key emails in the thread. 2) Extract personnel and deadlines. 3) Generate summary and draft response."
- When explicit reasoning improves: In ambiguous threads to ensure accurate action items.

##### When to Use
- Guidance: Use complex prompts for high-stakes N1 communications; simple for quick summaries.
- Trade-offs: Basic prompts are faster but less precise; refined ones save time in revisions.
- Real-world Navy scenarios: Processing leave requests or EVAL feedback aboard USS ships.

---

### Scenario 2: Reasoning & Decision Support
Application: Word | Navy Focus: N3 (Operations) | Duration: 20-25 min

#### Scenario Context
Aboard USS Abraham Lincoln (CVN-72) during a deployment workup at Naval Base San Diego, a Lieutenant Junior Grade (O-2) in Operations drafts training plans. This scenario focuses on structuring operation orders with recommendations for scheduling. Participants will create a department training document. This capability is essential for N3 as it aids in mitigating risks and optimizing resources in dynamic operational environments.

#### Copilot Capability Focus
- Primary capability: Reasoning & Decision Support.
- Specific sub-capabilities: Comparative analysis, recommendation generation, decision frameworks.
- Application to Navy operations: Supports watch bill adjustments and mission briefs, ensuring logical prioritization.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Draft a training plan for the department.
```
- What this prompt does: Generates a generic outline.
- Output example: "Sections: Objectives, Schedule, Resources."
- Limitations: Ignores Navy-specific conflicts like watch rotations.

##### Iteration 2: Add Context
```
Draft a department training plan for USS Abraham Lincoln's Operations team, considering watch schedules and personnel qualifications.
```
- How context improves output: Incorporates afloat unit details for relevance.
- Comparison to iteration 1: Adds operational realism, like shift conflicts.

##### Iteration 3: Add Specificity
```
Draft a department training plan: Analyze potential scheduling conflicts with watch bills, provide recommendations for personnel allocation (e.g., E-4 to E-6 Sailors), and include a decision framework for prioritizing quals.
```
- Why specificity matters: Structures output with analysis and options.
- Improved output quality: Includes tables for conflicts and ranked priorities.

##### Iteration 4: Final Optimized Prompt
```
Draft a comprehensive department training plan for N3 Operations: Step-by-step analyze conflicts in watch schedules, recommend mitigations (e.g., rotate E-5 POs), and create a decision matrix comparing training options based on readiness impact.
```
- Final refinements: Adds step-by-step reasoning for deeper support.
- Complete output example: Plan with matrix table; recommendations: "Shift training to off-watch hours to maintain 80% readiness."

#### Technical Steps
1. Open Word and create a new document; outline basic training needs.
2. Copy outline to Copilot Chat; apply Iteration 1 prompt for initial draft.
3. Iterate to 2-4, pasting refined drafts back to Word for editing.
4. Expected outputs: Basic outline (Iteration 1), analyzed plan with recommendations (Iteration 4).

#### Facilitation Notes
> 💡 Tips: Watch for prompt length limits; demonstrate matrix insertion in Word.
> ⚠️ Warning: Ensure no real operational data is used.
> 💡 Tip: Highlight how reasoning reduces errors in N3 planning.

#### Expected Outcomes
✅ Specific deliverables: Structured Word document with decision matrix.  
✅ Technical verification: Recommendations align with prompt inputs.  
✅ Confirmation of Copilot capability: Demonstrates reasoning for operational decisions.  
✅ Clear demonstration of progressive prompt building: Iterations build logical depth.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: For optimizing decision frameworks.
- Example: "Help me create a prompt to draft training plans. What details on watch bills and quals should I add for better recommendations?"
- When most valuable: In complex N3 scenarios with multiple variables.

##### Chain of Reasoning
- How to apply: Explicit steps for analysis.
- Example: "Let's work through this step by step: 1) List training requirements. 2) Identify conflicts. 3) Recommend allocations. 4) Prioritize based on mission impact."
- When explicit reasoning improves: For justifying decisions in readiness reports.

##### When to Use
- Guidance: Use for multifaceted ops planning; simple for basic outlines.
- Trade-offs: Complex prompts yield robust support but require more setup.
- Real-world Navy scenarios: Adjusting watch schedules during exercises at Naval Station Norfolk.

---

### Scenario 3: Data Analysis & Visualization
Application: Excel | Navy Focus: N4 (Logistics) | Duration: 20-25 min

#### Scenario Context
At Naval Base San Diego, a Petty Officer First Class (E-6) in Supply tracks equipment readiness for a surface warfare group. This scenario analyzes CASREP data for patterns in maintenance issues. Participants will interpret supply data and recommend visualizations. This capability is critical for N4 as it identifies logistics bottlenecks, supporting fleet readiness without external tools.

#### Copilot Capability Focus
- Primary capability: Data Analysis & Visualization.
- Specific sub-capabilities: Pattern identification, insight generation, chart recommendations.
- Application to Navy operations: Enhances Ao rate tracking and supply chain efficiency.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Analyze this equipment data.
```
- What this prompt does: Provides simple stats.
- Output example: "Average Ao rate: 85%."
- Limitations: No patterns or visuals mentioned.

##### Iteration 2: Add Context
```
Analyze this CASREP data for ship equipment at Naval Base San Diego, focusing on maintenance issues and Ao rates.
```
- How context improves output: Adds Navy logistics terms for targeted insights.
- Comparison to iteration 1: Includes specific metrics like downtime causes.

##### Iteration 3: Add Specificity
```
Analyze CASREP data: Identify patterns in maintenance issues (e.g., recurring parts failures), generate insights on supply bottlenecks, and recommend Excel visualizations like pie charts for leadership briefs.
```
- Why specificity matters: Directs to actionable outputs with visual suggestions.
- Improved output quality: Lists patterns with chart types.

##### Iteration 4: Final Optimized Prompt
```
Analyze the following CASREP dataset: Step-by-step identify patterns in equipment failures, calculate Ao trends over quarters, provide insights on logistics impacts, and recommend specific Excel charts (e.g., line graph for trends) for N4 reports.
```
- Final refinements: Adds calculations and step-by-step for thorough analysis.
- Complete output example: Patterns: "Radar failures 40%"; Insights: "Supply delay in parts"; Charts: "Use bar chart for failure types."

#### Technical Steps
1. Open Excel with sample CASREP spreadsheet; select data range.
2. Copy data to Copilot Chat; use Iteration 1 for basic analysis.
3. Refine to Iterations 2-4, pasting insights and chart suggestions back to Excel to create visuals.
4. Expected outputs: Basic stats (Iteration 1), full report with charts (Iteration 4).

#### Facilitation Notes
> 💡 Tips: Assist with data pasting; verify chart creation in Excel.
> ⚠️ Warning: Use dummy data only to comply with OPSEC.
> 💡 Tip: Discuss how visualizations aid briefings to CO.

#### Expected Outcomes
✅ Specific deliverables: Excel sheet with analyzed data and charts.  
✅ Technical verification: Insights match dataset patterns.  
✅ Confirmation of Copilot capability: Effective data interpretation for logistics.  
✅ Clear demonstration of progressive prompt building: Builds from stats to visuals.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: For better data queries.
- Example: "Help me create a prompt to analyze CASREP data. What details on Ao rates and patterns should I include?"
- When most valuable: When datasets are large or complex.

##### Chain of Reasoning
- How to apply: Sequential data breakdown.
- Example: "Let's work through this step by step: 1) Calculate Ao averages. 2) Spot failure patterns. 3) Suggest mitigations. 4) Recommend visuals."
- When explicit reasoning improves: For validating logistics insights.

##### When to Use
- Guidance: Complex prompts for trend analysis; simple for quick stats.
- Trade-offs: More detail yields deeper insights but increases prompt time.
- Real-world Navy scenarios: Tracking maintenance aboard USS ships during sustainment.

---

### Scenario 4: Automation & Orchestration
Application: Power Automate | Navy Focus: N6 (Communications & IT) | Duration: 20-25 min

#### Scenario Context
At Naval Station Norfolk, an Information Systems Technician Second Class (E-5) manages NMCI help desk tickets for a command. This scenario designs workflows for ticket routing. Participants will create automation logic for access requests. This capability is vital for N6 as it streamlines IT support in network-constrained environments, reducing resolution times.

#### Copilot Capability Focus
- Primary capability: Automation & Orchestration.
- Specific sub-capabilities: Workflow design, logic optimization, decision point creation.
- Application to Navy operations: Automates SIPR/NIPR access and ticket tracking.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Design a workflow for help desk tickets.
```
- What this prompt does: Outlines simple steps.
- Output example: "Receive ticket, assign, resolve."
- Limitations: No Navy IT specifics or branches.

##### Iteration 2: Add Context
```
Design a workflow for NMCI help desk tickets at Naval Station Norfolk, including routing to tech teams based on issue type.
```
- How context improves output: Adds DoD network terms.
- Comparison to iteration 1: Includes conditional routing.

##### Iteration 3: Add Specificity
```
Design a Power Automate workflow for NMCI tickets: Include logic for priority levels (e.g., urgent for SIPR downtime), notifications to supervisors (e.g., IT1 to LCDR), and tracking resolution times.
```
- Why specificity matters: Defines branches and metrics.
- Improved output quality: Step-by-step flow with conditions.

##### Iteration 4: Final Optimized Prompt
```
Design a detailed Power Automate workflow for processing NMCI help desk tickets: Step-by-step orchestrate routing based on issue (e.g., access request to NIPR team), send notifications, track SLAs, and optimize for efficiency in N6 operations.
```
- Final refinements: Adds optimization and metrics.
- Complete output example: Flow steps: "If urgent, notify CO; Else, assign to PO2; Track time to resolution."

#### Technical Steps
1. Open Power Automate; start a new flow.
2. Copy requirements to Copilot Chat; use Iteration 1 for basic design.
3. Iterate to 2-4, pasting logic back to build the flow.
4. Expected outputs: Simple outline (Iteration 1), full orchestrated flow (Iteration 4).

#### Facilitation Notes
> 💡 Tips: Guide on connector setup; test flows in sandbox.
> ⚠️ Warning: Avoid connecting to real systems.
> 💡 Tip: Emphasize automation's role in reducing N6 workload.

#### Expected Outcomes
✅ Specific deliverables: Functional Power Automate flow for tickets.  
✅ Technical verification: Logic handles branches correctly.  
✅ Confirmation of Copilot capability: Orchestrates IT processes effectively.  
✅ Clear demonstration of progressive prompt building: Evolves from basic to optimized.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: For workflow complexity.
- Example: "Help me create a prompt to design NMCI workflows. What logic and notifications should I specify?"
- When most valuable: For troubleshooting intricate automations.

##### Chain of Reasoning
- How to apply: Logical flow breakdown.
- Example: "Let's work through this step by step: 1) Receive ticket. 2) Classify issue. 3) Route and notify. 4) Track and close."
- When explicit reasoning improves: In optimizing decision points.

##### When to Use
- Guidance: Complex for branched workflows; simple for linear.
- Trade-offs: Detailed prompts ensure robustness but may overwhelm beginners.
- Real-world Navy scenarios: Automating access requests on USS ships.

---

### Scenario 5: Search & Retrieval
Application: Power BI | Navy Focus: N2 (Intelligence) | Duration: 20-25 min

#### Scenario Context
Aboard USS Gerald R. Ford (CVN-78) at Naval Station Norfolk, an Intelligence Specialist Third Class (E-4) organizes threat assessments from dashboards. This scenario extracts key indicators from intelligence reports. Participants will consolidate data into briefs. This capability is key for N2 as it enables quick information retrieval in offline settings, supporting IPOE.

#### Copilot Capability Focus
- Primary capability: Search & Retrieval.
- Specific sub-capabilities: Data extraction, information organization, content consolidation.
- Application to Navy operations: Streamlines threat summaries and brief preparation.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Find threat indicators in this report.
```
- What this prompt does: Lists basic items.
- Output example: "Indicators: Vessel movements, cyber threats."
- Limitations: No structure or Navy context.

##### Iteration 2: Add Context
```
Search this intelligence dashboard for threat indicators related to maritime operations in the Indo-Pacific, as per N2 summaries.
```
- How context improves output: Focuses on regional threats.
- Comparison to iteration 1: Adds operational relevance.

##### Iteration 3: Add Specificity
```
Search and retrieve from the Power BI dashboard: Extract specific threat indicators (e.g., adversary ship positions), organize into categories (e.g., kinetic, cyber), and create a structured summary for command brief.
```
- Why specificity matters: Ensures categorized output.
- Improved output quality: Bullet lists by type.

##### Iteration 4: Final Optimized Prompt
```
Search the following Power BI intelligence data: Retrieve and organize threat indicators step-by-step (e.g., from IPOE reports), extract critical points like timelines and sources, and consolidate into a brief format suitable for O-2 to O-4 Officers.
```
- Final refinements: Adds extraction details and format.
- Complete output example: Categorized list: "Kinetic: Enemy subs at coords; Cyber: Phishing alerts; Summary brief."

#### Technical Steps
1. Open Power BI with sample dashboard; export data view.
2. Copy data to Copilot Chat; apply Iteration 1 for initial extraction.
3. Refine to 2-4, pasting organized info back to Power BI or Word for brief.
4. Expected outputs: Basic list (Iteration 1), structured brief (Iteration 4).

#### Facilitation Notes
> 💡 Tips: Help with data export; verify extraction accuracy.
> ⚠️ Warning: Use unclassified sample data only.
> 💡 Tip: Show how retrieval speeds N2 briefings.

#### Expected Outcomes
✅ Specific deliverables: Organized threat brief from dashboard data.  
✅ Technical verification: Extracted points match source.  
✅ Confirmation of Copilot capability: Efficient search in intelligence tools.  
✅ Clear demonstration of progressive prompt building: From list to consolidated format.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: For precise searches.
- Example: "Help me create a prompt to extract threats from dashboards. What categories and details should I include?"
- When most valuable: In voluminous N2 reports.

##### Chain of Reasoning
- How to apply: Stepwise extraction.
- Example: "Let's work through this step by step: 1) Scan for indicators. 2) Categorize by type. 3) Extract timelines. 4) Organize summary."
- When explicit reasoning improves: For ensuring comprehensive retrieval.

##### When to Use
- Guidance: Complex for detailed organization; simple for quick finds.
- Trade-offs: Specificity reduces omissions but increases prompt complexity.
- Real-world Navy scenarios: Compiling daily intel briefs aboard carriers.

---

### Scenario 6: Personalization & Context Awareness
Application: Teams | Navy Focus: N1 (Manpower & Personnel) | Duration: 20-25 min

#### Scenario Context
At Naval Base San Diego, a Chief Petty Officer (E-7) coordinates promotion boards for a logistics command. This scenario summarizes meetings and generates follow-ups adapted to ranks. Participants will create context-aware agendas. This capability is crucial for N1 as it tailors communications to chain of command, enhancing personnel management.

#### Copilot Capability Focus
- Primary capability: Personalization & Context Awareness.
- Specific sub-capabilities: Terminology adaptation, role-specific suggestions, contextual summarization.
- Application to Navy operations: Customizes EVAL/FITREP discussions and follow-ups.

#### Progressive Prompt Building
##### Iteration 1: Basic Prompt
```
Summarize this meeting notes.
```
- What this prompt does: General overview.
- Output example: "Discussed promotions and tasks."
- Limitations: No Navy ranks or context.

##### Iteration 2: Add Context
```
Summarize meeting notes from promotion board planning at Naval Base San Diego, using Navy terminology like EVALs and chain of command.
```
- How context improves output: Incorporates naval terms.
- Comparison to iteration 1: More relevant to personnel.

##### Iteration 3: Add Specificity
```
Summarize promotion board meeting notes: Adapt language for ranks (e.g., formal for O-3, instructional for E-4), generate follow-up messages, and ensure context awareness of NSIPS updates.
```
- Why specificity matters: Personalizes for audience.
- Improved output quality: Rank-tailored summaries.

##### Iteration 4: Final Optimized Prompt
```
Summarize the following promotion board meeting notes with personalization: Use Navy-specific terms (e.g., FITREPs, detailing), create context-aware agendas for next meeting, and draft follow-up messages adapted to recipients (e.g., respectful tone for CMC, directive for PO3).
```
- Final refinements: Adds agenda and messages.
- Complete output example: Summary with terms; Follow-up: "BMC, Please review EVALs by 10 OCT."

#### Technical Steps
1. Open Teams; access sample meeting transcript.
2. Copy notes to Copilot Chat; use Iteration 1 for basic summary.
3. Iterate to 2-4, pasting personalized outputs back to Teams for messages/agendas.
4. Expected outputs: Generic summary (Iteration 1), tailored follow-ups (Iteration 4).

#### Facilitation Notes
> 💡 Tips: Demonstrate Teams integration via copy/paste.
> ⚠️ Warning: No real personnel data.
> 💡 Tip: Stress personalization's role in N1 communications.

#### Expected Outcomes
✅ Specific deliverables: Personalized Teams messages and agendas.  
✅ Technical verification: Outputs reflect rank adaptations.  
✅ Confirmation of Copilot capability: Context-aware for personnel tasks.  
✅ Clear demonstration of progressive prompt building: From basic to personalized.

#### Discussion Points
##### Meta-Prompting
- How meta-prompting could enhance: For adaptive prompts.
- Example: "Help me create a prompt to summarize meetings. What rank and terminology details should I add for personalization?"
- When most valuable: In diverse N1 teams.

##### Chain of Reasoning
- How to apply: Step-by-step adaptation.
- Example: "Let's work through this step by step: 1) Summarize key points. 2) Identify recipients. 3) Adapt tone per rank. 4) Generate messages."
- When explicit reasoning improves: For nuanced communications.

##### When to Use
- Guidance: Complex for rank-specific tasks; simple for general summaries.
- Trade-offs: Personalization ensures appropriateness but requires more input.
- Real-world Navy scenarios: Follow-ups after advancement boards on installations.

---

## Quick Reference

### Summary Table of All 6 Scenarios
| Scenario | Capability | Application | Navy Focus | Duration |
|----------|------------|-------------|------------|----------|
| 1 | Language Understanding & Generation | Outlook | N1 (Manpower & Personnel) | 20-25 min |
| 2 | Reasoning & Decision Support | Word | N3 (Operations) | 20-25 min |
| 3 | Data Analysis & Visualization | Excel | N4 (Logistics) | 20-25 min |
| 4 | Automation & Orchestration | Power Automate | N6 (Communications & IT) | 20-25 min |
| 5 | Search & Retrieval | Power BI | N2 (Intelligence) | 20-25 min |
| 6 | Personalization & Context Awareness | Teams | N1 (Manpower & Personnel) | 20-25 min |

### Progressive Prompt Building Tips
- Start basic: Focus on core task.
- Add context: Include Navy specifics (ranks, locations, terms).
- Specify outputs: Request formats (bullets, tables), tones, structures.
- Optimize: Incorporate steps or refinements for precision.
> 💡 Tip: Always compare iterations to show improvements.

### Key Talking Points for Each Copilot Capability
- **Language Understanding & Generation**: Ideal for drafting and summarizing naval correspondence; adjust tone for ranks.
- **Reasoning & Decision Support**: Provides frameworks for ops planning; mitigates risks in schedules.
- **Data Analysis & Visualization**: Uncovers logistics patterns; suggests charts for briefs.
- **Automation & Orchestration**: Builds IT workflows; optimizes N6 processes.
- **Search & Retrieval**: Extracts intel data; organizes for quick access.
- **Personalization & Context Awareness**: Tailors to Navy context; respects chain of command.

### Meta-Prompting and Chain of Reasoning Quick Reference
- **Meta-Prompting**: "Help me craft a prompt for [task]. Suggest key details like [Navy terms]."
  - Use when: Starting complex scenarios.
- **Chain of Reasoning**: "Step by step: 1) [Action], 2) [Analysis], 3) [Output]."
  - Use when: Needing logical breakdowns for accuracy.

### Common Questions with Answers
- Q: Why no web search? A: DoD environments prohibit it for security.
- Q: How to handle errors? A: Refine prompts; check copy/paste.
- Q: Can I use integrated Copilot? A: No, only standalone Chat.

### Troubleshooting Common Issues
- **Prompt Too Vague**: Add specifics; retry iteration.
- **Output Irrelevant**: Include more Navy context.
- **Copy/Paste Fails**: Use text-only; avoid images.
- **App Integration**: Ensure offline mode; test workflows.
> ⚠️ Warning: Restart Copilot Chat if unresponsive.

### Additional Learning Resources
- [Microsoft Learn: Copilot Chat Fundamentals](https://learn.microsoft.com/en-us/copilot/chat)
- [Microsoft Learn: Prompt Engineering Basics](https://learn.microsoft.com/en-us/training/modules/prompt-engineering)
- Navy-specific: Review NAVADMIN on AI Tools (unclassified versions).