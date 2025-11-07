# Turning Elicitation Data into Use Cases That Tell the User’s Story

A few years ago, I worked with a small team building a student registration system. After weeks of interviews and observations, our notebooks were bursting with quotes, screenshots, and sticky notes. But when the developers asked, “So what exactly should the system *do*?” — we realized we had a mountain of information and no clear map.  
That’s where **use cases** came in.  

Use cases act like storyboards for software. They bridge the gap between the messy, human side of requirements gathering and the structured, logical world of development.

---

## What Is a Use Case?

A **use case** is a short, structured story that describes how a user (called an *actor*) interacts with a system to achieve a specific goal. It focuses on **what** the user wants to do — not necessarily **how** the system implements it.  

Think of a use case as a conversation between a person and the system:
> The user does something → the system responds → the user continues → the system reacts.

Each use case captures one complete task or goal, like “Submit a job application,” “Track a package,” or “Reset a password.”

---

## Why Use Cases Matter

After you’ve conducted interviews, observations, or workshops, you’ll have rich data — needs, frustrations, steps, and expectations. Translating that into use cases helps:
- Clarify user goals and system boundaries  
- Align designers, developers, and stakeholders around a shared story  
- Identify missing steps, exceptions, and dependencies early  
- Create a foundation for test cases later in the project  

They’re the “living script” that turns user insights into actionable software behavior.

---

## Anatomy of a Use Case

While there are many templates, most use cases include these common sections:

| Element | Description | Example |
|----------|--------------|----------|
| **Use Case ID/Name** | A short identifier for the use case | UC-01: Submit Timesheet |
| **Actor(s)** | Who interacts with the system | Employee |
| **Goal** | The actor’s objective | Submit weekly work hours for approval |
| **Preconditions** | What must be true before it starts | Employee is logged in |
| **Trigger** | What initiates the use case | User clicks “Submit Timesheet” |
| **Main Flow (Basic Path)** | The normal step-by-step interaction | 1. User enters hours <br> 2. System validates input <br> 3. User submits <br> 4. System confirms submission |
| **Alternate/Exception Flows** | Variations or error conditions | 2a. If invalid input, system displays error message |
| **Postconditions (Outcomes)** | What’s true after completion | Timesheet is saved and marked as pending approval |

This structure keeps things consistent, readable, and easy to trace back to elicited requirements.

---

## From Raw Data to Use Cases

Here’s how to make the jump from stakeholder conversations to polished use cases:

### 1. Identify the goals hidden in your notes
Review your interview transcripts or observation notes. Highlight every action where someone said, *“I need to…”* or *“I usually…”*.  
Example:  
> “I just want to check if my payment went through without calling support.”  
→ Potential goal: *User checks payment status online.*

### 2. Define the actors
Ask: Who’s interacting with the system to achieve that goal? It might be a customer, employee, admin, or even another system.  
In the example above, the actor is *Customer*.

### 3. Outline the main steps
Walk through what the user does first, what the system does in response, and what happens next. Stick to essentials — this isn’t code, it’s storytelling with logic.

### 4. Capture exceptions
Real life rarely follows a perfect script. What if the payment fails? What if the system is down? Document these “alternate flows” — they often reveal missing requirements.

### 5. Validate with stakeholders
Share the draft use case with the people you interviewed. Ask, *“Is this what you actually do?”* or *“Would this flow make sense?”* Their feedback ensures accuracy and keeps them engaged in the process.

---

## A Quick Example

**Use Case:** UC-05: Track a Package  
**Actor:** Customer  
**Goal:** Check the delivery status of a recent order.  
**Preconditions:** Customer has an active order and tracking number.  
**Trigger:** Customer clicks “Track Package” from their order history.  

**Main Flow:**
1. Customer selects an order from their history.  
2. System retrieves tracking data from the shipping service.  
3. System displays delivery status, estimated arrival date, and tracking history.  
4. Customer closes the view or returns to the dashboard.  

**Alternate Flow:**
- 2a. If tracking data is unavailable, system displays a message: “Tracking information will be available within 24 hours.”

**Postconditions:**
- Customer has viewed the most up-to-date package status.

This use case is simple but powerful — it captures *what* happens without prescribing *how* the system handles API calls or data structures.

---

## Why It Works

When you transform elicitation data into use cases, you’re translating human stories into system logic. You’re making invisible workflows visible, and turning user voices into a language your team can build from.

A good use case doesn’t just describe functionality — it captures empathy. It shows that you’ve listened, understood, and structured the story in a way everyone can act on.

---

**Bottom Line:**  
Use cases are the connective tissue between discovery and design. They turn messy notes into clear narratives — so when developers start coding, they’re not guessing what users need… they’re following the script you helped write.
