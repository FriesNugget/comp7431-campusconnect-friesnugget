# Lab09 Multimodal Journey Evidence
Branch: feature/week-9-multimodal-integration
## Journey A — Supported
- Input method used: text 
- RAG answer observed: follow the correct instruction and ask " how you usually sign in to CampusConnect?"
- Citation or source observed: Lovable website
- Voice behavior: not checked
- Video remained optional: yes 
## Journey B — Unsupported
- Question used: Thanksgiving dining hall hours
- Abstention or human next step observed: said it don't have and can try to help if provide more information 
- Text fallback worked with video muted/skipped: yes 
## Traceability
- Requirement: one optional multimodal CampusConnect journey
- Files changed: src/routes/index.tsx src/routes/__root.tsx src/styles.css src/components/ui/button.tsx AGENTS.md
- Known limitation: ask a question with text on the website on top doesn't answer but with the ask AI on the bottom it can answer the question normally 
