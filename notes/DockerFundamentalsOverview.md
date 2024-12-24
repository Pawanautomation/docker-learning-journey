graph TD
    A[Why Containerization] --> B[History of Docker]
    B --> C[Docker Installation]
    C --> D[Inside Docker Architecture]
    D --> E[DockerHub]
    E --> F[Images vs Containers]
    
    subgraph "Core Concepts"
    A --- G[Problems Solved]
    A --- H[Benefits]
    end
    
    subgraph "Docker Architecture"
    D --- I[Docker Daemon]
    D --- J[Docker Client]
    D --- K[Docker Registry]
    end
    
    subgraph "Image & Container Relationship"
    F --- L[Image: Read-only Template]
    F --- M[Container: Running Instance]
    end