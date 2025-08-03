---
theme: default
background: '#f4f0eb'
title: Supplemental Guide - Hands-On Demo
info: |
  ## AI Development Workshop - Supplemental Guide
  Build real products. Ship real code. Lead real transformation.
  
  Presented by Daygent
highlighter: shiki
lineNumbers: false
transition: slide-left
mdc: true
fonts:
  sans: 'Inter,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial'
  mono: 'Fira Code,Monaco,Courier New'
colorSchema: 'light'
resolution: '1920x1080'
aspectRatio: '16/9'
slideNumber: false
---

# 📚 Agentic Topics

## Table of Contents

### <a href="/3">🚀 Getting Started with Claude Code</a>

### <a href="/9">🧠 Understanding Context Windows</a>

### <a href="/12">🤖 Working with AI Agents</a>

### <a href="/18">📸 Visual Examples & Screenshots</a>

### <a href="/30">🔄 Version Control & Deployment</a>

### <a href="/35">🎯 Practice Session</a>

---

<style>
/* Typography Hierarchy System */
.slidev-page-number {
  display: none !important;
}

.slidev-layout {
  padding: 3rem 4rem;
  padding-top: 2rem;
  max-width: 1200px;
  margin: 0 auto;
  background-color: #f4f0eb !important;
}

/* Ensure all slide containers have the background */
.slidev-page {
  background-color: #f4f0eb !important;
}

.slidev-slide-container {
  background-color: #f4f0eb !important;
}

/* Primary Heading - 2.5rem, Light weight */
h1 {
  font-size: 2.5rem;
  font-weight: 300;
  letter-spacing: -0.02em;
  line-height: 1.1;
  color: #000;
}

/* Secondary Heading - 1.75rem, Medium weight */
h2 {
  font-size: 1.75rem;
  font-weight: 500;
  letter-spacing: -0.01em;
  line-height: 1.2;
  color: #000;
}

/* Tertiary Heading - 1.25rem, Semi-bold weight */
h3 {
  font-size: 1.25rem;
  font-weight: 600;
  line-height: 1.3;
  color: #000;
}

/* Body Text - Improved contrast */
p {
  line-height: 1.6;
  color: #1a1a1a;
}

.text-muted {
  color: #666;
}

.brand {
  font-weight: 800;
  letter-spacing: 0.2em;
  font-size: 1.25rem;
  color: #2563eb;
}

.section-label {
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #666;
  margin-bottom: 2rem;
}

/* Hero Title - 4rem */
.hero-title {
  font-size: 4.5rem;
  font-weight: 800;
  line-height: 1.05;
  margin: 2rem 0;
  color: #111827;
}

.subtitle {
  font-size: 1.5rem;
  color: #6b7280;
  font-weight: 500;
}

.highlight-box {
  background: rgba(255, 255, 255, 0.5);
  padding: 2rem;
  border-radius: 8px;
  margin: 2rem 0;
}

.metric {
  font-size: 2.5rem;
  font-weight: 600;
  color: #000;
}

