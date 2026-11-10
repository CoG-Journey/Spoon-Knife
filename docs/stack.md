```mermaid
flowchart TD
    A[Browser] -->|Compose| B(frontend\n3000:80)
    B --> C(api\n8080:8000)
    C --> D(db\ndb:5432)
    D --> |End Compose| E(pgdata volume)
```