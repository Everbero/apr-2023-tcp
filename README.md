# apr-2023-tcp

```mermaid
graph TB;
    closed["ClOSED"]
    closing["CLOSING"]
    listen["LISTEN"]

    listen -->|CLOSE| closed
```