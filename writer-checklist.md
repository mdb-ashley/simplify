# Writer Checklist: Simplifying MongoDB Documentation (Top 250 Project)

This checklist supports the Simplifying Content project for the Top 250 MongoDB Manual pages.  
Use it each time you revise a page to ensure consistency, accuracy, and alignment across the Docs team.

---

## 1. Determine the Page’s Purpose

Before editing, confirm:

- [ ] What information type is this page?
  - **Concept** – What it is / why it matters / high-level how it works  
  - **Task** – Ordered steps to achieve an outcome  
  - **Reference** – Definitions, parameters, behaviors, options  
  - **Landing/Overview** – High-level orientation + links
- [ ] Does the current structure match the chosen type?
- [ ] Does the page have a clear scope?

---

## 2. Scan for Duplication

Identify content that appears multiple times:

- [ ] Within this page  
- [ ] Across sibling pages in the TOC  
- [ ] In introductory sections repeated elsewhere  

For each duplicated idea:

- [ ] Decide where the **single source of truth** should live  
- [ ] Consolidate or remove redundant copies  
- [ ] Add a link instead of repeating content (when appropriate)

---

## 3. Simplify and Reduce Word Count

When simplifying, ensure you have:

- [ ] Reduced long or repetitive paragraphs  
- [ ] Removed filler phrases (“in order to,” “it is important to note,” etc.)  
- [ ] Turned verbose explanations into concise, clear statements  
- [ ] Shortened or clarified intros to 1–3 crisp sentences  
- [ ] Eliminated unnecessary background users already know

Target: meaningful simplification without loss of accuracy.

---

## 4. Improve Structure and Scannability

Check that the page is easy to scan:

- [ ] Headings follow a logical hierarchy  
- [ ] Sections are short and focused  
- [ ] Long paragraphs are broken into:
  - bullet lists  
  - numbered steps  
  - short sub-sections  
- [ ] Examples are placed where they reinforce—not interrupt—the flow  
- [ ] Optional details are separated from core steps or concepts

Structure should support reading by CTRL+F, scanning, and linked anchors.

---

## 5. Preserve Technical Accuracy

Before finalizing:

- [ ] No technical behavior has changed  
- [ ] No invented examples, parameters, flags, or commands  
- [ ] No removed caveats, warnings, or prerequisites that affect correctness  
- [ ] Code blocks reflect the original content unless improved solely for clarity  
- [ ] Version-specific details are still correct

If accuracy is uncertain:

- [ ] Flag the section for engineering review

---

## 6. Apply MongoDB Documentation Style Expectations

Check for:

- [ ] Active voice  
- [ ] Direct address (“you”)  
- [ ] Clear audience assumptions  
- [ ] Consistent terminology across the Manual  
- [ ] No marketing language

Formatting:

- [ ] Headings use consistent Markdown structure  
- [ ] Lists are used where appropriate  
- [ ] Code blocks are clean and minimal  
- [ ] No overlinking (link sparingly and intentionally)

---

## 7. AI-Assisted Workflow (If Using Copilot or NotebookLM)

After generating an AI simplification pass:

- [ ] Review for unintended meaning changes  
- [ ] Remove hallucinated details  
- [ ] Compare original and rewritten versions closely  
- [ ] Keep AI changes that improve clarity, discard those that alter behavior  
- [ ] Ensure AI hasn’t oversimplified advanced concepts  

If AI output seems risky or shaky:

- [ ] Revert to manual rewrite  
- [ ] Ask for a “guidance only” analysis instead of rewriting  

---

## 8. Final Review Before Marking the Ticket Done

- [ ] Re-read the page from top to bottom—does it flow logically?  
- [ ] Confirm it fits its information type cleanly  
- [ ] Confirm duplicated ideas have been removed or consolidated  
- [ ] Verify links point to the best canonical content  
- [ ] Add “fast follows” for any remaining issues out of scope  
- [ ] If substantial technical changes were made, route to engineering review  

---

## 9. Optional: Useful Micro-Checks

- [ ] Is the introduction the right length and content?  
- [ ] Are there any paragraphs > 4 lines long?  
- [ ] Are readers required to jump across pages more than necessary?  
- [ ] Does the page rely on outdated assumptions or terminology?  
- [ ] Would a diagram, example, or table (existing only!) improve understanding?  
- [ ] Does each section earn its keep?

---

## 10. “Done Means Done” Definition

A page is complete when:

- It is **simplified**, **accurate**, **scannable**, and **non-duplicative**  
- It fits its information type  
- AI-assisted content has been vetted  
- It requires minimal future maintenance  
- It serves as a reliable source of truth for its topic  


Just tell me which formats you want!
