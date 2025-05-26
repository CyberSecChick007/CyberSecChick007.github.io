``` mermaid

---
config:
  theme:redux
---

flowchart TB

    A["How to have Good Dental Health at Home"] 
    B["Go to the Store"]
    C["Go the Dental Section"]
    D["Pick Out - Tongue Scraper - Toothbrush - Toothpaste - Mouthwash - Floss"]
    F["One| D[-Go to the bathroom -Wet your Toothbrush -Put toothpaste on your Toothbrush -Brush your teeth]
    E -->|Two| E[- Rinse your mouth out - Scrape your Tongue - Floss your teeth - Rinse your mouth out]
    G -->|Three| F[-Rinse your mouth with mouthwash for at least 1-2 minutes-Spit out mouthwash]
    D --> H {Clean Teeth} 
    E --> H 
    F --> H 
    
