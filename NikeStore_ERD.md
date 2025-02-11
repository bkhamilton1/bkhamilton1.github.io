```mermaid
erDiagram
          CUSTOMER ||--o{ PRODUCT : orders
          SALES ||--o{ INVENTORY : checks
          CUSTOMER ||--o{ SALES : queries
          PRODUCT ||--o{ INVENTORY : shipped_from
```
