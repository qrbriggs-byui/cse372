# Workshop: Exploring Formats for Acceptance Criteria

**Duration:** 45 minutes  
**Goal:** Learn how to express acceptance criteria in multiple formats and apply them to your existing user stories from earlier workshops.

---

## Overview

In this workshop, you’ll take your **user stories** from the previous session and explore two common ways to express their acceptance criteria: the **checklist format** and the **Given–When–Then format**. You’ll practice transforming and comparing these styles to understand when and why each is used.

This activity emphasizes clear, testable communication of requirements using both **textual precision** and **visual context**.

---

## Learning Outcomes

By the end of this workshop, you will be able to:
1. Define acceptance criteria that describe “done” for a user story.  
2. Write acceptance criteria in both **checklist** and **Given–When–Then** formats.  
3. Identify when to use simple versus complex acceptance criteria.  
4. Communicate requirements effectively to diverse audiences using clear text and visual references.

---

## Workshop Agenda

### 1. Introduction (5 minutes)
- Review what **acceptance criteria** are and why they matter.  
- Discuss how they clarify expectations between users, designers, and developers:contentReference[oaicite:2]{index=2}.  
- Review the two common formats:  
  - **Checklist format** — a simple, bullet-point list of success conditions.  
  - **Given–When–Then format** — a structured, scenario-based format from Behavior-Driven Development (BDD):contentReference[oaicite:3]{index=3}.

---

### 2. Review User Stories (5 minutes)
- Retrieve your **user stories and prototypes** from the previous workshop.  
- Choose **one user story** to use for this activity.  
  Example:  
  > As a student, I want to see which classes are full so that I can plan alternatives early.  

---

### 3. Write Acceptance Criteria: Checklist Format (10 minutes)
- Write 3–5 acceptance criteria for your selected user story using a checklist format.  
- Each bullet should represent a testable condition.  
- Example:  
  - The system displays seat availability next to each class.  
  - Full classes are marked as “Closed.”  
  - The data refreshes automatically every minute.  
  - The student can only register for available classes.  

**Tip:** Use simple, unambiguous language. Each item should describe one specific outcome.

---

### 4. Write Acceptance Criteria: Given–When–Then Format (15 minutes)
- Now, rewrite your criteria using **Gherkin syntax**.  
- This format is great for describing **complex, multi-step interactions**.  
- Use multiple “And” statements to capture dependent actions and outcomes.  

**Example:**  
Given the student is logged into the system
And the course list is visible
When they attempt to register for a class that is full
Then the system displays a “Closed” status
And prevents registration.


- Compare this to your checklist version. What differences do you notice in structure, readability, and testing potential?

---

### 5. Reflection and Discussion (10 minutes)
- Share your examples with another group.  
- Discuss the following:  
  - Which format was easier to write?  
  - Which better communicates logic to developers or testers?  
  - How might each format suit different audiences?  

---

## Deliverables

By the end of the session, each team should have:  
- One user story written in both **checklist** and **Given–When–Then** acceptance criteria formats.  
- A short reflection (100–150 words) comparing the two styles and explaining when each is most useful.  
- Annotated visuals (wireframes or flow diagrams) showing where these criteria apply in the prototype.

---

## Tools
- Google Docs or Miro for writing and collaboration  
- Access to your prototype or user story documents  
- Optional: Figma or Lucidchart for visual annotation  

---

## Communication Focus

Practice communicating requirements in two complementary ways:  
- **Textual clarity** — writing concise, testable conditions.  
- **Visual clarity** — linking acceptance criteria to prototype screens or workflows.  

