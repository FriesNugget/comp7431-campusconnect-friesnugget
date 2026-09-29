# CampusConnect Requirements Specification v1

Status: Draft — Week 3
Student: Minh Hoang
Branch: docs/week-3-requirements-ai

## 1. Problem statement
Students who need IT Support information need a reliable way to find the correct
next step because the current experience may be scattered, difficult to search, or
hard to verify as current.

## 2. Evidence carried forward from Week 2
- E-01: Marcus tired after dealing with question that is outside of his department
- E-02: Marcus said to the student to email the correct department instead of him
- A-01: Marcus work has reduced 

## 3. One user journey inside the MVP
A student asks one typed IT Support question. CampusConnect searches only approved
IT Support material, returns a short answer with a visible source, or says the
available sources do not support an answer.

## 4. Four requirements
- FR-01 — The system shall accept one typed IT Support question.
- GR-01 — Every factual answer shall identify the approved source used.
- SF-01 — If approved sources are insufficient, the system shall not invent an
answer and shall provide a helpful IT Support next step.
- NFR-01 — A keyboard user shall be able to submit a question and read the result.

## 5. MVP boundary
IN: one typed question, approved IT Support material, one grounded answer, visible
source, safe failure, and helpful next step.
OUT: password resets, ticket creation, personal student records, voice, automatic
actions, and answers from unapproved material.

## 6. AI critique and human decision
- ChatGPT suggestion: 
Specify that when sources are insufficient, the system shall state that it cannot answer from approved sources and provide a next step explicitly identified in approved IT Support material.
- Claude suggestion: 
Mark A-01 and the Section 1 problem claims as ASSUMPTION until you can cite an approved Week 2 source, and reword A-01 as a measurable, labeled statement
- My decision: Accepted Claude, Rejected ChatGPT
- My reason: Claude response are more informative as it give out more information compare to ChatGPT that just give the general solution rather than specific
