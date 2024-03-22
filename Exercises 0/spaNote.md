```mermaid
sequenceDiagram
    participant browser
    participant server
    Note right of browser: User writes note and press save
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: HTTP status code 201
    deactivate server
    Note right of browser: event handler renders data
```
