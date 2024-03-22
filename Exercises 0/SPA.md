```mermaid
sequenceDiagram
    participant Browser
    participant Server

    Browser->>Server: GET request for spa, main.css, spa.js, data.json
    Server-->>Browser: Responds with status code 200 OK and requested files

```
