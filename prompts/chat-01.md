# Prompt Engineering: From Basic to Intermediate

A hands-on guide to building effective prompts through progressive enhancement.

## 🖥️ Setup Instructions

**Before you begin:**
1. Go to [chatgpt.com](https://chatgpt.com)
2. Ensure **GPT-4o** is selected as your model
3. Follow the exercises below to experience the evolution of prompt engineering

## 📋 Essential Prompt Components

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

---

## 🚀 The Evolution: From Basic to Sophisticated

### Level 1: Basic Question
*Getting a simple answer*

```markdown
What are the SDGs?
```

**Result:** Generic information without personalization or specific application.

---

### Level 2: Context-Driven Approach
*Making the AI work for better context*

> **💡 Pro Tip:** Ask AI to ask YOU questions to build proper CONTEXT.

```markdown
I'm building a web application to address an SDG. Ask me three questions, one question at a time, to help me identify which SDG to work on.
```

**Improvement:** AI gathers specific information before providing recommendations.

**🤔 Reflection Question:** What other CONTEXT could we provide to better inform the LLM?

---

### Level 3: Structured Prompt

#### 🎭 **ROLE Definition**
```markdown
ROLE: 
You are an expert career counselor whose goal is to help high school students:
- Increase their curiosity  
- Nurture their creativity
- Identify real-world problems they deeply care about
```
> **💡 Pro Tip:** Use Shift + Enter to add a newline in the chat window.

#### 🌍 **CONTEXT Setting**
```markdown
CONTEXT:
The student is assigned a project to develop a web application that addresses an SDG (Sustainable Development Goal).
```

#### 🎯 **TASK Specification**
```markdown
TASK: 
Assist the student in selecting an SDG that aligns with their values and interests.
Ask three multiple-choice questions, one at a time. 
After the student answers all three, use their responses to recommend the most relevant SDG, along with one or two related SDGs they may also consider.
```

#### 🗣️ **TONE Guidelines**
```markdown
TONE: 
Your tone should be encouraging, clear, and thought-provoking. Prioritize helping the student feel excited and confident about the issue they want to work on.
```

---

## 🔍 Impact Analysis

### Before vs. After Comparison

**📝 Reflection Exercise:**
```markdown
How did defining the ROLE influence the conversation? Compare the interaction before and after the ROLE was set. What were the key differences in tone, structure, and approach? Display the results in a table for a side-by-side comparision.
```

**Key Differences to Observe:**
- **Expertise Level:** Generic vs. specialized knowledge
- **Communication Style:** Formal vs. age-appropriate
- **Question Quality:** Surface-level vs. thoughtful inquiry
- **Goal Alignment:** Information delivery vs. student development

---

## 🛠️ Advanced Components in Action

### 📚 **EXAMPLES Component**
*Show, don't just tell*

```markdown
EXAMPLES:
Question 1: "Which area interests you most? A) Environmental sustainability B) Social equality C) Economic development"

Expected response format: "Based on your answers, I recommend SDG 13 (Climate Action) as your primary focus..."
```

### 📝 **FORMAT Component**
*Structure for usability*

```markdown
FORMAT:
- Present each question in a numbered list
- Provide exactly 3 multiple-choice options (A, B, C)
- End with a recommendation section containing:
  * Primary SDG recommendation
  * 1-2 alternative SDGs
  * Brief rationale (2-3 sentences)
```

### 🎯 **Best Practices Checklist**

✅ **Do:**
- Start with the end goal in mind
- Layer complexity gradually
- Test with different inputs
- Iterate based on results

❌ **Avoid:**
- Overwhelming with too many instructions
- Vague or ambiguous language
- Conflicting requirements
- Generic, one-size-fits-all approaches

---

## 🚀 Next Steps: Put It Into Practice

1. **Try the Basic Version** - Start with "What are the SDGs?"
2. **Apply Context Engineering** - Use the Level 2 approach
3. **Build Your Full Prompt** - Implement all components
4. **Compare Results** - Document the differences
5. **Iterate and Improve** - Refine based on outcomes

### 💡 **Pro Tips for Success**
- **Start Simple:** Begin with ROLE and CONTEXT
- **Be Specific:** Vague prompts yield vague results
- **Test Iteratively:** Small changes can have big impacts
- **Document What Works:** Build your prompt library