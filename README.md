# Customer Due Diligence (CDD) Flowchart Powered by LLM

This diagram illustrates the Customer Due Diligence (CDD) workflow powered by a Large Language Model (LLM). It includes data inputs, processing stages, and final output components, highlighting the relationships and data flow among all the elements.

## 🧠 Diagram Overview

- Inputs include unstructured policy documents and customer public data.
- A Large Language Model performs policy analysis and risk assessment.
- The results are compiled into a CDD Report.
- Reusable structured data is extracted from the report.
- The final output supports relationship managers in their decision-making.

## 📈 Mermaid Diagram

```mermaid
flowchart TD
    A[Unstructured<br>Policy Documents] --> B[Large Language<br>Model]
    C[Customer<br>Public Data] --> B
    B --> D[Policy Analysis]
    B --> E[Risk Assessment]
    D <--> E
    B --> F[CDD Report]
    F --> G[Relationship<br>Manager]
    F -.->|Reusable<br>structured Data| H(( ))

    style A fill:#e0e0e0,stroke:#333,stroke-width:1px
    style C fill:#e0e0e0,stroke:#333,stroke-width:1px
    style B fill:#d3d3d3,stroke:#333,stroke-width:1px
    style D fill:#e0e0e0,stroke:#333,stroke-width:1px
    style E fill:#e0e0e0,stroke:#333,stroke-width:1px
    style F fill:#d3d3d3,stroke:#333,stroke-width:1px
    style G fill:#d3d3d3,stroke:#333,stroke-width:1px

