# Activity 2-3: From Elicitation to Use Case Modeling

## 🎯 Purpose
This activity helps students practice translating qualitative elicitation data into **structured use cases** that describe how users interact with a system.  
Students will use both **mock interview** and **job shadowing** scenarios as the basis for modeling detailed use cases, capturing **actors, preconditions, triggers, main flows, alternate flows, and postconditions**.

---

## 🧠 Learning Goals
- Identify **actors, goals, and system boundaries** from interviews or observations.  
- Draft complete use cases with **preconditions, triggers, main flows, alternates, and postconditions**.  
- Apply **active listening and note-taking skills** to confirm assumptions and separate facts from interpretations.  

---

## 🕒 Time Estimate
- 10 minutes – Instructor overview and template walkthrough  
- 30–35 minutes – Team use case drafting  
- 10–15 minutes – Peer review and reflection  

---

## 👥 Roles (Per Team of 3–4)
- **Modelers (1–2):** Drive the drafting of the use case.  
- **Reader:** Reads the scenario aloud and identifies hidden details.  
- **Analyst/QA:** Challenges assumptions and ensures completeness.  

Rotate roles between scenarios.

---

## 🧩 Materials
- The **Use Case Template** provided below  
- Notes from interviews or shadowing (simulated in this exercise)  
- Notebook or shared document for group collaboration  

---

## 📋 Use Case Template

| **Field** | **Description** |
|------------|-----------------|
| **Use Case ID/Name** | A short, descriptive name for the use case |
| **Primary Actor(s)** | Who initiates the interaction with the system |
| **Supporting Actor(s)** | Other systems or users that assist or interact |
| **Goal** | What the actor wants to achieve |
| **Preconditions** | What must be true before the use case begins |
| **Trigger** | What event or action starts the use case |
| **Main Flow** | Step-by-step sequence of actions between actor and system |
| **Alternate/Exception Flows** | Variations or errors that deviate from the main flow |
| **Postconditions** | What must be true after the use case finishes |
| **Business Rules / Constraints** | Conditions or policies that affect the use case |
| **Open Questions / Assumptions** | Items needing clarification or confirmation |

---

## 🎬 Scenarios to Model

### **Part A – Based on Mock Interviews**

#### **Scenario A1: Campus Print Credit Top-Up**
**Interview Findings:**  
Students mentioned wanting a quick, reliable way to add print credit before classes. They often forget account numbers and experience failed payments on weak campus Wi-Fi. Some want confirmation that the credit applied successfully.  

**Hints for Use Case:**  
- **Actor(s):** Student (primary), Payment System (supporting)  
- **Trigger:** Student selects “Add Print Credit” on the web portal.  
- **Possible Preconditions:** Logged into student account; payment method available.  
- **Pain Points / Gaps:** Slow connection, failed payment feedback, missing confirmation.  
- **Postconditions:** Credit added successfully or clear failure message displayed.  

---

#### **Scenario A2: Faculty Recommendation Letter Portal**
**Interview Findings:**  
Students said they’re unsure what information professors need. Faculty noted that requests often arrive incomplete or missing deadlines, requiring multiple follow-ups.  

**Hints for Use Case:**  
- **Actor(s):** Student (primary), Faculty Member, Email Service (supporting)  
- **Trigger:** Student clicks “Request Recommendation” in the portal.  
- **Pain Points / Gaps:** Missing information fields, unclear deadlines, lack of status tracking.  
- **Postconditions:** Request sent with all required details; status visible to student.  

---

### **Part B – Based on Job Shadowing**

#### **Scenario B1: Library Self-Checkout with Mixed Media**
**Observation Notes:**  
A parent with a stroller scanned several books and a DVD. The kiosk didn’t clearly indicate that DVDs require scanning both the case and the disk. Lighting glare affected the scanner. The user re-scanned items multiple times to be sure checkout succeeded.  

**Hints for Use Case:**  
- **Actor(s):** Patron (primary), Self-Checkout Kiosk (system), Library Database (supporting)  
- **Trigger:** Patron taps “Start Checkout” on kiosk.  
- **Tacit Insights:** Confusing scanner feedback, physical accessibility issues (stroller, glare), lack of clear item confirmation.  
- **Postconditions:** Items checked out, printed or digital receipt provided.  

---

#### **Scenario B2: Cafeteria Allergen-Aware Meal Kiosk**
**Observation Notes:**  
During busy lunch periods, many students skipped the allergen screen and asked staff for help. Staff referred to a laminated allergen chart taped to the counter. One student zoomed in on the kiosk because the text was too small.  

**Hints for Use Case:**  
- **Actor(s):** Student (primary), Kiosk System, Menu Database, Staff (supporting)  
- **Trigger:** Student selects “Build Your Meal.”  
- **Tacit Insights:** Accessibility issues (text size), reliance on external aids, skipped steps leading to potential health risks.  
- **Postconditions:** Order placed successfully; allergen information displayed or confirmed.  

---

## 🧭 Activity Steps

### Step 1: Review the Scenario (5 min)
Highlight key details, including user goals, pain points, and unspoken behaviors (e.g., repeated steps, shortcuts).

### Step 2: Draft the Use Case (15–20 min)
Using the template, fill out:
- Actors and roles  
- Preconditions and triggers  
- Main flow (6–10 clear, testable steps)  
- Alternate flows and exceptions  
- Postconditions and outcomes  

### Step 3: Clarify Assumptions (5–10 min)
Use **active listening techniques** in your group discussion:
- Paraphrase unclear statements.  
- Separate facts from interpretations.  
- Document all open questions and assumptions.

### Step 4: Peer Review (10 min)
Exchange your draft with another team. They should be able to understand user intent and system behavior without additional context.

---

## 📦 Deliverables
Each team submits:
1. One completed use case for a **mock interview scenario** (A1 or A2).  
2. One completed use case for a **job shadowing scenario** (B1 or B2).  
3. A short paragraph explaining **how tacit or unspoken behaviors** influenced the final use case design.  

---

## 💬 Reflection Questions
- What details from the interviews or observations changed how you defined the main flow?  
- Which alternate flows revealed the most hidden requirements?  
- How did **active listening** improve the clarity or completeness of your use case?  

---

### ✅ Outcome
By the end of this activity, students will be able to:
- Translate stakeholder insights into detailed, structured use cases.  
- Identify tacit and explicit requirements from interviews or shadowing.  
- Communicate system behavior clearly and empathetically.
