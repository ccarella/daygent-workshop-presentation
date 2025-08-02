---
theme: default
background: '#f4f0eb'
title: Agents
info: |
  ## AI Development Workshop
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

</style>

# <span class="brand">DAYGENT</span>

<div class="hero-title">
AGENTIC CODING FOR<br/>
PRODUCT MANAGERS
</div>

<p class="subtitle">
August 4-5, 2025
</p>

<div class="hero-section">
<p class="text-large container-wide font-semibold" style="line-height: 1.4;">
Today, you'll experience the moment<br/>
a PM realizes they can ship code.
</p>
</div>

---
transition: fade
---

<div class="section-label">MY STORY</div>

<h1 class="mb-3">
The Developers are way ahead.
</h1>

<p class="text-medium mb-3 container-medium">
I've been building with AI development tools since the beginning of the year. As I mastered these tools, I realized something striking: I was the only non-technical person in every developer chat and community I joined.
</p>

<div class="key-learning mt-4">
  <h3>Key Learning</h3>
  <p>
    Product development with AI agents still needs to be product managed. The tools are powerful, but without product thinking, they just build faster solutions to the wrong problems.
  </p>
</div>

---
transition: fade
---

<div class="section-label">MY STORY</div>

<h1 class="mb-3">
Designing with v0
</h1>

<p class="text-medium mb-3 container-medium">
I had a big Product Design task where I needed to provide low fidelity wireframes. I budgeted for a week and finished it with a full clickable prototype in a day.
</p>

<div class="key-learning mt-4">
  <h3>Key Learning</h3>
  <p>
    AI design tools don't replace design thinking—they amplify it. What used to take a week of wireframing can now be done in hours, leaving more time for user testing and iteration.
  </p>
</div>

---
layout: center
transition: fade
---

<div class="section-label">MY STORY</div>

<h1 class="mb-3">
Downsizing our startup.
</h1>

<p class="text-medium mb-3 container-medium">
We downsized our team at the beginning of the year. To pick up the slack, I opened Cursor, loaded up our codebase, and started making direct contributions.
</p>

<p class="text-medium mb-3 container-medium">
That moment changed everything: I realized this wasn't just about design or product anymore—I was now contributing working code to production.
</p>

<div class="key-learning mt-4">
  <h3>Key Learning</h3>
  <p>
    When you eliminate silos, you eliminate excuses. AI-native tools like Cursor lower the barrier between roles—so if you're willing to learn, you can contribute anywhere.
  </p>
</div>

---
transition: slide-left
---

<div class="section-label">WORKSHOP</div>

<h1 class="mb-4">
What Do You Want to Get Out of Today?
</h1>

<div class="container-medium">
  <p class="text-large mb-3" style="font-weight: 600;">
    Goals for Today:
  </p>
  
  <ul class="text-medium list-clean list-spaced list-large">
    <li>• Build internal tools</li>
    <li>• Understand what's possible</li>
    <li>• Move faster with AI</li>
    <li>• Prototype ideas quickly</li>
    <li>• Collaborate better with engineers</li>
    <li>• Speak developer language</li>
  </ul>
</div>

<p class="text-medium text-primary text-center mt-3" style="font-weight: 500;">
  Take a moment to share in the chat or unmute
</p>

---

<div class="section-label">WORKSHOP</div>

<h1 class="mb-4">Setup: GitHub</h1>

<div class="container-narrow setup-section">
  <div class="workshop-step">
    <h2 class="mb-2">1. Create Account</h2>
    <p class="text-large mb-1">
      <a href="https://github.com/join" class="text-primary">github.com/join</a>
    </p>
  </div>

  <div class="workshop-step">
    <h2 class="mb-2">2. Install CLI</h2>
    <code class="workshop-code">brew install gh</code>
    <p class="text-muted mt-2">Windows: Download from GitHub releases</p>
  </div>

  <div class="workshop-step">
    <h2 class="mb-2">3. Authenticate</h2>
    <code class="workshop-code">gh auth login</code>
    <p class="text-muted mt-2">Choose: Login with a web browser</p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">WORKSHOP</div>

<h1 class="mb-4">Setup: Vercel</h1>

