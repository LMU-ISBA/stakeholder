# Creating Powerful Elevator Pitches with AI

A systematic guide to crafting compelling elevator pitches for SDG-focused applications using advanced prompt engineering.

## 🖥️ Setup Instructions

**Before you begin:**
1. Create a new chat by opening [chatgpt.com](https://chatgpt.com) in a new browser tab
2. **Select your AI model** (reasoning models work best for structured pitch development):
   - **Recommended:** o3, Claude 4 Opus, or Gemini 2.5 Pro for complex reasoning
   - **Alternative:** o4-mini, Claude 3.5 Sonnet, or Gemini 2.0 Flash for faster iteration
   - **Step-by-step thinking:** Add "Think step by step" to any prompt for better analysis
3. **Prerequisites**: Complete Chat 01 (SDG selection) and Chat 02 (Deep research)
4. Have your research findings and SDG choice ready

---

## 🎯 The Importance of Clear Requirements

Before diving into pitch creation, remember: **Clear requirements lead to powerful results**. An elevator pitch must be:
- **Concise**: One compelling sentence
- **Clear**: Easily understood by any audience
- **Compelling**: Motivates action or interest
- **Connected**: Tied to real impact

---

## 🚀 Step-by-Step Pitch Development

### 📝 **Step 1: Define Your ROLE**

**ROLE = WHO the AI should be** (expertise, background, perspective)

Start by establishing the AI's expertise for your specific SDG.

**⚠️ IMPORTANT: Run this prompt in your original Chat 01 conversation thread**

**Example Prompt:**
```markdown
What is an effective ROLE I can assign to an LLM to support me in building a web application that addresses SDG 4?
Output in markdown in this format:
### ROLE:
{{ROLE}}
```
*Then copy the output to use in your new Chat 03 conversation.*

**Good ROLE Examples:**
- Expert startup pitch coach specializing in social impact ventures
- Venture capitalist focused on SDG investments
- Social impact consultant with startup experience
- Career counselor specializing in purpose-driven entrepreneurship

**Alternative Approach:** Ask your group for role suggestions, then validate with AI.

### 🌍 **Step 2: Build Rich CONTEXT**

Combine insights from your previous research to create comprehensive background.

#### **Context Component 1: Your Journey**
**⚠️ IMPORTANT: Run this prompt in your original Chat 01 conversation thread**
```markdown
I'm building a web application to address an SDG. Summarize how I arrived at SDG 4 based on how I responded to the questions from the career counselor. Output in markdown, in the first person voice, and in this format:
### CONTEXT:
{{CONTEXT}}
```
*Then copy the response to use as context in your new Chat 03 conversation.*

#### **Context Component 2: Research Foundation**
- Include your deep research report from Chat 02
- Reference key findings and statistics
- Highlight implementation gaps you discovered

### 🎯 **Step 3: Define Your TASK**

Be specific about what you want to achieve.

**Core Task:**
```markdown
### TASK:
Create a 1-sentence elevator pitch for this SDG-focused web application.
```

### ✅ Submit Your Prompt So Far

---

### 📚 **Step 4: Add EXAMPLES**

Provide frameworks to guide the AI's output.

1. **Select Best Framework**: Choose from the frameworks you researched in setup (or ask AI for suggestions)
2. **Apply Framework**:
```markdown
### EXAMPLES:
Use the [framework name] framework to create this elevator pitch.
```
**Prompting Tip:** To get better output, try being quantitatively more specific:  
```markdown
Be 10 times more specific in your recommendations.
```

### 🎪 **Step 5: Experiment with TONE**

**TONE = HOW the AI should communicate** (style, energy, formality level)

Test different communication styles to find your voice. Keep the same ROLE but change how it speaks.

**Tone Variations:**
```markdown
### TONE:
Rewrite the pitch with a professional but passionate tone about social impact.
```
```markdown
### TONE:
Rewrite the pitch as a pirate.
```
```markdown
### TONE:
Rewrite the pitch using a conversational and approachable tone.
```

**Good TONE Options:**
- Professional but passionate about social impact
- Conversational and approachable
- Formal and authoritative
- Energetic and inspiring
- Direct and no-nonsense
- Empathetic and human-centered

**💡 Pro Tip:** The same expert ROLE can use different TONEs depending on your audience (investors vs. students vs. policy makers).

---

## 🔄 Refinement & Feedback Loop

### 🎯 **Critical Feedback Process**

Get honest assessment to improve your pitch:

```markdown
Give RUTHLESSLY HONEST feedback on this pitch and identify blind spots.
```

**Follow-up:**
```markdown
Rewrite the pitch by applying your feedback.
```

### 🤔 **Understanding the Reasoning**

Ask for transparency in AI decision-making:

```markdown
Explain your reasoning. Why did you choose this approach?
```

---

## 📊 Decision-Making Framework

### 🎯 **Generate Multiple Options**

Create variety for comparison:

```markdown
Give me 5 elevator pitch options with pros and cons for each. Output in a table.
```
### 🎯 **Final OUTPUT Formatting**

Specify your preferred format:

```markdown
Output as bullets.
```

**Final Decision Prompt:**
```markdown
Make a final recommendation with evidence, then provide the final 1-sentence elevator pitch.
```

---

### 🗣️ **Conversational Approach**

Instead of giving orders, start conversations:
- Develop better understanding of the situation
- Force critical thinking and decision-making
- Ask better questions rather than demanding answers


---

## 🎯 Best Practices Checklist

### ✅ **Do:**
- Build on previous research (Chat 01 & 02)
- Test multiple tone variations
- Seek critical feedback
- Generate multiple options
- Ask for reasoning transparency
- Iterate based on feedback

### ❌ **Avoid:**
- Skipping the context-building phase
- Accepting the first pitch without alternatives
- Ignoring critical feedback
- Using vague task descriptions
- Forgetting to specify output format

---

## 🚀 Quick Start Template

**Complete Prompt Example:**
```markdown
ROLE: You are an expert startup pitch coach specializing in social impact ventures.

CONTEXT: [Insert your SDG journey summary and research findings]

TASK: Create 5 one-sentence elevator pitch options for my SDG 4 web application.

EXAMPLES: Use the Problem-Solution-Impact framework.

FORMAT: Present as a table with pros/cons for each option.

TONE: Professional but passionate about education equity.

Follow up with your top recommendation and reasoning.
```