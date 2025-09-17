# Lesson 4: Analyzing Stakeholder Interviews (20 minutes)

**Objective:** Systematically analyze stakeholder conversations to extract PRD-ready insights, combining AI simulation experience with real transcript analysis to develop comprehensive stakeholder intelligence.

**Learning Outcome:** Master systematic stakeholder data analysis and insight synthesis that directly supports strategic PRD development and identifies information gaps for complete requirements gathering.

---

## Step 1: Generate Analysis Framework for Simulation Insights (8 minutes)

### Step 1A: Create RCTO Analysis Prompt (4 minutes)

**Using your interview simulation experience from Lesson 3, type this prompt:**

```
ROLE: [What type of expertise do we need for this research?]

CONTEXT: [What background should the AI understand about our situation?]

TASK: [What specific deliverables do we need?]

OUTPUT FORMAT: [What structure would be most useful for our discovery meeting preparation?]

—
Write a prompt following the structure above for this topic:
Analyze the stakeholder interview transcript and extract insights that can be used to populate a PRD (Product Requirements Document).

<PRD>
### TL;DR
Write a clear, concise 2–3 sentence summary describing the problem, core benefits, basic features, and intended audience.

---

## Goals
### Business Goals
List 3–5 measurable objectives aligned to company/business priorities.

### User Goals
List 3–5 key user outcomes or benefits. Focus on solving real user needs.

### Non-Goals
List 2–3 items that are not in scope for this project. Be explicit to avoid scope creep.

---

## User Stories
For each user persona (real roles, e.g., Customer, Support Agent), provide multiple user stories in the following format:
- As a <USER TYPE>, I want to <ACTION>, so that <BENEFIT>.

---

## Functional Requirements
List features and requirements, grouped by product area and prioritized.
- <Feature Group> (Priority: <PRIORITY>)
  -- <Feature Name:> <Short feature description>

---

## User Experience
Provide a detailed, stepwise journey through the product:
- Entry Point & First-Time User Experience: Describe first access and onboarding.
- Core Experience: Describe main flows step by step from user perspective, including UI/UX and data/validation.
- Advanced Features & Edge Cases: Address power-users and error conditions.
- UI/UX Highlights: List key accessibility or design priorities.

---

## Narrative
Craft a 200–300 word story illustrating a typical user's challenge, how the product helps, and the final outcome—emphasizing both business and end-user wins.

---

## Success Metrics
List 4–6 clear measures of success, and organize into the following groups:
### User-Centric Metrics
### Business Metrics
### Technical Metrics
### Tracking Plan

---

## Technical Considerations
Outline the most relevant implementation challenges and factors:
- Technical Needs: APIs, data models, components.
- Integration Points: Existing systems or 3rd parties.
- Data Storage & Privacy: Data flow and compliance.
- Scalability & Performance: Key demands and projections.
- Potential Challenges: Risks or complexities to consider.

---

## Milestones & Sequencing
Provide an actionable, pragmatic roadmap:
- Project Estimate: Use startup-friendly (not enterprise) timeframes (Extra-small, Small, Medium, Large).
- Team Size & Composition: Keep teams lean. Prefer 1–2 people for small projects.
- Suggested Phases: Name each phase, its duration, deliverables, and dependencies.
</PRD>
```

**AI will generate a comprehensive RCTO framework for systematic stakeholder analysis aligned with PRD template requirements.**

### Step 1B: Analyze Your Interview Simulation (4 minutes)

**Use the AI-generated RCTO prompt to analyze your Lesson 3 simulation experience.**

**Include in your analysis:**
- **Context from Lesson 3:** Stakeholder personality you chose, key responses, adaptation moments
- **Simulation insights:** What you learned about stakeholder needs, concerns, and priorities
- **Interview quality:** What worked well and what you would improve

**Expected Output:**
- Insights organized by PRD section based on your simulation
- Identification of strong findings vs. areas needing more information
- Comparison between different stakeholder personality approaches (if you tried multiple)

---

## Step 2: Analyze Real Stakeholder Transcript (12 minutes)

### Step 2A: Apply Framework to Real Data (12 minutes)

**Download the real stakeholder transcript from:** [student/transcript.txt](../student/transcript.txt)

**Now apply the same analysis framework to the real stakeholder conversation by attaching the transcript to the chat and repurposing the previous prompt to analyze the interview.

**Key Analysis Areas:**

**Look for in the transcript:**
- **Pain Points:** Current challenges and frustrations mentioned
- **Success Criteria:** How stakeholders define improvement or success
- **User Types:** Different customer segments and their needs
- **Technical Context:** Existing systems, tools, and constraints
- **Business Priorities:** What matters most to the organization
- **Process Insights:** Current workflows and desired improvements

**After completing your transcript analysis, also add this synthesis prompt:**

```
Based on both my interview simulation experience and analysis of the real Apogee Digital transcript:

1. Compare and contrast insights from simulation vs. real stakeholder data
2. Identify which PRD sections have strong information and which need more discovery
3. Highlight any contradictions or areas where stakeholder needs are unclear
4. Recommend specific follow-up questions for areas with insufficient information
5. Assess readiness to begin PRD development based on available stakeholder insights
```

---

## Lesson 4 Deliverable

**You should now have:**
1. **Analysis Framework Mastery:** RCTO prompt for systematic stakeholder interview analysis
2. **Simulation Insights Analysis:** Organized insights from your AI interview practice experience
3. **Real Transcript Analysis:** Comprehensive analysis of actual Apogee Digital stakeholder conversation
4. **PRD Readiness Assessment:** Clear understanding of information completeness for each PRD section
5. **Gap Identification:** Specific areas requiring additional stakeholder input or validation

---

## Self-Assessment Questions

- Can I systematically extract insights from stakeholder conversations and organize them by PRD sections?
- Do I understand the difference between direct stakeholder statements and implied needs?
- Can I identify information gaps that require additional discovery before PRD completion?
- Am I able to synthesize insights from multiple stakeholder sources (simulation + real transcript)?
- Do I have sufficient information to begin comprehensive PRD development, or do I need additional stakeholder input?

---

## Advanced Analysis (Optional)

**If time permits, conduct additional analysis:**

### Stakeholder Validation Readiness
- **Type:** "Based on my analysis, create a validation plan for confirming these insights with Apogee Digital stakeholders before finalizing the PRD"
- **Focus:** Which findings need stakeholder confirmation vs. which seem well-established

### Competitive Context Integration
- **Type:** "How do the stakeholder insights align with or differ from industry best practices for customer service automation in B2B technical companies?"
- **Focus:** Unique vs. common challenges and solution approaches

---

**Workshop Completion:** Your comprehensive stakeholder analysis provides the foundation needed for PRD development. The systematic insights you've gathered and organized by ChatPRD template sections prepare you for strategic product requirements documentation in future coursework or professional contexts.