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

/* Page numbers are hidden - remove conflicting styles */

/* Workshop specific components */
.workshop-step {
  background: rgba(255, 255, 255, 0.8);
  padding: 1.5rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  border-left: 4px solid #2563eb;
}

.workshop-code {
  font-family: 'Fira Code', monospace;
  background: #f1f5f9;
  color: #1e293b;
  padding: 0.75rem 1rem;
  border-radius: 6px;
  display: inline-block;
  margin: 0.5rem 0;
}

/* Container utilities */
.container-narrow {
  max-width: 700px;
  margin: 0 auto;
}

.text-large {
  font-size: 1.125rem;
}

.text-primary {
  color: #2563eb;
}

.mb-0 { margin-bottom: 0; }
.mb-1 { margin-bottom: 0.5rem; }
.mb-2 { margin-bottom: 1rem; }
.mb-3 { margin-bottom: 1.5rem; }
.mb-4 { margin-bottom: 2rem; }
.mb-5 { margin-bottom: 2.5rem; }

.mt-2 { margin-top: 1rem; }
.mt-3 { margin-top: 1.5rem; }

.list-clean {
  list-style: none;
  padding-left: 0;
}

.list-clean li {
  padding-left: 0;
}

.list-spaced li {
  margin-bottom: 0.75rem;
}

.list-large {
  font-size: 1.125rem;
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
    <li>Build internal tools</li>
    <li>Understand what's possible</li>
    <li>Move faster with AI</li>
    <li>Prototype ideas quickly</li>
    <li>Collaborate better with engineers</li>
    <li>Speak developer language</li>
  </ul>
</div>

<p class="text-medium text-primary text-center mt-3" style="font-weight: 500;">
  Take a moment to share in the chat or unmute
</p>

---

<div class="section-label">WORKSHOP</div>

<h1 style="font-size: 1.75rem; margin-bottom: 1.5rem;">Setup: GitHub</h1>

<div style="max-width: 800px; margin: 0 auto;">
  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">1</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Create Account</h3>
        <a href="https://github.com/join" class="text-primary" style="font-size: 1rem;">github.com/join</a>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">2</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Install CLI</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">brew install gh</code>
        <p style="margin: 0.5rem 0 0 0; color: #666; font-size: 0.875rem;">Windows: Download from GitHub releases</p>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">3</div>
      </td>
      <td>
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Authenticate</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">gh auth login</code>
        <p style="margin: 0.5rem 0 0 0; color: #666; font-size: 0.875rem;">Choose: Login with a web browser</p>
      </td>
    </tr>
  </table>
</div>

---
transition: fade
---

<div class="section-label">WORKSHOP</div>

<h1 style="font-size: 1.75rem; margin-bottom: 1.5rem;">Setup: Vercel</h1>

<div style="max-width: 800px; margin: 0 auto;">
  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">1</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Sign Up</h3>
        <a href="https://vercel.com/signup" class="text-primary" style="font-size: 1rem;">vercel.com/signup</a>
        <p style="margin: 0.5rem 0 0 0; color: #666; font-size: 0.875rem;">Use your GitHub account to sign in</p>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">2</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Install CLI</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">npm i -g vercel</code>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">3</div>
      </td>
      <td>
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Authenticate</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">vercel login</code>
        <p style="margin: 0.5rem 0 0 0; color: #666; font-size: 0.875rem;">Opens browser for authentication</p>
      </td>
    </tr>
  </table>
</div>

---
transition: fade
---

<div class="section-label">WORKSHOP</div>

<h1 style="font-size: 1.75rem; margin-bottom: 1.5rem;">Setup: Claude Code</h1>

<div style="max-width: 800px; margin: 0 auto;">
  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">1</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Check Node.js</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">node --version</code>
        <p style="margin: 0.5rem 0 0 0; color: #666; font-size: 0.875rem;">Must be v18 or higher</p>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">2</div>
      </td>
      <td style="padding-bottom: 1.5rem;">
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Install Claude Code</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">npm i -g @anthropic-ai/claude-code</code>
      </td>
    </tr>
    <tr>
      <td style="width: 50px; vertical-align: top; padding-right: 1rem;">
        <div style="background: #2563eb; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;">3</div>
      </td>
      <td>
        <h3 style="margin: 0 0 0.5rem 0; font-size: 1.125rem;">Verify Installation</h3>
        <code style="background: #f1f5f9; color: #1e293b; padding: 0.5rem 1rem; border-radius: 6px; font-family: 'Fira Code', monospace; display: inline-block;">claude-code --help</code>
      </td>
    </tr>
  </table>
</div>


---
transition: slide-down
layout: center
---

<h1 class="hero-title-simple">
Let's get started.
</h1>

---
transition: slide-down
layout: center
---

<h1 class="hero-title-simple">
What is Claude Code?
</h1>


---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.48.34.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.49.18.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.51.33.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.53.13.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.54.02.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.55.18.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.56.16.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.56.48.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.07.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.28.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2008.57.39.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.07.27.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.07.47.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.08.21.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.12.24.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.12.48.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.17.09.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.17.45.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.20.11.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.20.22.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.21.06.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.21.51.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.24.04.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.26.18.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.27.05.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.27.14.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.27.33.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.46.32.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.58.37.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.58.51.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2009.59.03.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.00.15.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.01.14.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.01.30.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.01.49.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.02.31.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.03.03.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.03.21.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.04.24.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.06.42.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.07.25.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.09.17.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.13.16.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.13.24.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.13.56.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.15.01.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.15.30.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.15.38.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.16.15.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.17.32.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.18.05.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.18.11.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.18.45.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.19.04.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.40.31.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.40.38.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.43.24.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.44.17.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.52.43.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.55.34.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.56.37.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.56.47.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2010.58.11.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.00.32.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.00.48.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.02.38.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.05.29.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.18.35.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.18.43.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.19.10.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.22.11.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.23.47.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.33.09.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.35.32.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.35.58.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.45.37.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.46.35.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.48.23.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.50.55.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.51.21.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.52.02.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2011.52.36.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.00.19.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.04.11.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.05.01.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.05.42.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.06.14.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.09.03.png)

---

![](/Workshop%20images/workshop%202025-08-02%20at%2012.14.25.png)

---
