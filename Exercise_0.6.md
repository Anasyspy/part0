``` mermaid
sequenceDiagram
    participant Client
    participant Serveur
    Client->>Serveur: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Serveur-->>Client: 201 response (Successful)
```
