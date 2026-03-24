```mermaid
graph TD;
    A[User] -->|uses| B[Web Application];
    B --> C[Server];
    C --> D[Database];
    C --> E[Cache];
    B --> F[API];
    F --> G[Third Party Service];
```