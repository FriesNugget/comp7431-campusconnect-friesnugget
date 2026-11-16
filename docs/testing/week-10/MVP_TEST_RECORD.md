# Week 10 MVP Test, CI, and Freeze
Student: Minh Hoang
Date: 11/16/2026
Branch: release/week-10-rc1
Local URL: http://127.0.0.1:7860
Environment: MacOS
## 1. Six-test MVP record
| # | Quality area | Action and expected result | Observed evidence | Result |
|---|---|---|---|---|
| 1 | Supported retrieval | Ask: "How do I reset my CampusConnect password?" The answer uses the approved password-reset passage. | Guide the user step by step how to do and if fail tell the user to contact IT support| PASS |
| 2 | Citation support | Open the displayed source from Test 1. At least one important answer claim is directly supported by the source passage. | Give source for answer and source support it | PASS |
| 3 | Unsupported query | Ask: "What are the Thanksgiving dining hall hours?" The system states its IT-support limit and does not invent hours, a source, phone number, or office. | It said it didn't know and said user should ask the appropriate office | PASS |
| 4 | Voice and text fallback | Use the supported answer. If voice works, its meaning matches the visible grounded answer. If voice is unavailable, the text, source, and a clear Continue in text or retry path remain. | Both is working as intended| PASS |
| 5 | Video accessibility | Mute the tab and skip the video. AI disclosure and transcript remain visible, and the chatbot is reachable by keyboard. | Everything pass | PASS |
| 6 | Latency and recovery | Time one supported question. Class target: grounded text in 5 seconds or less. If slower, the question is preserved and progress, retry, or text fallback is clear. | Everything in order | PASS |
## 2. Lighthouse and manual accessibility evidence
Performance score: 96
Accessibility score: 95
One important Lighthouse finding or "none listed": none listed
Keyboard plus muted-video result: PASS
## 3. Defect decision and retest
Highest-severity finding: NONE
Severity: NONE
Smallest repair made: No repair required
Focused retest result: Everything work
## 4. Release gate
Release decision: GO
Decision reason: Everything pass the required test
GitHub Actions run: Pending - workflow added in Step 6
Release tag if GO: v0.9.0-rc1
## 5. Engineering and AI Use Log
What I tested myself: How to the website work and the required MVP
What remained human-reviewed rather than automated: None
Known limitation carried into Week 11 Red Teaming: None
