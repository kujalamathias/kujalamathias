## Hi there 👋

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#fff'}}}%%
graph TD;
    style A fill:#fff,stroke:#000,stroke-width:2px;
    style B fill:#fff,stroke:#000,stroke-width:2px;
    style C fill:#fff,stroke:#000,stroke-width:2px;
    style D fill:#fff,stroke:#000,stroke-width:2px;
    style E fill:#fff,stroke:#000,stroke-width:2px;
    
    A[<div class="node-bg">Node 1</div>]
    B[<div class="node-bg">Node 2</div>]
    C[<div class="node-bg">Circular Node</div>]
    D[<div class="node-bg">Node 3</div>]
    E[<div class="node-bg">Node 4</div>]
    
    A --> B
    B --> C
    C --> D
    D --> E
