# Codedirect

Here I will write code and save from different sources which I feel that would be important in future

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
