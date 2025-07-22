# AI Workshop Prompts Cheatsheet

A comprehensive reference guide for all workshop prompts and techniques.

## 🎯 Quick Navigation
- [Chat 01: Basic to Intermediate Prompts](#chat-01-basic-to-intermediate-prompts)
- [Chat 02: Deep Research](#chat-02-deep-research)
- [Chat 03: Elevator Pitches](#chat-03-elevator-pitches)
- [Chat 04: AI Coding Agents](#chat-04-ai-coding-agents)
- [Essential Components](#essential-components)
- [Best Practices](#best-practices)

---

## Chat 01: Basic to Intermediate Prompts

### 📋 Essential Prompt Components

| Component | Purpose | Impact |
|-----------|---------|---------|
| **ROLE** | Define who the AI should be | Sets expertise level and perspective |
| **CONTEXT** | Provide background information | Ensures relevant and accurate responses |
| **TASK** | Specify what you want done | Creates clear objectives and deliverables |
| **EXAMPLES** | Show desired output format | Improves consistency and quality |
| **FORMAT** | Define structure requirements | Ensures usable output format |
| **TONE** | Set communication style | Matches audience and purpose |
| **MODELS** | Specify AI capabilities needed | Optimizes for specific strengths |
| **FILES** | Reference relevant documents | Provides context and constraints |
| **TOOLS** | Define available resources | Enables enhanced functionality |

### 🚀 The Evolution: Basic to Sophisticated

#### Level 1: Basic Question
```markdown
What are the SDGs?
```

#### Level 2: Context-Driven Approach
```markdown
I'm building a web application to address an SDG. Ask me three questions, one question at a time, to help me identify which SDG to work on.
```

#### Level 3: Structured Prompt
```markdown
ROLE: 
You are an expert career counselor whose goal is to help high school students:
- Increase their curiosity  
- Nurture their creativity
- Identify real-world problems they deeply care about

CONTEXT:
The student is assigned a project to develop a web application that addresses an SDG (Sustainable Development Goal).

TASK: 
Assist the student in selecting an SDG that aligns with their values and interests.
Ask three multiple-choice questions, one at a time. 
After the student answers all three, use their responses to recommend the most relevant SDG, along with one or two related SDGs they may also consider.

TONE: 
Your tone should be encouraging, clear, and thought-provoking. Prioritize helping the student feel excited and confident about the issue they want to work on.
```

---

## Chat 02: Deep Research

### 🔍 Deep Research Overview

Deep Research is an advanced AI feature that:
- **Multi-Step Investigation**: Breaks down complex topics into systematic research phases
- **Source Discovery**: Actively searches and evaluates multiple authoritative sources
- **Critical Analysis**: Synthesizes information from diverse perspectives
- **Comprehensive Reporting**: Produces detailed, well-structured research reports with citations

### 🛠️ Research Process

1. **Create a new chat** (fresh context)
2. **Access Tools menu**
3. **Select Deep Research**
4. **Input your refined research question**
5. **Validate sources** thoroughly

### 💰 Current Pricing & Access (2025)

| Tier | Monthly Cost | Full Deep Research | Lightweight Version |
|------|--------------|-------------------|---------------------|
| **Free** | $0 | 0 | 5/month |
| **Plus, Team, Enterprise, Edu** | $20 | 10/month | 15/month |
| **Pro** | $200 | 125/month | 125/month |

### 🚀 Available Platforms
- **OpenAI (ChatGPT)** ✅ Full Deep Research + Lightweight
- **Anthropic (Claude)** ✅ Research capabilities
- **Google (Gemini)** ✅ Research tools

---

## Chat 03: Elevator Pitches

### 🎯 Key Requirements
- **Concise**: One compelling sentence
- **Clear**: Easily understood by any audience
- **Compelling**: Motivates action or interest
- **Connected**: Tied to real impact

### 📝 Step-by-Step Development

#### Step 1: Define ROLE
```markdown
What is an effective ROLE I can assign to an LLM to support me in building a web application that addresses SDG 4?
Output in markdown in this format:
### ROLE:
{{ROLE}}
```

#### Step 2: Build Rich CONTEXT
```markdown
I'm building a web application to address an SDG. Summarize how I arrived at SDG 4 based on how I responded to the questions from the career counselor. Output in markdown, in the first person voice, and in this format:
### CONTEXT:
{{CONTEXT}}
```

#### Step 3: Define TASK
```markdown
### TASK:
Create a 1-sentence elevator pitch for this SDG-focused web application.
```

#### Step 4: Add EXAMPLES
```markdown
### EXAMPLES:
Use the [framework name] framework to create this elevator pitch.
```

#### Step 5: Experiment with TONE
```markdown
### TONE:
Rewrite the pitch with a professional but passionate tone about social impact.
```

### 🔄 Refinement Process

#### Critical Feedback
```markdown
Give RUTHLESSLY HONEST feedback on this pitch and identify blind spots.
```

#### Generate Options
```markdown
Give me 5 elevator pitch options with pros and cons for each. Output in a table.
```

#### Final Decision
```markdown
Make a final recommendation with evidence, then provide the final 1-sentence elevator pitch.
```

---

## Chat 04: AI Coding Agents

### 🎯 Understanding the Task
**Goal**: Create an optimized prompt for AI coding agents to build your landing page.

**Process**:
1. **In Chat 04 (ChatGPT/Claude)**: Build comprehensive prompt
2. **Then in Lovable/Bolt**: Submit that prompt to generate landing page

### 🤖 Recommended AI Coding Platforms
- **[Lovable](https://lovable.dev)** ⭐ **RECOMMENDED** - Rapid web app prototyping
- **[Bolt.new](https://bolt.new)** - Full-stack development with real-time preview
- **[Replit](https://replit.com)** - Collaborative coding environment
- **[Cursor](https://cursor.com)** - AI-powered IDE
- **[Claude Code](https://claude.ai/code)** - AI development environment

### 🚀 Complete Coding Prompt Template

```markdown
ROLE: You are an expert full-stack developer and UX/UI designer specializing in social impact startup landing pages.

CONTEXT:
- SDG Focus: [Your chosen SDG]
- Elevator Pitch: [Your refined pitch from Chat 03]
- Target Audience: [From Chat 01 analysis]
- Research Insights: [Key findings from Chat 02]
- Design Reference: [Describe uploaded UI mockup]
- Purpose: Startup pitch competition demo

TASK: Create a compelling, responsive landing page that showcases my SDG-focused web application with hero section, problem/solution explanation, key features, impact demonstration, and strong call-to-action.

EXAMPLES: Follow successful startup landing page patterns (Stripe, Notion-style) with clear value proposition, social proof, and conversion optimization.

OUTPUT FORMAT: Complete HTML/CSS/JavaScript code with component structure, responsive design, and detailed implementation comments.

TONE: Professional, innovative, impact-focused, with clear technical specifications and no ambiguity.

Generate the complete landing page code now.
```

### 📊 Quality Evaluation

#### ✅ What to Look For (Good)
- **Design Quality**: Clean, modern, professional appearance
- **Content Integration**: Elevator pitch and SDG focus clearly communicated
- **Technical Implementation**: Responsive, accessible, fast-loading
- **User Experience**: Intuitive navigation and clear call-to-actions
- **Brand Consistency**: Aligns with SDG mission and target audience

#### ❌ What to Flag (Needs Improvement)
- **Generic Content**: Placeholder text not customized to your project
- **Poor Responsiveness**: Doesn't work well on mobile devices
- **Unclear Value Proposition**: Elevator pitch not prominently featured
- **Missing SDG Connection**: Impact and alignment not clearly communicated
- **Technical Issues**: Broken links, slow loading, accessibility problems

---

## Essential Components

### 🎭 ROLE Examples
- Expert startup pitch coach specializing in social impact ventures
- Venture capitalist focused on SDG investments
- Social impact consultant with startup experience
- Career counselor specializing in purpose-driven entrepreneurship
- Expert full-stack developer and UX/UI designer

### 🌍 CONTEXT Components
- **Your Journey**: How you arrived at your SDG choice
- **Research Foundation**: Key findings from deep research
- **Target Audience**: Who you're building for
- **Technical Requirements**: Platform, timeline, constraints
- **Visual Design Reference**: UI mockups or design inspiration

### 🎯 TASK Variations
- Create a 1-sentence elevator pitch
- Generate 5 elevator pitch options with pros/cons
- Build a responsive landing page
- Conduct deep research on SDG implementation
- Ask clarifying questions to understand user needs

### 📚 EXAMPLES Frameworks
- **Problem-Solution-Impact**: Structure for elevator pitches
- **Startup Landing Page**: Hero, social proof, features, CTA
- **Research Question**: Scope, objectives, variables, parameters
- **Multiple Choice**: Provide exactly 3 options (A, B, C)

### 🗣️ TONE Options
- Professional but passionate about social impact
- Conversational and approachable
- Formal and authoritative
- Energetic and inspiring
- Direct and no-nonsense
- Empathetic and human-centered

---

## Best Practices

### ✅ Do:
- **Start with the end goal in mind**
- **Layer complexity gradually**
- **Test with different inputs**
- **Iterate based on results**
- **Build on previous research**
- **Test multiple tone variations**
- **Seek critical feedback**
- **Generate multiple options**
- **Ask for reasoning transparency**
- **Be specific about technical requirements**
- **Include visual references**
- **Reference successful examples**
- **Plan for iteration**

### ❌ Avoid:
- **Overwhelming with too many instructions**
- **Vague or ambiguous language**
- **Conflicting requirements**
- **Generic, one-size-fits-all approaches**
- **Skipping the context-building phase**
- **Accepting first output without alternatives**
- **Ignoring critical feedback**
- **Using vague task descriptions**
- **Forgetting to specify output format**

---

## 🚀 Quick Reference Commands

### Feedback & Iteration
```markdown
Give RUTHLESSLY HONEST feedback on this and identify blind spots.
```

```markdown
Rewrite by applying your feedback.
```

```markdown
Explain your reasoning. Why did you choose this approach?
```

### Multiple Options
```markdown
Give me 5 options with pros and cons for each. Output in a table.
```

### Enhanced Specificity
```markdown
Be 10 times more specific in your recommendations.
```

### Format Control
```markdown
Output as bullets.
```

```markdown
Output in markdown in this format:
### SECTION:
{{CONTENT}}
```

### Reasoning Models
```markdown
Think step by step.
```

---

## 🔍 Quality Assurance Checklist

### Before Submitting Final Work:
- [ ] **Functionality**: All links and interactions work
- [ ] **Responsiveness**: Tests well on mobile, tablet, desktop
- [ ] **Content**: Elevator pitch prominently featured
- [ ] **SDG Alignment**: Clear connection to chosen sustainable goal
- [ ] **Visual Appeal**: Professional, modern design
- [ ] **Performance**: Fast loading, optimized images
- [ ] **Accessibility**: Proper contrast, alt tags, semantic HTML
- [ ] **Call-to-Action**: Clear next steps for visitors

---

*This cheatsheet compiles all prompts and techniques from the AI Workshop series. Use as a reference for building effective AI interactions across all four chat sessions.*