<div class="container-narrow setup-section">
  <div class="workshop-step">
    <h2 class="mb-2">1. Sign Up</h2>
    <p class="text-large mb-1">
      <a href="https://vercel.com/signup" class="text-primary">vercel.com/signup</a>
    </p>
    <p class="text-muted">Use your GitHub account to sign in</p>
  </div>

  <div class="workshop-step">
    <h2 class="mb-2">2. Install CLI</h2>
    <code class="workshop-code">npm i -g vercel</code>
  </div>

  <div class="workshop-step">
    <h2 class="mb-2">3. Authenticate</h2>
    <code class="workshop-code">vercel login</code>
    <p class="text-muted mt-2">Opens browser for authentication</p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">WORKSHOP</div>

<h1 class="mb-5">Setup: Claude Code</h1>

<div class="container-narrow setup-section">
  <div class="workshop-step">
    <h2 class="mb-3">1. Check Node.js</h2>
    <code class="workshop-code text-large">node --version</code>
    <p class="text-muted mt-2">Must be v18 or higher</p>
  </div>

  <div class="workshop-step">
    <h2 class="mb-3">2. Install Claude Code</h2>
    <code class="workshop-code text-large">npm i -g @anthropic-ai/claude-code</code>
  </div>

  <div class="workshop-step">
    <h2 class="mb-3">3. Verify Installation</h2>
    <code class="workshop-code text-large">claude-code --help</code>
  </div>
</div>


---
transition: slide-down
layout: center
---

<h1 class="hero-title-simple">
Let's get started.
</h1>

---
transition: slide-left
---

<div class="section-label">HANDS-ON DEMO</div>

<h1 class="mb-3">
How This Works
</h1>

<div class="container-medium demo-section">
  <div class="workflow-step">
    <span class="step-number">1</span>
    <div>
      <h2 class="mb-1">Open Your Environment</h2>
      <p class="text-muted">Open your code editor or terminal</p>
    </div>
  </div>
  
  <div class="workflow-step">
    <span class="step-number">2</span>
    <div>
      <h2 class="mb-1">Follow the Commands</h2>
      <p class="text-muted">Follow along with my screen</p>
    </div>
  </div>
  
  <div class="workflow-step">
    <span class="step-number">3</span>
    <div>
      <h2 class="mb-1">Learn by Doing</h2>
      <p class="text-muted">Build and learn together</p>
    </div>
  </div>
</div>

<div class="workshop-tip text-center mt-3">
  Ready? Let's build something real.
</div>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

<h1 class="mb-4">Step 1: Navigate to Your Projects</h1>

<div class="container-wide demo-section">
  <div class="terminal-output">
    <p class="terminal-prompt">$ cd ~/Projects</p>
    <p class="terminal-comment mb-3">Navigate to your projects folder</p>
    
    <p class="terminal-prompt">$ claude-code</p>
    <p class="terminal-comment">Launch Claude Code in your terminal</p>
  </div>
  
  <div class="workshop-tip mt-3">
    <strong>Tip:</strong> Claude Code will ask for permission to access this folder
  </div>
</div>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

<h1 class="mb-4">Step 2: Trust the Folder</h1>

<div class="container-wide demo-section">
  <div class="workshop-checkpoint">
    <h2 class="text-warning mb-2">⚠️ Claude Code Security Check</h2>
    <p class="text-large mb-2">Do you trust the files in this folder?</p>
    <p class="text-warning">With your permission Claude Code may execute files in this folder.</p>
  </div>
  
  <div class="flex-center gap-3">
    <div class="btn btn-success">
      ✓ Yes, proceed
    </div>
    <div class="btn btn-disabled">
      No, exit
    </div>
  </div>
  
  <p class="text-muted mt-3 text-center">
    Choose "Yes, proceed" to continue
  </p>
</div>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

<h1 class="mb-4">What Just Happened?</h1>

<div class="container-wide demo-section">
  <div class="alert-success">
    <h2 class="success-indicator mb-2">✓ Claude Code is now running!</h2>
    <ul class="text-large" style="line-height: 1.8; list-style: none; padding: 0;">
      <li class="mb-2">• Created a new project folder</li>
      <li class="mb-2">• Claude Code has full access to this folder</li>
      <li>• Ready to build your first app</li>
    </ul>
  </div>
  
  <p class="text-large text-center text-muted">
    Now let's give Claude Code its first instruction...
  </p>
</div>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

<h1 class="mb-3">The Commands That Matter</h1>

<div class="container-wide demo-section">
  <div class="mb-3">
    <h2 class="mb-2">Your First Claude Code Command:</h2>
    <div class="follow-along-command">
      Create a simple portfolio website with a home page, about page, and projects page. Use modern design.
    </div>
    <p class="text-muted">Type this exactly as shown and press Enter</p>
  </div>

  <div>
    <h2 class="mb-2">What Claude Code Will Do:</h2>
    <ul class="list-clean">
      <li class="mb-1">🔨 Create folder structure</li>
      <li class="mb-1">📄 Generate HTML/CSS files</li>
      <li class="mb-1">🎨 Apply modern design</li>
      <li>🚀 Set up for deployment</li>
    </ul>
  </div>
</div>

---
transition: slide-up
---

<div class="section-label">DEMO</div>

<h1 class="mb-3">Your Turn</h1>

<div class="container-wide demo-section">
  <div class="workshop-checkpoint text-center mb-3" style="background: #2563eb; color: white;">
    <h2 class="mb-1">🚀 Let's Code Together!</h2>
    <p class="text-medium">Follow along in your terminal now</p>
  </div>

  <div class="text-medium" style="line-height: 1.6;">
    <p class="mb-2"><strong>Next Steps:</strong></p>
    <ol style="padding-left: 1.5rem;">
      <li class="mb-1">Type the command in your Claude Code terminal</li>
      <li class="mb-1">Watch Claude Code build your portfolio</li>
      <li>Ask questions if you get stuck</li>
    </ol>
  </div>

  <div class="workshop-tip mt-3">
    <strong>Tip:</strong> If Claude Code asks for permissions, always choose "Yes"
  </div>
</div>

---
transition: slide-left
---

<div class="section-label">CONTEXT WINDOWS</div>

<h1 class="mb-4">
Claude's Short-Term Memory
</h1>

<div class="feature-grid container-wide">
  <div v-click class="workshop-card">
    <div class="hero-icon">🧠</div>
    <h2 class="mb-2">Like Your Working Memory</h2>
    <p class="text-medium">
      Claude can only "remember" what's in the current conversation
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <div class="hero-icon">📏</div>
    <h2 class="mb-2">Limited Space</h2>
    <p class="text-medium">
      Once it's full, older information gets forgotten
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <div class="hero-icon">💰</div>
    <h2 class="mb-2">Costs Money</h2>
    <p class="text-medium">
      More context = higher costs, so be efficient
    </p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">CONTEXT WINDOWS</div>

<h1 class="mb-3">
The Goldilocks Problem
</h1>

<div class="container-wide">
  <div v-click class="alert-warning">
    <h2 class="mb-2">🔥 Too Much Information</h2>
    <p class="text-medium">
      Like trying to read 10 books at once - Claude gets overwhelmed
    </p>
  </div>
  
  <div v-click class="alert-warning">
    <h2 class="mb-2">❄️ Too Little Information</h2>
    <p class="text-medium">
      Like trying to help someone without knowing what they need
    </p>
  </div>
  
  <div v-click class="alert-success">
    <h2 class="mb-2">✨ Just Right</h2>
    <p class="text-medium">
      Give Claude exactly what it needs to solve the current problem
    </p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">CONTEXT WINDOWS</div>

<h1 class="mb-3">
Practical Tips for PMs
</h1>

<div class="container-wide">
  <div v-click class="workshop-step">
    <span class="step-number">1</span>
    <div>
      <h3 class="mb-1">Start Fresh When Stuck</h3>
      <p class="text-muted">If Claude gets confused, exit and restart with clearer instructions</p>
    </div>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">2</span>
    <div>
      <h3 class="mb-1">Be Specific</h3>
      <p class="text-muted">"Fix the navbar" is better than "make the site better"</p>
    </div>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">3</span>
    <div>
      <h3 class="mb-1">One Task at a Time</h3>
      <p class="text-muted">Complete features before starting new ones</p>
    </div>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">4</span>
    <div>
      <h3 class="mb-1">Reference Recent Work</h3>
      <p class="text-muted">"Like the button we just made" helps Claude understand</p>
    </div>
  </div>
