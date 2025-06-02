``` mermaid
sequenceDiagram
    participant Client
    participant Serveur
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/spa
    Serveur-->>Client: spa.html
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Serveur-->>Client: main.css
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/spa.js
    Serveur-->>Client: spa.js
    Client->>Serveur: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Serveur-->>Client: data.json
```
