# Microsoft 365 Copilot Chat Quick Reference Guide
## USMC Workshop Cheat Sheet

**Classification:** UNCLASSIFIED  
**Version:** October 2025  
**Environment:** DoD Cloud (Web search grounding disabled via policy – default off unless explicitly enabled)

---

## 🎯 Quick Start

### What You Need
- Microsoft 365 license that includes Copilot Chat (E3/E5, F3, etc.)
- Microsoft 365 Copilot license (add-on) for work data grounding inside Microsoft 365 apps (recommended for richer in-app experiences)
- Web browser access to Microsoft 365 Copilot Chat (web-only in DoD/GCC High)
- DoD cloud tenant (Copilot Chat rollout in DoD Q3 CY25; GCC High availability planned—verify current tenant status)

### How to Access
1. Navigate to **m365.cloud.microsoft/chat** (copilot.cloud.microsoft redirects here) or open the Microsoft 365 Copilot web app
2. Sign in with your Microsoft Entra ID (DoD account)
3. Provide context by pasting, uploading, or referencing files with "/" (ContextIQ). Without a Microsoft 365 Copilot license, Copilot Chat responses are web-grounded only unless you supply content directly.

---

## 📝 The Golden Rule of Prompting

### Progressive Prompt Framework
Build prompts in **4 iterations** for best results:

1. **Basic** → Simple request (gets generic output)
2. **+ Context** → Add location, organization, purpose
3. **+ Specificity** → Define format, structure, audience
4. **+ Optimization** → Include role, regulations, constraints

### Formula for Great Prompts
```
As a [ROLE] at [LOCATION], [ACTION]: [SPECIFIC REQUIREMENTS], 
[FORMAT PREFERENCES], [CONSTRAINTS/REGULATIONS].
```

**Example:**
```
As an S-1 clerk at Camp Lejeune, summarize this email thread 
on award nominations: List participants by rank, extract action 
items and deadlines, draft a response to the CO with formal 
USMC language, ensuring compliance with MCO 1650.19.
```

---

## 🛠️ Six Copilot Capabilities

### 1. Language Understanding & Generation
**Use For:** Email drafts, summaries, tone adjustment  
**Apps:** Outlook, Word, Teams  
**USMC Examples:**
- Award nomination summaries
- FITREP correspondence
- Leave authorization requests
- Meeting minutes

**Key Phrases:**
- "Summarize this email thread..."
- "Draft a response to [RANK/POSITION]..."
- "Adjust tone to be [formal/professional/brief]..."
- "Extract action items and deadlines..."

---

### 2. Reasoning & Decision Support
**Use For:** Planning, conflict resolution, recommendations  
**Apps:** Word, PowerPoint  
**USMC Examples:**
- Training schedule OPORDs
- Resource allocation conflicts
- Risk assessments
- Priority frameworks

**Key Phrases:**
- "Analyze conflicts in [SCENARIO]..."
- "Recommend priorities based on [CRITERIA]..."
- "Structure this as a 5-paragraph order..."
- "Identify overlaps and suggest alternatives..."

---

### 3. Data Analysis & Visualization
**Use For:** Trend identification, chart recommendations  
**Apps:** Excel  
**USMC Examples:**
- Equipment readiness (CMR) tracking
- Supply chain analysis
- Maintenance pattern detection
- Budget reports

**Key Phrases:**
- "Analyze this data for patterns..."
- "Calculate readiness rates..."
- "Suggest visualizations for [PURPOSE]..."
- "Identify bottlenecks in [PROCESS]..."

---

### 4. Automation & Orchestration
**Use For:** Workflow design, process optimization  
**Apps:** Power Automate  
**USMC Examples:**
- Help desk ticket routing
- Access request workflows
- Approval processes
- Notification systems

**Key Phrases:**
- "Design a workflow for [PROCESS]..."
- "Create branching logic for [CONDITIONS]..."
- "Optimize this flow for [CRITERIA]..."
- "Troubleshoot errors in [WORKFLOW]..."

**Note:** Copilot in Power Automate can draft initial flow steps (supported action groups). Review, configure connections, and refine—treat output as a starting point, not final production logic.

---

### 5. Search & Retrieval
**Use For:** Data extraction, organization, consolidation  
**Apps:** Power BI, SharePoint, OneDrive  
**USMC Examples:**
- INTSUM compilation
- Threat indicator extraction
- Report consolidation
- Dashboard interpretation

**Key Phrases:**
- "Extract [DATA TYPE] from this content..."
- "Organize by [CATEGORY/PRIORITY]..."
- "Create a structured brief on [TOPIC]..."
- "Find and categorize [INFORMATION]..."

**Note:** If Copilot in Power BI isn’t enabled for your workspace/capacity, export or describe data. When enabled (and licensed), Copilot can summarize/interpret accessible reports—subject to permissions and row/visual limits.

---

### 6. Personalization & Context Awareness
**Use For:** Rank-appropriate communication, audience adaptation  
**Apps:** Teams, Outlook  
**USMC Examples:**
- Promotion board summaries
- Chain of command correspondence
- Meeting agendas
- Personnel announcements

**Key Phrases:**
- "Adapt language for [RANK RANGE] audience..."
- "Use USMC terminology and [REFERENCE]..."
- "Personalize follow-ups by rank..."
- "Demonstrate context awareness of [UNIT STRUCTURE]..."

---

## 🚀 Advanced Techniques

### Meta-Prompting
Ask Copilot to help build better prompts:
```
"Help me create an effective prompt to [TASK]. 
What details should I include?"
```

