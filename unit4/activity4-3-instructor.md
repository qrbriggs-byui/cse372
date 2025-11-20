# Instructor Guide: Transforming Findings into User Stories with Acceptance Criteria

**Duration:** 45 minutes  
**Audience:** Undergraduate software engineering or requirements-gathering students  
**Workshop Theme:** Converting user insights from research and prototypes into structured, actionable user stories with measurable acceptance criteria.

---

## Learning Objectives

By the end of this workshop, students should be able to:
1. Translate user needs and frustrations into clear user stories.  
2. Write acceptance criteria that define measurable success.  
3. Use textual and visual strategies to communicate requirements effectively.  
4. Understand how research informs development priorities.

---

## Preparation

- Review sample user stories and acceptance criteria (both checklist and Gherkin formats).  
- Have student groups bring:  
  - Results from their **user survey workshop**.  
  - Prototypes created during the **low-fidelity prototyping workshop**.  
- Prepare one example story and criteria to model for students.  

**Example:**  
> Story: As a student, I want to view my weekly schedule visually so that I can identify time conflicts.  
> Criteria:  
> - The system displays all enrolled classes in a weekly grid.  
> - Overlapping courses trigger a visual warning.  

---

## Session Breakdown (45 minutes)

### **1. Introduction (5 minutes)**
- Explain how insights become actionable stories.  
- Reiterate that user stories focus on value, not features:contentReference[oaicite:5]{index=5}.  
- Discuss how clear acceptance criteria promote shared understanding between teams:contentReference[oaicite:6]{index=6}.

**Instructor Demo:**  
Show how a single user insight from a survey (e.g., “I can’t tell when courses are full”) becomes a user story and measurable criteria.

---

### **2. Identify Key Insights (10 minutes)**
- Ask groups to review their survey data and prototype feedback.  
- Have them highlight 2–3 key findings that reveal user needs or frustrations.  
- Walk around and prompt students with guiding questions:  
  - “What problem does this feedback reveal?”  
  - “How might solving this help the user achieve their goal?”  

---

### **3. Write User Stories (15 minutes)**
- Groups turn their chosen insights into 2–3 user stories.  
- Reinforce the story structure: *As a [user], I want [goal], so that [reason].*  
- Encourage precision and empathy—avoid system jargon or technical detail.  

**Instructor Tip:**  
Model one story on the board and review it with the class for clarity, scope, and focus.

**Coaching Focus:**  
- Does each story describe user value?  
- Can developers understand what needs to be built?

---

### **4. Add Acceptance Criteria (10 minutes)**
- Have groups write 3–5 acceptance criteria per story.  
- Encourage both **checklist** and **Given–When–Then** styles to reinforce versatility:contentReference[oaicite:7]{index=7}.  
- Emphasize that each criterion should be testable and unambiguous.

**Example Walkthrough:**  

Given the user is logged in,
When they add a course that conflicts with another,
Then the system displays a red conflict warning and blocks submission.


**Instructor Tip:**  
Remind students that criteria bridge design and testing—they define “done” for developers and QA teams.

---

### **5. Reflection and Presentation (5 minutes)**
- Invite groups to present one story with its acceptance criteria.  
- Lead a brief discussion:  
  - “Which criteria formats worked best?”  
  - “How did your prototype or survey data inform this story?”  

---

## Assessment and Follow-Up

**During Class:**  
Evaluate groups on:  
- Clear connection between user insights and stories.  
- Logical and testable acceptance criteria.  
- Use of both textual and visual references.  

**After Class:**  
Students refine stories for inclusion in their project specification document (to be used in the next workshop on acceptance criteria formats).

---

## Communication Emphasis

Highlight how effective requirements communication merges:  
- **Textual clarity** — well-structured, user-centered stories.  
- **Visual context** — prototypes and diagrams supporting understanding.  
- **Empathy and alignment** — bridging user voice and engineering execution:contentReference[oaicite:8]{index=8}:contentReference[oaicite:9]{index=9}.

Encourage students to treat this as a professional skill: transforming conversation and feedback into precise, testable requirements.
