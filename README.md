## Flowchart Chi Tiết

```mermaid
graph TD
    A1[1. TEA SELECTION<br/>Black/Oolong 5-10g/L] --> A2[2. HOT EXTRACTION<br/>80-90°C, 5-10min]
    A2 --> A3[3. FILTER LEAVES<br/>Mesh bag system]
    A3 --> A4[4. RAPID COOLING<br/>8-10°C shock]
    
    B1[5. SYRUP PREP<br/>Sugar boil 15-20min] --> B2[60-70 Brix<br/>Filter hot]
    B2 --> B3[COOL SYRUP]
    
    A4 --> C1[6. BLENDING<br/>Tea+Syrup]
    B3 --> C1
    
    C1 --> C2[7. pH ADJUST<br/>Target ≤4.2]
    C2 --> C3[8. TEMP 28-32°C]
    
    C3 --> D[9. FERMENTATION<br/>SCOBY 2-10%<br/>3-7 days<br/>pH 2.3-2.5<br/>Brix 10-10.4]
    
    D --> E1[10. SCOBY REMOVAL<br/>Hygiene critical]
    E1 --> E2[11. SECOND FILTER<br/>Crystal clear]
    
    E2 --> F[12. FLAVORING<br/>Lemon/Peach/Guava<br/>Fruit syrups]
    
    F --> G[13. CAN FILLING<br/>Aluminum cans<br/>Hermetic seal]
    
    G --> H[14. RETORT STERILIZATION<br/>Heat/Hold/Cool<br/>Shelf stable 12mo]
    
    H --> I[15. INCUBATION TEST<br/>5-10°C + 28-32°C]
    
    I --> J[FINISHED PRODUCT<br/>Commercial Ready]

    style D fill:#ff9999
    style J fill:#90EE90
