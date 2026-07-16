```mermaid
flowchart LR
    A((Employee Request))
    B[HR NHC Engagement]
    C[Administrative Affairs]
    D[Employee requester CXO]

    E(FYI: HR Engagement)
    F[FYI: Admin]
    G[FYI: Internal]

    A --> B
    B --> C
    C --> D

    D -.-> E
    D -.-> F
    D -.-> G
```
