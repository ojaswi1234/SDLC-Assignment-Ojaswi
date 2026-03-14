# DevOps Assignment 1: The "Release Manager" Roleplay

## Student Information
* **Name:** Ojaswi Bhardwaj
* **Registration No:** 12319444
* **GitHub Profile:** [ojaswi1234](https://www.github.com/ojaswi1234)
* **Course:** SDLC & DevOps Fundamentals
* **Project:** Smart-Attend Mobile App

---

## 1. The Scenario
The **Smart-Attend** mobile app is a university startup project designed to automate attendance through geo-fencing. During development, a new requirement for **Biometric (Face ID) verification** was introduced to prevent proxy attendance. This change requires a significant adjustment to the project plan, features, and design.

## 2. Why Waterfall Would Create a Crisis
Using the Waterfall model for this project would lead to serious issues:

* **Rigidity:** Waterfall operates in a straight sequence, making it difficult and messy to return to previous phases. 
* **Frozen Requirements:** Requirements are usually set at the beginning; adding Face ID mid-way would disturb the entire project flow.
* **High Cost of Change:** Developers would need to retroactively alter authentication modules, permissions, security checks, and database structures. This results in extra effort, time, and cost.
* **Delayed Testing:** Technical problems related to Face ID integration or camera permissions might only be discovered near the end of the project, causing major release delays.

## 3. Agile Pivot Using Scrum
The **Scrum framework** is a more practical choice because it is flexible and accepts change as a standard part of the process. The work is divided into two 2-week sprints:

* **Sprint 1 (MVP):** Focuses on the Minimum Viable Product, including basic UI, user login, and core geo-fencing logic.
* **Sprint 2 (Update):** Adds Biometric (Face ID) verification and improves the reporting dashboard based on feedback.

This approach allows the team to build a functional base system before adding complex security layers.

## 4. Sprint Backlog: Sprint 1

| Task ID | User Story | Priority | Est. Hours |
| :--- | :--- | :--- | :--- |
| **US01** | Student login using university ID | High | 4 |
| **US02** | Teacher real-time list of present students | High | 6 |
| **US03** | System detection of student within 10 meters | High | 8 |
| **US04** | Student notification when attendance is marked | Medium | 3 |
| **US05** | Admin manual attendance override | Low | 4 |

**Total Estimated Effort:** 25 hours.

---

## Conclusion
The Waterfall model struggles with sudden changes, leading to rework and higher costs. By contrast, **Scrum** manages the situation through short sprints, reducing project risk and making development more manageable.