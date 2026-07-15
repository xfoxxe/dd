```mermaid
flowchart TD
    X(["Phase 2"])
    A[Sector Requester <br/>(Submit Request)] --> B[HR_NHC_Engagement Group<br/>(Approval)]
    B --> C[HR_NHC_Engagement CXO<br/>(Approval)]
    C --> D[Administrative Affairs<br/>(Total Cost Calculation)]
    D --> E[Requesting Sector CXO<br/>(Event & Cost Approval)]
    E(["Phase 2"])
    A[Administrative Affairs<br/>Request PO] --> B[Finance<br/>Approval]
    B --> C[Administrative Affairs<br/>Ready to Proceed]
    C --> D[HR<br/>FYI Notification]
    C --> E[Internal Communications<br/>FYI Notification]
    C --> F[Administrative Affairs CXO<br/>FYI Notification]
```
