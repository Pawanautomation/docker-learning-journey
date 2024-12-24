```mermaid
graph TB
    A[Docker Client] -->|Commands| B[Docker Daemon]
    B -->|Manages| C[Containers]
    B -->|Manages| D[Images]
    B -->|Manages| E[Networks]
    B -->|Manages| F[Volumes]
    
    G[Docker Registry] -->|Provides Images| B
    
    subgraph "Docker Host"
    B
    C
    D
    E
    F
    end
    
    style A fill:#9cf,stroke:#333
    style B fill:#f96,stroke:#333
    style G fill:#9cf,stroke:#333
    ```