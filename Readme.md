# 📘 SDLC (Software Development Life Cycle)

## 🧩 1️⃣ What is SDLC?
SDLC (Software Development Life Cycle)** is a process used by software industries to design, develop, test, and deploy software applications.  
It defines **phases** that ensure the software meets quality standards and client requirements.

---

## ⚙️ 2️⃣ SDLC Phases

Here the typical phases of SDLC 

| **1. Requirement Gathering & Analysis** | Understand what the client needs, gather functional & non-functional requirements. |
| **2. Planning** | Estimate cost, resources, time, and risks. Create a project plan. |
| **3. Design** | Create system architecture, database design, and UI/UX wireframes. |
| **4. Development (Coding)** | Developers write code based on design documents using programming languages. |
| **5. Testing** | QA team tests the application for bugs, performance, and security issues. |
| **6. Deployment** | Software is released to production (real-world use). |
| **7. Maintenance** | Fix post-release bugs, provide updates, and improve performance. |

---

## 🧠 3️⃣ Example

👉 Example: Building a hospital management system  
- Requirement: Manage patients, doctors, and appointments  
- Planning: Time = 3 months, Team = 5 developers  
- Design: Create ER diagram and UI  
- Development: Backend (Python, .NET), Frontend (React)  
- Testing: Unit + Integration + UAT  
- Deployment: Deploy to Azure Cloud  
- Maintenance: Fix bugs and add new features

---

#  SDLC Models (Software Development Life Cycle Models)

What is an SDLC Model?
An **SDLC Model** is a structured approach or **framework** that defines how the software development process should be carried out — step by step.

Different models follow the same SDLC phases but in **different ways** (sequential, iterative, or incremental).

## 1️⃣ Waterfall Model

Definition: It is the **oldest and simplest** SDLC model. Each phase flows **downward like a waterfall**, and you move to the next phase **only after completing the previous one.**

🔄 Flow:
Requirement → Design → Development → Testing → Deployment → Maintenance

✅ Advantages:
- Simple and easy to manage  
- Works well for small projects with clear requirements  

❌ Disadvantages:
- Difficult to go back and make changes  
- Not suitable for complex or changing requirements  

## 2️⃣ Agile Model

Definition: Agile is an **iterative and incremental** model that focuses on **continuous delivery** of working software in **short cycles (Sprints)** with customer feedback.

🔄 Flow:
Requirements → Design → Development → Testing → Review → Repeat (each sprint)

✅ Advantages:
- Flexible and adaptable to changes  
- Frequent delivery of working software  
- Continuous feedback and improvement  

❌ Disadvantages:
- Needs active customer involvement  
- Can be difficult to estimate time and budget

## 3️⃣ V-Model (Verification and Validation Model)

Definition: Also known as the **Validation and Verification model**, it is an **extension of the Waterfall model.**  
Each development phase has a **corresponding testing phase**.

🔄 Flow:
Requirement ↔ Acceptance Testing  
Design ↔ System Testing  
Development ↔ Unit Testing  

✅ Advantages:
- Emphasizes testing at every stage  
- Easy to detect defects early  

❌ Disadvantages:
- Expensive for large projects  
- Rigid — not ideal for frequently changing requirements  

## 4️⃣ Iterative Model

Definition: Software is developed **in small parts (iterations)**.  
Each iteration adds new functionality and improves the previous version.

🔄 Flow:
Requirement → Design → Development → Testing → Feedback → Next Iteration

✅ Advantages:
- Early delivery of partial software  
- Easier to fix issues early  

❌ Disadvantages:
- Needs more resources  
- Managing multiple iterations can be complex  

## 5️⃣ Spiral Model

Definition: Combines **prototyping and iterative** models with a strong focus on **risk analysis** at each stage.

🔄 Flow:
Planning → Risk Analysis → Engineering → Evaluation → Repeat

✅ Advantages:
- Best for large, complex, and high-risk projects  
- Continuous risk management  

❌ Disadvantages:
- Costly due to risk analysis  
- Needs expert risk assessment team 

---

## 5️⃣ Why SDLC is Important?
- Provides clear process and structure  
- Reduces development cost and time  
- Ensures software quality and reliability  
- Helps in project tracking and risk management  


## 6️⃣ DevOps & SDLC Relationship
Traditional SDLC ends at **deployment**, but in **DevOps**, continuous monitoring, feedback, and automation are added.

## | SDLC                 | DevOps                   |
   | Manual steps         | Automated pipelines      |
   | One-time deployment  | Continuous deployment    |
   | Separate teams       | Collaboration between Dev + Ops |
   | Waterfall/Agile      | CI/CD integrated |


## 7️⃣ Real-Time Example (DevOps Project)
- **SDLC Phase:** Development → Jenkins pipeline builds app  
- **Testing:** Automated unit tests run via CI  
- **Deployment:** Containerized app pushed to Kubernetes  
- **Maintenance:** Logs monitored with Prometheus + Grafana  



## Summary
- SDLC defines **how software is planned, built, and maintained.**  
- DevOps extends SDLC by adding **automation, collaboration, and monitoring.**


