# Instructor Guide: Exploring Formats for Acceptance Criteria

**Duration:** 45 minutes  
**Audience:** Undergraduate software engineering or requirements-gathering students  
**Workshop Theme:** Comparing checklist and Given–When–Then formats for writing acceptance criteria.

---

## Learning Objectives

By the end of the workshop, students should be able to:
1. Write acceptance criteria in both checklist and Given–When–Then (Gherkin) formats.  
2. Identify when to use simple versus complex acceptance criteria.  
3. Link textual requirements to visual design elements.  
4. Explain how acceptance criteria support communication between users, designers, developers, and testers.

---

## Preparation

- Review examples from the readings showing both simple and complex acceptance criteria:contentReference[oaicite:6]{index=6}.  
- Prepare one example user story to demonstrate each format in class.  
  **Example:**  
  > As a student, I want to check course availability so that I can avoid schedule conflicts.  

**Checklist Example:**  
- The system displays all courses with real-time seat availability.  
- Closed courses are marked “Full.”  
- Students can filter by availability.

**Gherkin Example:**  
Given the student is on the course selection page
When a course becomes full
Then it is marked “Full” in the list
And the registration button is disabled.

- Bring example prototypes (from previous sessions) to illustrate how acceptance criteria relate to user interactions.  

---

## Session Breakdown (45 minutes)

### **1. Introduction (5 minutes)**
- Review the purpose of acceptance criteria: to define clear, testable conditions for a user story to be complete.  
- Highlight how effective communication combines **textual precision** (criteria wording) and **visual clarity** (prototypes, flowcharts):contentReference[oaicite:7]{index=7}.

**Instructor Tip:**  
Show how acceptance criteria prevent misunderstandings between designers, developers, and testers.

---

### **2. Review User Stories (5 minutes)**
- Have students retrieve one user story from the previous workshop.  
- Remind them: each user story represents a single, user-focused goal.  
- Confirm they understand the story’s *who*, *what*, and *why*.

---

### **3. Write Checklist Criteria (10 minutes)**
- Guide students to list 3–5 bullet points that define success.  
- Emphasize clarity, testability, and single-purpose phrasing.  

**Instructor Observation Points:**  
- Are bullets written as measurable outcomes?  
- Do students avoid vague terms like “easy” or “intuitive”?  

Encourage peer review to ensure criteria are specific and actionable.

---

### **4. Write Given–When–Then Criteria (15 minutes)**
- Introduce Gherkin syntax and demonstrate its structure.  
- Explain that “And” statements expand detail for complex workflows:contentReference[oaicite:8]{index=8}.  
- Have students rewrite their checklist criteria using this format.  

**Instructor Demo:**  
Show an example on the board with multiple “And” conditions to illustrate how logic unfolds step by step.  

**Observation Focus:**  
- Are students using consistent tense and perspective?  
- Does each scenario clearly define the context, action, and outcome?

---

### **5. Reflection and Discussion (10 minutes)**
- Have groups exchange examples and discuss which format best fits their story.  
- Facilitate a short class discussion:  
  - When might a simple checklist suffice?  
  - When is Gherkin better for testing automation or complex logic?  
  - How do visuals (wireframes, flowcharts) support understanding of these criteria?

**Instructor Tip:**  
Encourage students to connect back to earlier work: “How would these criteria clarify your prototype from Workshop 2?”

---

## Assessment and Follow-Up

**During Class:**  
Assess groups based on:  
- Completeness of both checklist and Gherkin versions.  
- Logical, testable phrasing of acceptance criteria.  
- Integration of visuals for context.  
- Clarity and precision in communication.

**After Class:**  
Ask students to refine their acceptance criteria and include them in their evolving **requirements specification document**.  
In the next project stage, they will use these criteria for mock user testing or QA simulation.

---

## Communication Emphasis

Reinforce how communicating requirements effectively requires balancing:  
- **Visual clarity** (prototypes, flow diagrams).  
- **Textual precision** (checklists, Gherkin scenarios).  
- **Audience awareness** — adapting format to context and stakeholder needs

This workshop strengthens the link between visual design, textual definition, and shared understanding — the heart of strong requirements engineering.
