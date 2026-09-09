# Kivi — Intelligent Dictation & Structured Note Partner

*Your words remain yours.*

Kivi is an automated dictation assistant and structuring companion engineered specifically for consultants and high-context professionals. By capturing raw speech and transforming it into tailored, actionable textual assets without overriding original judgment or nuance, Kivi eliminates manual meeting documentation so professionals can stay 100% focused on active problem-solving.

---

## Problem Overview

Consultants navigate fast-paced, high-stakes client meetings where critical numerical data, strategic shifts, and immediate action items must be captured accurately. Juggling active listening, client diagnosis, and manual note-taking leads to:
* **Divided attention** during critical revenue-impacting discussions.
* **Inconsistent documentation** and lost numerical data that is difficult to retain from memory.
* **Administrative friction** and post-meeting documentation drag, ultimately contributing to consultant burnout.

---

## The Solution

Kivi operates silently in the background of your desktop environment. With a global keyboard shortcut or voice command, Kivi captures speech and instantly processes it through domain-specific frameworks while maintaining an exact verbatim transcript.

* **Strict Neutrality:** Structures and extracts data without distorting the speaker's original intent or judgment.
* **Dual-Pane Fidelity:** Saves and displays both the raw, word-for-word transcript and the processed framework output side by side.
* **Zero-Friction Access:** Accessible via global hotkeys, a floating quick actions trigger, or hands-free wake phrases.

---

## Key Features & UI Architecture

### 1. Output Frameworks & Granular Rules
Users can toggle individual framework cards (`Active` / `Inactive`) and drill down into sub-rules using expander arrows:

* **Analyst Brief (`Data Extraction` rules):** Extracts quantitative metrics and action items into bulleted points.
  * **Highlight Financials:** Automatically bolds all currency amounts and percentages (e.g., `Q3 revenue hit $4.2M, an increase of 14%`).
  * **Flag Deadlines:** Identifies dates/times and surfaces them at the top (e.g., `Action Item: Submit the Q4 roadmap by Friday at 5 PM`).
  * **Strict Mode:** Strips speech disfluencies and fillers, outputting hard factual records (e.g., reduces *"So, um, yeah they finally said yes..."* to `Budget approved`).
* **Executive Summary (`Content Distillation` rules):** Condenses raw dictation into high-level strategic summaries.
  * **Generate TL;DR:** Inserts a bottom-line summary sentence at the top (e.g., `TL;DR: Q2 margins grew 8%; recommend proceeding with the merger`).
  * **Elevate Tone:** Rewrites colloquial phrasing into executive, formal terminology (e.g., converts *"we fixed the mess"* to `Operational headwinds were mitigated`).
  * **Flag Approvals:** Auto-detects and highlights sign-offs and strategic decisions (e.g., `Decision: The $1.5M marketing budget was approved`).
* **Script Structure / Client Memo:** Formats conversational brain dumps into polished external memos and structured scripts.
* **Raw Strategy:** Retains word-for-word dictations while locking in firm-specific abbreviations, acronyms, and technical jargon.
* **Add Frameworks (`+`):** Build and configure custom extraction and distillation templates to fit firm-specific deliverables.

### 2. Multilingual Speech & Script Formatting
* **Speech Language Detection:** Choose between automated detection (`Auto Detect`) or manual selection (e.g., `English`, `हिन्दी - Hindi`).
* **Dual Script Formatting:**
  * **Native Script:** Renders speech in its authentic orthography (e.g., `नमस्ते ! आप कैसे हैं ?`).
  * **Roman Script:** Phonetically transliterates non-Latin scripts into standard Latin lettering (e.g., `Namaste! Aap kaise hain?`).
* **Live Transcript Preview:** Dynamic feedback preview showing real-time formatting changes before finalizing notes.

### 3. Desktop Shell & Ecosystem Controls
* **Unobtrusive HUD:** Minimalist dark-mode desktop interface branded with the signature Kivi mascot.
* **Sidebar Navigation:** Expandable drawer for profile management, workspace views, and deep configuration without obstructing active work.
* **Top Header Utilities:** Global search bar, quick settings cog, and standard window controls (`Minimize`, `Maximize`, `Close`).
* **Connected Apps:** Dropdown integration hub for syncing structured notes directly into external SaaS tools and enterprise workspaces.
* **Floating Quick Actions:** Persistent floating microphone pill button in the bottom corner for immediate recording, dictation toggles, and audio adjustments.
* **Voice Command Support:** Activate listening hands-free via `"Hello Kivi"`.

---

## Getting Started

1. **Launch & Authenticate:** Start Kivi (runs in background on system startup) and sign in using **Continue with Google** or enterprise credentials.
2. **Set Your Role:** Select your firm role to auto-configure industry-standard terminology and output frameworks.
3. **Configure Speech & Script:**
   * Select `Auto Detect` or specify your spoken language (e.g., English, Hindi).
   * Select your script output preference: `Native` or `Roman`.
4. **Choose & Refine Frameworks:**
   * Toggle your primary output card (e.g., `Analyst Brief` or `Executive Summary`).
   * Click the framework arrow (`>`) to configure granular extraction rules (e.g., `Highlight Financials`, `Flag Deadlines`, `Strict Mode`).
5. **Dictate:** Press your custom keyboard shortcut, click the floating **Quick Actions** microphone, or say `"Hello Kivi"`.
6. **Review & Sync:** Inspect your verbatim transcript against the structured card, make manual inline edits, and push directly to your connected apps.

---

## Design & Prototype Resources

* **Interactive Prototype:** [Test the Kivi Prototype in Figma](https://www.figma.com/proto/aMNzd0IK3ghCQOsBFBRBFM/Kivi_Prototype?node-id=11-143&p=f&t=Sd76HNq2gqWOTquf-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=6%3A110)
* **Figma Design Canvas:** [Inspect Frames & UI Components](https://www.figma.com/design/aMNzd0IK3ghCQOsBFBRBFM/Kivi_Prototype?node-id=0-1&p=f&t=0TFgzbqShJbSviPn-0)

---

*Note: This documentation reflects the current Figma design specifications and is subject to evolution during implementation.*