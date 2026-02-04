# Kombucha Production Process

<img src="https://images.unsplash.com/photo-1623418663518-6b009d3e9488?w=400" width="120" alt="SCOBY">

## Production Flowchart

```mermaid
graph TD
    A[Tea Selection] --> B[Extraction]
    B --> C[Filtration Cooling]
    C --> D[Syrup Prep]
    D --> E[pH Adjustment]
    E --> F[Fermentation]
    F --> G[SCOBY Removal]
    G --> H[Flavoring]
    H --> I[Canning]
    I --> J[Pasteurization]
    J --> K[Quality Check]
    K --> L[Finished Product]
| Process      | Parameter   | Range   |
| ------------ | ----------- | ------- |
| Syrup        | Brix        | 60-70   |
| Start        | pH          | 4.2 max |
| End          | pH          | 2.3-2.5 |
| Fermentation | Temperature | 28-32C  |
def validate_process(ph, temp, brix):
    if ph > 4.2 or temp < 28 or temp > 32 or brix < 60:
        return "FAIL"
    return "PASS"

print(validate_process(4.0, 30, 65))  # PASS
git add README.md
git commit -m "Add kombucha flowchart v1.0"
git push origin main

## **CHÌA KHÓA THÀNH CÔNG**:
