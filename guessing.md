---
config:
  layout: elk
  look: handDrawn
  theme: dark
---
flowchart TB
  A[Start GUESSING!] --> B{Guess}
  B -->|Corect| C[YOU WIN!]
  B -->|Incorect| D[YOU LOSE...]