</div>

---
transition: slide-down
layout: center
---

<h1 class="hero-title-simple">
Your AI Development Team
</h1>

<p class="subtitle text-center mt-4">
Specialized AI agents that work for you
</p>

---
transition: slide-left
---

<div class="section-label">SUB-AGENTS</div>

<h1 class="mb-4">
Think of It Like a Real Team
</h1>

<div class="feature-grid container-wide">
  <div v-click class="workshop-card">
    <div class="hero-icon">🤖</div>
    <h2 class="mb-2">Frontend Developer</h2>
    <p class="text-medium">
      Specializes in UI, styling, and user interactions
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <div class="hero-icon">🔍</div>
    <h2 class="mb-2">Code Reviewer</h2>
    <p class="text-medium">
      Finds bugs and suggests improvements
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <div class="hero-icon">🧪</div>
    <h2 class="mb-2">Test Writer</h2>
    <p class="text-medium">
      Creates and runs tests to ensure quality
    </p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

<h1 class="mb-4">
Why This Changes Everything
</h1>

<div class="container-wide">
  <div v-click class="workshop-card mb-3">
    <h2 class="text-primary mb-2">🎯 One Agent, One Job</h2>
    <p class="text-large">
      Instead of one Claude doing everything, each agent becomes an expert at their specific task
    </p>
  </div>
  
  <div v-click class="workshop-card mb-3">
    <h2 class="text-primary mb-2">🚀 Work in Parallel</h2>
    <p class="text-large">
      Run multiple terminals with different agents - like having a whole dev team
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <h2 class="text-primary mb-2">🧠 You're the Manager</h2>
    <p class="text-large">
      Focus on what to build while your AI team handles how to build it
    </p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

<h1 class="mb-4">
Creating Your First Agent
</h1>

<div class="container-medium">
  <div v-click class="follow-along mb-4">
    <h3>Let's Create a Code Reviewer Agent</h3>
    <div class="follow-along-command">
      /agents
    </div>
    <p class="text-muted mt-2">Type this in Claude Code and press Enter</p>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">1</span>
    <div>
      <h3 class="mb-1">Choose: "Create new agent"</h3>
      <p class="text-muted">Claude will guide you through the process</p>
    </div>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">2</span>
    <div>
      <h3 class="mb-1">Name it: "code-reviewer"</h3>
      <p class="text-muted">Keep names simple and descriptive</p>
    </div>
  </div>
  
  <div v-click class="workshop-step">
    <span class="step-number">3</span>
    <div>
      <h3 class="mb-1">Let Claude generate the config</h3>
      <p class="text-muted">It will create a specialized agent for code reviews</p>
    </div>
  </div>
</div>

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

<h1 class="mb-4">
Using Your Agent
</h1>

<div class="container-wide">
  <div v-click class="follow-along mb-4">
    <h3>Ask Claude to Use Your Agent</h3>
    <div class="follow-along-command">
      Use the code-reviewer agent to check my code for issues
    </div>
  </div>
  
  <div v-click class="alert-success mb-3">
    <h3 class="success-indicator">What Happens Next</h3>
    <ul class="text-medium" style="list-style: none; padding: 0;">
      <li class="mb-2">• Claude delegates the task to your specialized agent</li>
      <li class="mb-2">• The agent reviews your entire codebase</li>
      <li>• You get a detailed report of issues and improvements</li>
    </ul>
  </div>
  
  <div v-click class="workshop-tip">
    <strong>Pro Tip:</strong> Agents remember their specialty - no need to re-explain what you want
  </div>
</div>

---
transition: fade
---

<div class="section-label">SUB-AGENTS</div>

<h1 class="mb-4">
Practical Agent Examples
</h1>