.metric-label {
  font-size: 0.875rem;
  color: #666;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

/* Slidev page number styling */
.slidev-page-number {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  font-size: 0.875rem;
  color: #666;
  font-weight: 500;
  z-index: 100;
}

/* Container utilities */
.container-narrow {
  max-width: 700px;
  margin: 0 auto;
}

.container-medium {
  max-width: 800px;
  margin: 0 auto;
}

.container-wide {
  max-width: 900px;
  margin: 0 auto;
}

.container-full {
  max-width: 1200px;
  margin: 0 auto;
}

/* Workshop specific components */
.workshop-step {
  background: rgba(255, 255, 255, 0.8);
  padding: 1.5rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  border-left: 4px solid #2563eb;
}

.step-number {
  display: inline-block;
  width: 2rem;
  height: 2rem;
  background: #2563eb;
  color: white;
  border-radius: 50%;
  text-align: center;
  line-height: 2rem;
  font-weight: 600;
  margin-right: 1rem;
}

.workshop-checkpoint {
  background: #fef3c7;
  border: 2px solid #f59e0b;
  padding: 2rem;
  border-radius: 8px;
  margin: 2rem 0;
}

.follow-along {
  background: #e0e7ff;
  border-left: 4px solid #4f46e5;
  padding: 1rem 1.5rem;
  margin: 2rem 0;
}

.follow-along-command {
  font-family: 'Fira Code', monospace;
  background: #1e293b;
  color: #94a3b8;
  padding: 1rem 1.5rem;
  border-radius: 6px;
  margin: 1rem 0;
  font-size: 1rem;
  line-height: 1.5;
}

.workshop-tip {
  background: #dbeafe;
  border: 1px solid #3b82f6;
  padding: 1rem 1.5rem;
  border-radius: 6px;
  margin: 1rem 0;
}

.workshop-card {
  background: rgba(255, 255, 255, 0.9);
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.workshop-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Alerts and indicators */
.alert-success {
  background: #d1fae5;
  border: 2px solid #10b981;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 1rem 0;
}

.alert-warning {
  background: #fed7aa;
  border: 2px solid #f97316;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 1rem 0;
}

.success-indicator {
  color: #059669;
}

.error-indicator {
  color: #dc2626;
}

.text-warning {
  color: #f59e0b;
}

.text-primary {
  color: #2563eb;
}

/* Demo specific styles */
.demo-section {
  margin: 2rem 0;
}

.terminal-output {
  background: #1e293b;
  color: #e2e8f0;
  padding: 1.5rem;
  border-radius: 8px;
  font-family: 'Fira Code', monospace;
  margin: 1rem 0;
}

.terminal-prompt {
  color: #10b981;
  margin-bottom: 0.5rem;
}

.terminal-comment {
  color: #64748b;
  font-style: italic;
}

/* Feature grid */
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.grid-2 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
  margin: 2rem 0;
}

.grid-3 {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin: 2rem 0;
}

/* Workflow styles */
.workflow-step {
  display: flex;
  align-items: flex-start;
  margin-bottom: 1.5rem;
}

/* Button styles */
.btn {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  font-weight: 600;
  text-align: center;
  transition: all 0.2s;
}

.btn-success {
  background: #10b981;
  color: white;
}

.btn-disabled {
  background: #e5e7eb;
  color: #9ca3af;
  cursor: not-allowed;
}

/* Utilities */
.text-center {
  text-align: center;
}

.text-large {
  font-size: 1.125rem;
}

.text-medium {
  font-size: 1rem;
}

.text-small {
  font-size: 0.875rem;
}

.mb-0 { margin-bottom: 0; }
.mb-1 { margin-bottom: 0.5rem; }
.mb-2 { margin-bottom: 1rem; }
.mb-3 { margin-bottom: 1.5rem; }
.mb-4 { margin-bottom: 2rem; }
.mb-5 { margin-bottom: 2.5rem; }

.mt-0 { margin-top: 0; }
.mt-1 { margin-top: 0.5rem; }
.mt-2 { margin-top: 1rem; }
.mt-3 { margin-top: 1.5rem; }
.mt-4 { margin-top: 2rem; }
.mt-5 { margin-top: 2.5rem; }

.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.gap-3 {
  gap: 1.5rem;
}

.list-clean {
  list-style: none;
  padding-left: 0;
}

.list-spaced li {
  margin-bottom: 0.75rem;
}

.list-large {
  font-size: 1.125rem;
}

/* Hero sections */
.hero-section {
  text-align: center;
  padding: 3rem 0;
}

.hero-title-simple {
  font-size: 3.5rem;
  font-weight: 700;
  line-height: 1.1;
  margin-bottom: 1rem;
}

.hero-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

/* Exercise box */
.exercise-box {
  background: #f0f9ff;
  border: 2px solid #0ea5e9;
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem 0;
}

/* Code styles */
.workshop-code {
  font-family: 'Fira Code', monospace;
  background: #f1f5f9;
  color: #1e293b;
  padding: 0.75rem 1rem;
  border-radius: 6px;
  display: inline-block;
  margin: 0.5rem 0;
}

/* Setup section styles */
.setup-section .workshop-step {
  margin-bottom: 1.5rem;
}

.setup-section h2 {
  color: #1e293b;
  margin-bottom: 0.5rem;
}

.setup-section code {
  display: block;
  margin: 0.5rem 0;
}

/* Font weight utilities */
.font-semibold {
  font-weight: 600;
}

/* v-click support */
.slidev-vclick-hidden {
  opacity: 0;
  pointer-events: none;
}

.slidev-vclick-target {
  transition: opacity 0.3s ease;
}

</style>

<div class="section-label">HANDS-ON DEMO</div>

# How This Works

**1. Open Your Environment**
Open your code editor or terminal

**2. Follow the Commands**
Follow along with my screen

**3. Learn by Doing**
Build and learn together

<v-click>

**Ready? Let's build something real.**

</v-click>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

# Step 1: Navigate to Your Projects

## 📁 Navigate to your projects folder
```bash
$ cd ~/Projects
```

## 🚀 Launch Claude Code
```bash
$ claude-code
```

💡 **Tip:** Claude Code will ask for permission to access this folder

---
transition: slide-up
---

<div class="section-label">DEMO</div>

# Step 2: Trust the Folder

## ⚠️ Claude Code Security Check
*Do you trust the files in this folder?*

With your permission Claude Code may execute files in this folder.

### ✓ Yes, proceed (Choose this)
### ✗ No, exit

*Choose "Yes, proceed" to continue*

---
transition: slide-up
---

<div class="section-label">DEMO</div>

# What Just Happened?

## ✓ Claude Code is now running!

• Created a new project folder  
• Claude Code has full access to this folder  
• Ready to build your first app

<v-click>

*Now let's give Claude Code its first instruction...*

</v-click>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

# The Commands That Matter

## Your First Claude Code Command:
```
Create a simple portfolio website with a home page, about page, and projects page. Use modern design.
```
*Type this exactly as shown and press Enter*

<v-click>

## What Claude Code Will Do:
🔨 Create folder structure  
📄 Generate HTML/CSS files  
🎨 Apply modern design  
🚀 Set up for deployment

</v-click>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

# Your Turn

## 🚀 Let's Code Together!
*Follow along in your terminal now*

### Next Steps:
1. Type the command in your Claude Code terminal
2. Watch Claude Code build your portfolio
3. Ask questions if you get stuck

💡 **Tip:** If Claude Code asks for permissions, always choose "Yes"

---
transition: slide-left
---

<div class="section-label">CONTEXT WINDOWS</div>

# Claude's Short-Term Memory

## 🧠 Like Your Working Memory
Claude can only "remember" what's in the current conversation

## 📏 Limited Space
Once it's full, older information gets forgotten

## 💰 Costs Money
More context = higher costs, so be efficient

---
transition: fade
---

<div class="section-label">CONTEXT WINDOWS</div>

# The Goldilocks Problem

## 🔥 Too Much Information
Like trying to read 10 books at once - Claude gets overwhelmed

## ❄️ Too Little Information
Like trying to help someone without knowing what they need

## ✨ Just Right
Give Claude exactly what it needs to solve the current problem

---
transition: fade
---

<div class="section-label">CONTEXT WINDOWS</div>

# Practical Tips for PMs

<div class="grid-2" style="margin-top: 1.5rem;">
<div>

**🔄 Start Fresh When Stuck**  
Exit and restart with clearer instructions

**🎯 Be Specific**  
"Fix navbar" > "make site better"

</div>
<div>

**1️⃣ One Task at a Time**  
Complete features before starting new ones

**🔗 Reference Recent Work**  
"Like the button we just made"

</div>
</div>

---
transition: slide-down
layout: center
---

# Your AI Development Team

*Specialized AI agents that work for you*

---
transition: slide-left
---

<div class="section-label">SUB-AGENTS</div>

# Think of It Like a Real Team

## 🤖 Frontend Developer
Specializes in UI, styling, and user interactions

## 🔍 Code Reviewer
Finds bugs and suggests improvements

## 🧪 Test Writer
Creates and runs tests to ensure quality

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

# Why This Changes Everything

## 🎯 One Agent, One Job
Instead of one Claude doing everything, each agent becomes an expert at their specific task

## 🚀 Work in Parallel
Run multiple terminals with different agents - like having a whole dev team

## 🧠 You're the Manager
Focus on what to build while your AI team handles how to build it

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

# Creating Your First Agent

### Let's Create a Code Reviewer Agent

```
/agents
```

<v-click>

**1. Choose: "Create new agent"**
Claude will guide you through the process

**2. Name it: "code-reviewer"**
Keep names simple and descriptive

**3. Let Claude generate the config**
It will create a specialized agent for code reviews

</v-click>

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

# Using Your Agent

## Ask Claude to Use Your Agent
```
Use the code-reviewer agent to check my code for issues
```

## What Happens Next
• Claude delegates the task to your specialized agent  
• The agent reviews your entire codebase  
• You get a detailed report of issues and improvements

💡 **Pro Tip:** Agents remember their specialty - no need to re-explain what you want

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

# Practical Agent Examples

<div class="grid-2" style="margin-top: 1.5rem; gap: 2rem;">
<div>

**🔍 Code Reviewer**  
"Find bugs and security issues"

**🧪 Test Writer**  
"Create comprehensive test suites"

</div>
<div>

**🐛 Bug Fixer**  
"Debug complex problems"

**📝 Docs Writer**  
"Generate API documentation"

</div>
</div>

<v-click>
<div style="text-align: center; margin-top: 2rem;">
<em>Each agent gets better the more you use them!</em>
</div>
</v-click>


---
transition: slide-down
layout: center
---

# 📸 Visual Examples & Screenshots

*Real examples of Claude Code in action*

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.48.34.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.49.18.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.51.33.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.53.13.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.54.02.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.55.18.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.56.16.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.56.48.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.07.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.28.png)

