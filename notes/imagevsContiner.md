
```mermaid
graph TD
    A[Docker Image] -->|run| B[Container 1]
    A -->|run| C[Container 2]
    A -->|run| D[Container 3]
    
    subgraph "Image Characteristics"
    E[Read-only Template]
    F[Layered Architecture]
    G[Shareable]
    end
    
    subgraph "Container Characteristics"
    H[Writable Layer]
    I[Isolated Process]
    J[Runtime Instance]
    end
    ```
    style A fill:#f96,stroke:#333
    style B,C,D fill:#9cf,stroke:#333