<div class="grid-2 container-wide">
  <div v-click class="workshop-card">
    <h3 class="text-primary mb-2">🔍 Code Reviewer</h3>
    <p class="text-medium">
      "Review my code for bugs and security issues"
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <h3 class="text-primary mb-2">🧪 Test Writer</h3>
    <p class="text-medium">
      "Write tests for the shopping cart feature"
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <h3 class="text-primary mb-2">🐛 Bug Fixer</h3>
    <p class="text-medium">
      "Debug why the form isn't submitting"
    </p>
  </div>
  
  <div v-click class="workshop-card">
    <h3 class="text-primary mb-2">📝 Docs Writer</h3>
    <p class="text-medium">
      "Create API documentation for this service"
    </p>
  </div>
</div>

<div v-click class="workshop-tip mt-4 container-wide">
  Each agent becomes an expert at their task - they get better the more you use them!
</div>

---
transition: fade
---


---
transition: slide-left
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

<h1 class="mb-4">
From Idea to Live Website
</h1>

<p class="text-large mb-5 container-wide">
Claude Code handles the technical stuff so you can focus on what to build
</p>

<div class="grid-3 container-full">
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">📝</div>
    <h2 class="mb-1">You Describe</h2>
    <p class="text-medium text-muted">"I need a landing page"</p>
  </div>
  
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">🤖</div>
    <h2 class="mb-1">Claude Builds</h2>
    <p class="text-medium text-muted">Creates and tests code</p>
  </div>
  
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">🌐</div>
    <h2 class="mb-1">Goes Live</h2>
    <p class="text-medium text-muted">Deployed to the web</p>
  </div>
</div>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

<h1 class="mb-4">
The Magic: Claude Handles Git
</h1>

<div class="container-wide">
  <div v-click class="follow-along mb-4">
    <h3>Simple Command:</h3>
    <div class="follow-along-command">
      Please commit these changes
    </div>
  </div>
  
  <div v-click class="workshop-card mb-3">
    <h3 class="text-primary mb-2">🤖 What Claude Does For You:</h3>
    <ul class="text-large list-clean">
      <li class="mb-2">• Reviews all your changes</li>
      <li class="mb-2">• Writes a clear commit message</li>
      <li class="mb-2">• Handles all the Git commands</li>
      <li>• Pushes to GitHub automatically</li>
    </ul>
  </div>
  
  <div v-click class="workshop-tip">
    <strong>No Git Knowledge Required!</strong> Just tell Claude what you did
  </div>
</div>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>


---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

<h1 class="mb-4">
When Things Go Wrong
</h1>

<p class="text-large mb-4 container-wide">
The secret: Don't fight it, just restart
</p>

<div class="grid-2 container-wide">
  <div v-click class="alert-warning">
    <h3 class="error-indicator mb-2">❌ Common Mistake</h3>
    <p class="text-large">
      Trying to fix Claude's errors by giving more instructions
    </p>
  </div>
  
  <div v-click class="alert-success">
    <h3 class="success-indicator mb-2">✅ Smart Solution</h3>
    <p class="text-large">
      Exit (Ctrl+C) and start fresh with clearer instructions
    </p>
  </div>
</div>

<div v-click class="workshop-tip mt-4 container-wide">
  <strong>Remember:</strong> Claude gets smarter with clear, focused requests
</div>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

<h1 class="mb-4">
Sharing Your Work
</h1>

<div class="container-wide">
  <div v-click class="follow-along mb-4">
    <h3>Create a Pull Request:</h3>
    <div class="follow-along-command">
      Create a pull request for these changes
    </div>
  </div>
  
  <div v-click class="alert-success">
    <h3 class="success-indicator mb-2">Claude Creates Everything:</h3>
    <ul class="text-large list-clean">
      <li class="mb-2">• Professional PR description</li>
      <li class="mb-2">• List of all changes made</li>
      <li class="mb-2">• Test plan for reviewers</li>
      <li>• Direct link to review</li>
    </ul>
  </div>
  
  <div v-click class="workshop-tip mt-4">
    <strong>Pro Tip:</strong> Your team sees professional PRs without you learning Git!
  </div>
</div>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>

<h1 class="mb-4">
Your Code Goes Live Instantly
</h1>