### Chain of Reasoning
Break complex tasks into steps:
```
"Let's work through this step by step:
1) [FIRST STEP]
2) [SECOND STEP]
3) [THIRD STEP]
4) [FINAL STEP]"
```

### Provide Examples
Show Copilot what you want:
```
"Create a summary similar to this format:
- Key Point 1: [Details]
- Key Point 2: [Details]
Now summarize the following..."
```

---

## 📋 USMC Context Checklist

When prompting, include these elements for best results:

✅ **Rank/Position** - Your role (e.g., "As an S-4 logistician...")  
✅ **Location** - Base/installation (e.g., "at Camp Pendleton...")  
✅ **Unit Context** - Section/MOS (e.g., "S-1/S-2/S-3/S-4/S-6...")  
✅ **Audience** - Who will read this? (e.g., "for the CO...")  
✅ **Format** - Desired structure (e.g., "5-paragraph order...")  
✅ **Regulations** - Applicable orders (e.g., "per MCO 1650.19...")  
✅ **Terminology** - Use USMC-specific terms (OPORD, FRAGO, INTSUM, FITREP, T&R)

---

## 🔧 Troubleshooting

| Problem | Solution |
|---------|----------|
| **Vague/generic output** | Add more USMC context, ranks, locations |
| **Missing key details** | List specific information needed in prompt |
| **Wrong tone** | Specify audience and formality level |
| **Incomplete analysis** | Use "step by step" chain of reasoning |
| **Copy/paste fails** | Check window focus; try file upload instead |
| **File upload fails** | Use copy/paste as fallback method |
| **No access to feature** | Verify Copilot add-on license assigned |

---

## 📊 Quick Reference: Staff Section Use Cases

### S-1 (Admin/Personnel)
- Award nominations, FITREPs, leave requests
- Promotion board summaries, personnel announcements
- Meeting agendas, correspondence management

### S-2 (Intelligence)
- INTSUM compilation, threat assessments
- IPB preparation, recon reports
- Dashboard data extraction

### S-3 (Operations)
- Training OPORDs, FRAGOs, scheduling
- Resource conflict resolution
- Readiness reporting

### S-4 (Logistics)
- Equipment readiness (CMR) analysis
- Supply chain bottlenecks
- Maintenance tracking, budget reports

### S-6 (Communications)
- Help desk workflows, ticket routing
- Access request automation
- SOP documentation

---

## 💡 Pro Tips

1. **Start Simple, Then Iterate** - Don't try to write the perfect prompt first. Build progressively.

2. **Copy Successful Prompts** - Save prompts that work well for reuse.

3. **Provide Context First** - Upload files, paste content, or reference a file with "/" before asking questions.

4. **Be Specific About Format** - Tell Copilot exactly how you want output structured.

5. **Use Military Terms** - Copilot understands USMC terminology when you use it.

6. **Reference Regulations** - Mention MCOs, MARADMINs, T&R manuals for authenticity.

7. **Verify Output** - Always review Copilot's work before using it officially.

8. **Iterate If Needed** - Refine prompts based on initial results.

9. **Combine Capabilities** - Use multiple Copilot features together (e.g., summarize + draft response).

10. **Stay UNCLASSIFIED** - Only input unclassified information into Copilot.

---

## 🔒 Security Reminders

- ⚠️ **NEVER** input classified information
- ⚠️ **NEVER** include PII or sensitive data
- ⚠️ Web search (web grounding) disabled via policy (default OFF in DoD unless enabled by admin)
- ⚠️ All content stays within M365 tenant boundary
- ⚠️ Prompts/responses logged for audit/eDiscovery
- ⚠️ Follow your unit's information handling procedures

---

## 📚 Additional Resources

 - **Microsoft Learn - Copilot Fundamentals**  
   https://learn.microsoft.com/en-us/microsoft-copilot/

 - **Microsoft Learn - Prompt Engineering** (supports iterative context, specificity, role framing)  
   https://learn.microsoft.com/en-us/training/modules/engineer-copilot-prompts/

 - **Microsoft Learn - Copilot Feature Availability (Gov/DoD)**  
   https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-platform-service-description/microsoft-365-copilot#feature-availability

- **Internal:** MCTIMS M365 Training Modules

---

## 🎓 Workshop Scenarios Recap

| # | Scenario | Capability | Application | Duration |
|---|----------|------------|-------------|----------|
| 1 | Email Management | Language & Generation | Outlook | 20-25 min |
| 2 | OPORD Planning | Reasoning & Decision | Word | 20-25 min |
| 3 | Equipment Analysis | Data & Visualization | Excel | 20-25 min |
| 4 | Ticket Workflows | Automation | Power Automate | 20-25 min |
| 5 | Intel Extraction | Search & Retrieval | Power BI | 20-25 min |
| 6 | Meeting Summaries | Personalization | Teams | 20-25 min |

---

## ✅ Post-Workshop Action Items

- [ ] Bookmark M365 Copilot Chat in your browser
- [ ] Save your favorite prompts for reuse
- [ ] Identify 3 tasks where Copilot could save you time
- [ ] Share learnings with your unit
- [ ] Practice with real (unclassified) work scenarios
- [ ] Provide feedback to your S-6 on needed features
- [ ] Continue exploring Copilot capabilities

---

**Questions?** Contact your unit's S-6 or IT support desk.

**Semper Fi!** 🦅

---

*This cheat sheet is based on the USMC Copilot Chat Hands-On Workshop.*  
*Keep this reference handy for daily Copilot use.*
