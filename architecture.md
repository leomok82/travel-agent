```
flowchart LR
    A[JS UI] -->|Get input| B{Conversation agent Supervisor}
    B --> |More information| A                                         
    B --> L{Location Decision Agent }

    L --> D(Hotel Search tool)
    L --> G(Flight Search Tool) 
    B --> E(Time and Season tool)
    E -->B
    E --> L               
    L --> S(Social Media Tool) 
    L --> N(Recent News Tool)
    L --> F(Budgeting Tool)
    F --> B
    B --> F
    L --> B
```

![Architecture Flowchart](misc/flow.png)