<p class="text-large mb-4 container-wide">
Vercel makes deployment magical - no servers, no config, just URLs
</p>

<div class="feature-grid container-wide">
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">🔗</div>
    <h3 class="mb-2">Connect Once</h3>
    <p class="text-medium">
      Link GitHub to Vercel in 2 clicks
    </p>
  </div>
  
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">👀</div>
    <h3 class="mb-2">Preview Everything</h3>
    <p class="text-medium">
      Every change gets its own URL
    </p>
  </div>
  
  <div v-click class="workshop-card text-center">
    <div class="hero-icon">⚡</div>
    <h3 class="mb-2">Ship Instantly</h3>
    <p class="text-medium">
      Merge = Live in production
    </p>
  </div>
</div>

<div v-click class="workshop-checkpoint mt-4 container-wide">
  <p class="text-large text-center mb-0">
    <strong>No DevOps knowledge required!</strong> Vercel handles everything
  </p>
</div>

---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>


---
transition: fade
---

<div class="section-label">VERSION CONTROL & WORKFLOW</div>


---
transition: slide-left
---

<div class="section-label">HANDS-ON PRACTICE</div>

<h1 class="mb-4">
Let's Build Something Real!
</h1>

<div class="exercise-box">
  <h3>Your Turn: Ship Your First Feature</h3>
  
  <div class="workshop-checklist">
    <div class="workshop-checklist-item">
      <input type="checkbox">
      <span>Add a new feature to your portfolio</span>
    </div>
    
    <div class="workshop-checklist-item">
      <input type="checkbox">
      <span>Commit your changes</span>
    </div>
    
    <div class="workshop-checklist-item">
      <input type="checkbox">
      <span>Create a pull request</span>
    </div>
    
    <div class="workshop-checklist-item">
      <input type="checkbox">
      <span>Share your live URL in the chat!</span>
    </div>
  </div>
</div>

<div class="follow-along mt-4">
  <h3>Need Ideas? Try These:</h3>
  <ul class="text-large list-clean">
    <li class="mb-2">• "Add a contact form to my portfolio"</li>
    <li class="mb-2">• "Make the design more colorful"</li>
    <li class="mb-2">• "Add animations to the buttons"</li>
    <li>• "Create a blog section"</li>
  </ul>
</div>


---
layout: center
transition: slide-up
---

<div class="hero-section">
  <h1 class="hero-title-simple mb-4">
    You're Now a<br/>
    Technical PM
  </h1>
  
  <p class="subtitle">
    Go build something amazing.
  </p>
  
  <div class="mt-5">
    <p class="text-large text-muted">Questions?</p>
  </div>
</div>

---
layout: center
---

<div class="section-label">APPENDIX</div>

<h1 class="mb-4">Design System Reference</h1>

<div class="container-wide">
  <div class="grid-2 mb-4">
    <div class="workshop-card">
      <h3 class="text-primary mb-2">Workshop Components</h3>
      <ul class="list-clean">
        <li class="mb-1">• <code class="workshop-code-inline">.workshop-step</code> - Setup instructions</li>
        <li class="mb-1">• <code class="workshop-code-inline">.workshop-checkpoint</code> - Important alerts</li>
        <li class="mb-1">• <code class="workshop-code-inline">.follow-along</code> - Live coding sections</li>
        <li>• <code class="workshop-code-inline">.workshop-tip</code> - Helpful hints</li>
      </ul>
    </div>
    
    <div class="workshop-card">
      <h3 class="text-primary mb-2">Container Utilities</h3>
      <ul class="list-clean">
        <li class="mb-1">• <code class="workshop-code-inline">.container-narrow</code> - 700px</li>
        <li class="mb-1">• <code class="workshop-code-inline">.container-medium</code> - 800px</li>
        <li class="mb-1">• <code class="workshop-code-inline">.container-wide</code> - 900px</li>
        <li>• <code class="workshop-code-inline">.container-full</code> - 1200px</li>
      </ul>
    </div>
  </div>
  
  <div class="workshop-checkpoint">
    <p class="text-center mb-0">
      <strong>All inline styles have been migrated to reusable CSS classes!</strong>
    </p>
  </div>
</div>

---
