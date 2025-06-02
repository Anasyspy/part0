``` mermaid
sequenceDiagram
    participant Client
    participant Serveur
    Client->>Serveur: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    Serveur-->>Client: 302 redirection
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/notes
    Serveur-->>Client: HTML file
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Serveur-->>Client: main.css
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    Serveur-->>Client: main.js
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Serveur-->>Client: data.json
```
