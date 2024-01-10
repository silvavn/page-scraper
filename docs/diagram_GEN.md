```mermaid
flowchart TB
    E[QUESTION]

    E --> H
    subgraph GENERATION
        H[LLM]
        H --> RESPONSE
    end
```