---
layout: center
---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.39.png)

---
transition: slide-left
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

# From Idea to Live Website

*Claude Code handles the technical stuff so you can focus on what to build*

## 📝 You Describe
"I need a landing page"

## 🤖 Claude Builds
Creates and tests code

## 🌐 Goes Live
Deployed to the web

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

# The Magic: Claude Handles Git

### Simple Command:
```
Please commit these changes
```

**🤖 What Claude Does For You:**
- Reviews all your changes
- Writes a clear commit message
- Handles all the Git commands
- Pushes to GitHub automatically

<v-click>

**No Git Knowledge Required!** Just tell Claude what you did

</v-click>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

# When Things Go Wrong

*The secret: Don't fight it, just restart*

## ❌ Common Mistake
Trying to fix Claude's errors by giving more instructions

## ✅ Smart Solution
Exit (Ctrl+C) and start fresh with clearer instructions

<v-click>

💭 **Remember:** Claude gets smarter with clear, focused requests

</v-click>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

# Sharing Your Work

## Create a Pull Request:
```
Create a pull request for these changes
```

## Claude Creates Everything:
• Professional PR description  
• List of all changes made  
• Test plan for reviewers  
• Direct link to review

<v-click>

💡 **Pro Tip:** Your team sees professional PRs without you learning Git!

</v-click>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

# Your Code Goes Live Instantly

*Vercel makes deployment magical - no servers, no config, just URLs*

## 🔗 Connect Once
Link GitHub to Vercel in 2 clicks

## 👀 Preview Everything
Every change gets its own URL

## ⚡ Ship Instantly
Merge = Live in production

<v-click>

**No DevOps knowledge required!** Vercel handles everything

</v-click>

---
transition: slide-left
---

<div class="section-label">HANDS-ON PRACTICE</div>

# Let's Build Something Real!

## Your Turn: Ship Your First Feature

☐ Add a new feature to your portfolio  
☐ Commit your changes  
☐ Create a pull request  
☐ Share your live URL in the chat!

---

## Need Ideas? Try These:
• "Add a contact form to my portfolio"  
• "Make the design more colorful"  
• "Add animations to the buttons"  
• "Create a blog section"

---