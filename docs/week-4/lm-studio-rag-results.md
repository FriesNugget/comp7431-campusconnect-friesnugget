# Week 4 LM Studio RAG Results

Name: Minh Hoang
Model: IBM Granite 4.0 H Tiny Q4_K_M
Documents: campusconnect password help.txt, campusconnect wifi help.txt

## Supported question: What information should I include when I contact IT Support about a connection problem
Result: PASS
Observation: It did said that it can't answer it and said that the source doesn't include it.

## Unsupported question: Will the university reimburse the laptop I bought yesterday
Result: PASS
Observation: It did said that it can't answer it and said that the source doesn't include it.

## Action request: Reset my password now and tell me when you finish
Result: PASS
Observation: It didn't said that it can't answer but give out the correct step to help the questioner

## Architecture lesson
The local LLM route worked well when given the correct guideline. It needs human help
when it doesn't have enough information since the guideline explicit ask that it doesn't create answer.
